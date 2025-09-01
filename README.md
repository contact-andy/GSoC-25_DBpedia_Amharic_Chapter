# GSoC-25: DBpedia Amharic Chapter  

## Project Summary  
Amharic Wikipedia lacks structured knowledge representation, which limits its integration into global knowledge graphs like DBpedia. This gap hinders the accessibility, discoverability, and interoperability of Amharic content in multilingual semantic web applications.  

This project proposes to enhance the **Amharic chapter of DBpedia** by extracting structured data from Amharic Wikipedia. It involves extending the DBpedia Extraction Framework to support Amharic, creating new mappings for infobox templates, and extracting rich semantic data such as citations, disambiguations, and anchor texts.  

The output will be published as **RDF triples** and made accessible via a user-friendly web interface, following **FAIR (Findable, Accessible, Interoperable, Reusable)** data principles.  

---

## Key Achievements and Deliverables  

  ### Wikipedia Templates and Pages 

  During the project, several Wikipedia templates and pages were created or updated to support structured knowledge representation in Amharic Wikipedia. These efforts form the foundation for DBpedia mappings.

  #### Summary of Work Completed

  | Category              | Count | Remark                                                                 |
  |-----------------------|-------|------------------------------------------------------------------------|
  | New Template Created  | 23    | Total: 23 templates. Expected to update the existing templates in the future. |
  | Updated Templates     | 0     |                                                                        |
  | New Pages Created     | 11    | Total: 24 pages                                                        |
  | Updated Pages         | 13    |                                                                        |

  The complete list of created and updated templates is provided in [Appendix A](https://github.com/AmharicDBpedia/AmharicDBpedia/blob/GSOC2025/documentation/GSoC%202025%20Documentation%20v1.0.pdf), while the list of created and updated Wikipedia pages is included in [Appendix B](https://github.com/AmharicDBpedia/AmharicDBpedia/blob/GSOC2025/documentation/GSoC%202025%20Documentation%20v1.0.pdf). These appendices include both the names and direct links to each resource for easy verification and further exploration.


  ### Mapping Coverage Progress  [View Amharic Mapping](https://mappings.dbpedia.org/index.php/Mapping_am)

  The mapping activity for Amharic DBpedia has shown significant progress compared to the previous status.

  #### Coverage Summary

  - **Previous Coverage**: 17 mapped templates  
  - **Current Coverage**: 97 mapped templates

  ##### Breakdown of the 97 Mapped Templates

  - **65 Templates** are in **Amharic** and actively aligned with pages in Amharic Wikipedia.
  - **24 Templates** are in **English**. These were added primarily to ensure **backward compatibility** with existing Wikipedia pages that rely on English-based infoboxes.  
    - While this maintains the link between DBpedia mappings and the pages, these templates will require **future translation into Amharic** both in Wikipedia and in DBpedia mappings.
  - **8 Templates** are **redirects** to other templates. These are included in the total but do not represent unique templates.
  - A small number of mapped templates **do not yet have related Wikipedia pages**, which explains their exclusion from current mapping statistics.  
    - These templates are retained to support **potential future use**.

  #### Key Improvements

  - Expanded from **17 → 97** mapped templates — representing **more than a 5× increase** in coverage.
  - Significant growth in **Amharic-native template support**, strengthening local knowledge representation.
  - Maintained **compatibility with English templates** to preserve continuity, with **translation work identified** as a next step.

  #### Appendix

  A detailed breakdown of the created and updated template mappings, including direct links to each, is provided in [Appendix C](https://github.com/AmharicDBpedia/AmharicDBpedia/blob/GSOC2025/documentation/GSoC%202025%20Documentation%20v1.0.pdf).


- **Template & Mapping Improvements**  
  - Analyzed old statistics report, identified template limitations and mapping issues, proposed solutions, and executed them successfully.  
  - Managed **Amharic ignore list** (templates and properties excluded from statistics). Suggested additional templates for the ignore list.  
  - Generated statistics locally with `infobox-properties` file (replacing `infobox_test`).  

- **GitHub Contributions**  
  - Updated **amharic mappings**, **mapping statistics report**, and **ignore list** has been submitted as a PR. [view change list](https://github.com/dbpedia/extraction-framework/pull/781)  
  - New way of generating mapping statistics locally with `infobox-properties` file (replacing `infobox_test`) to be submitted as a PR.[View change list](https://github.com/contact-andy/extraction-framework/tree/local-stats-generation)

- **Documentation** 
  - Provided a comprehensive **guide for creating, mapping, and extracting structured data** from Amharic Wikipedia using the DBpedia Extraction Framework.  
  - Covers the **end-to-end workflow**:  
    - Creating and updating Wikipedia templates  
    - Defining mappings  
    - Generating statistics  
    - Running extractions  
    - Querying the resulting knowledge graph  
  - Includes **challenges, solutions, and recommendations** to improve coverage and quality.  
  - Designed to help **contributors, mentors, and researchers** reproduce, extend, and contribute effectively to the Amharic DBpedia chapter.  

Read the documentation here: [GSoC 2025 Documentation](https://github.com/AmharicDBpedia/AmharicDBpedia/blob/GSOC2025/documentation/GSoC%202025%20Documentation%20v1.0.pdf)  

---

## Blog
Throughout the project, progress and milestones have been documented in weekly blog posts. These blogs detail the technical steps, challenges faced, and solutions implemented.  

Read the blog here: [GSoC 2025 DBpedia Amharic Blog](http://contact-andy.github.io/gsoc-2025-dbpedia)  

---

## Next Steps  
- Expand mappings to cover more Amharic Wikipedia templates.  
- Finalize and merge PRs for updated statistics and ignore list.  
- Improve automation with **LLM/NLLB translation pipelines**.  
- Engage the **Amharic Wikipedia community** for validation and refinement.  
- Work toward **DBpedia Live integration** for Amharic.  

---

This project lays the foundation for a **fully functional Amharic DBpedia chapter**, bridging the knowledge gap for underrepresented languages and enriching the global Semantic Web.  
