Star Four: Semantic Metadata
==========================================

.. contents:: Module outline
   :depth: 1
   :local:

Learning objectives
-------------------
- Describe datasets with controlled vocabularies and ontologies.
- Use machine-readable metadata (JSON-LD) to capture meaning and context.
- Model entities like materials, devices, and processes with stable identifiers.

Watch
-----

.. raw:: html

   <video controls width="100%" preload="metadata">
     <source src="star-4-video.mov" type="video/quicktime">
     Your browser does not support the video tag.
   </video>

:download:`Download the video <star-4-video.mov>`

Read (key points)
-----------------
- Ontology basics: classes, properties, IRIs.
- Minimal JSON-LD patterns for batteries (materials, cells, tests).
- How semantic tags improve search, linking, and reuse.

Do: hands-on
------------
- :doc:`Explore the notebook <star-4-notebook>` to add semantic tags to your dataset.
- :download:`Exercise worksheet <star-4-exercises.md>` to map your terms to an ontology.

Checklist
---------
- [ ] Key entities use shared identifiers (e.g., CHEBI, Wikidata, custom IRIs).
- [ ] Relationships modeled (e.g., cell uses electrode, test measures capacity).
- [ ] Metadata exported as JSON-LD alongside the data.
- [ ] Human-readable documentation describes the schema used.

Further resources
-----------------
- JSON-LD primer.
- Battery-relevant ontologies and vocabularies.
- Examples of semantic annotations in materials data.

.. toctree::
   :hidden:
   :maxdepth: 1

   star-4-notebook
