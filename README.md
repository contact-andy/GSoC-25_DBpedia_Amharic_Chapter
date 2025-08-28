# GSoC-25: DBpedia Amharic Chapter  

## Project Summary  
Amharic Wikipedia lacks structured knowledge representation, which limits its integration into global knowledge graphs like DBpedia. This gap hinders the accessibility, discoverability, and interoperability of Amharic content in multilingual semantic web applications.  

This project proposes to enhance the **Amharic chapter of DBpedia** by extracting structured data from Amharic Wikipedia. It involves extending the DBpedia Extraction Framework to support Amharic, creating new mappings for infobox templates, and extracting rich semantic data such as citations, disambiguations, and anchor texts.  

The output will be published as **RDF triples** and made accessible via a user-friendly web interface, following **FAIR (Findable, Accessible, Interoperable, Reusable)** data principles.  

### Deliverables  
- An **Amharic-compatible extension** to the DBpedia Extraction Framework.  
- New **infobox mapping templates** for Amharic Wikipedia.  
- An **automated extraction pipeline** with support for citations, disambiguation, topical concepts, and personal data.  
- A **structured knowledge graph** (RDF triples) linked with English DBpedia and Wikidata.  
- A lightweight **web interface** with SPARQL querying and multilingual support.  
- Comprehensive **documentation** covering setup, usage, and FAIR-compliant publishing.  

---

## Key Achievements and Deliverables  

- **Wikipedia Templates and Pages**  
  - New Templates Created: **23**  
  - New Pages Created: **11**  
  - Updated Pages to support templates: **13**  

- **Mapping Coverage Progress**  [View Amharic Mapping](https://mappings.dbpedia.org/index.php/Mapping_am)
  - Previous Coverage: **17** mapped templates  
  - Current Coverage: **97** mapped templates   

- **Template & Mapping Improvements**  
  - Analyzed old statistics report, identified template limitations and mapping issues, proposed solutions, and executed them successfully.  
  - Managed **Amharic ignore list** (templates and properties excluded from statistics). Suggested additional templates for the ignore list.  
  - Generated statistics locally with `infobox-properties` file (replacing `infobox_test`).  

- **GitHub Contributions (Pending/Planned PRs)**  
  - New **mapping statistics report** and updated **ignore list** to be submitted as a PR.  

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

Read the documentation here: [GSoC 2025 Documentation](https://drive.google.com/file/d/1QO0FRSY1AEremEUcky7IG6AgXtnotbig/view?usp=drive_link)  

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
