### WRITE thesaurus

The **WRITE Thesaurus** is a carefully curated resource dedicated to Chinese cultural heritage, with a particular focus on contemporary arts and calligraphy. Developed by domain experts as part of the WenDAng project, this thesaurus, modelled in SKOS, provides a structured vocabulary that captures the evolving landscape of Chinese (contemporary) calligraphy and its role in redefining cultural identity.  
Designed as both a research tool for WRITE scholars and a comprehensive reference for a wider audience, the thesaurus categorises key concepts essential to understanding traditional and contemporary Chinese artistic expressions. By offering precise definitions and classifications, it serves as a bridge between traditions and emerging artistic practices in contemporary China.  

It is developed and maintained within the **WenDAng - WRITE Digital Archive project**.


📅 **Latest version:** v1.1.0 (2025-10-12)  
📘 **Full changelog:** [View CHANGELOG.md →](CHANGELOG.md)

---

### Access

The WRITE Thesaurus can be accessed through:

- 🌐 **/DH.arc Vocabularies:** [https://lab.dharc.unibo.it/skosmos/wt/en/](https://lab.dharc.unibo.it/skosmos/wt/en/)  
  *A user-friendly web interface for browsing and searching concepts, implemented using Skosmos.*

- 🧾 **Zenodo:** [https://doi.org/10.5281/zenodo.17243418](https://doi.org/10.5281/zenodo.17243418)  
  *Archived version of the thesaurus with DOI and metadata for citation.*

- 🔗 **w3id Persistent URI:** [https://w3id.org/write/thesaurus](https://w3id.org/write/thesaurus)  
  *Permanent and resolvable URIs for each concept.*

- 💻 **GitHub Repository:** [https://github.com/WenDAng-project/thesaurus](https://github.com/WenDAng-project/thesaurus)  
  *Latest version, RDF data, and documentation.*

---

### Structure

The WRITE thesaurus is modelled using **SKOS**.  
Each term is a `skos:Concept`, linked to a dedicated collection through `skos:member`, and to the thesaurus via `skos:inScheme`.

Each concept must include at least:  
- a `skos:prefLabel`  
- one or more `skos:altLabel`(s)  
- a `skos:definition` 

Semantic relations, external mappings and bibliographic references are recommended, but not mandatory.

---

### Contact
Katarina Lučić - PhD candidate  
Department of Interpreting and Translation, University of Bologna (Italy)    
📧 katarina.lucic2@unibo.it

---

### License
This work is licensed under the [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).
