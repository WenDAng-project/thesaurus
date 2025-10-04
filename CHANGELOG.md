# Changelog 

The **WRITE Thesaurus** is a carefully curated resource dedicated to Chinese cultural heritage, with a particular focus on contemporary arts and calligraphy. Developed by domain experts as part of the WenDAng project, this thesaurus, modelled in SKOS, provides a structured vocabulary that captures the evolving landscape of Chinese (contemporary) calligraphy and its role in redefining cultural identity.
Designed as both a research tool for WRITE scholars and a comprehensive reference for a wider audience, the thesaurus categorises key concepts essential to understanding traditional and contemporary Chinese artistic expressions. By offering precise definitions and classifications, it serves as a bridge between traditions and emerging artistic practices in contemporary China. 

Versioning of the WRITE Thesaurus follows [Semantic Versioning](https://semver.org/), and this changelog documents all notable updates, additions, and revisions across releases.

## [v1.0.0] – 2025-04-01
**Initial release**

The first version of the WRITE thesaurus includes 90 terms organised in 6 thematic groups [skos:Collection] - Chinese Concepts, Chinese Visual Elements, Script Styles, Graffiti Genres, Graffiti Types and Graffiti Styles.
Each term is a skos:Concept, linked to a dedicated collection through skos:member, and to the thesaurus via skos:inScheme.
Each concept must include at least: a skos:prefLabel, one or more skos:altLabel(s) and a skos:definition. Semantic relations, external mappings and bibliographic resource are recommended.

Some of the concepts in the WRITE thesaurus were mapped to the external concepts schemes, such as Chinese Iconography Thesaurus, INDIGO Graffiti Thesaurus and Getty Art & Architecture Thesaurus.

Besides this GitHub repository, the thesaurus is accessible via [/DH.arc Vocabularies](https://lab.dharc.unibo.it/skosmos/wt/en/), [Zenodo](https://zenodo.org/doi/10.5281/zenodo.17243419), and [w3id](https://w3id.org/write/thesaurus).
