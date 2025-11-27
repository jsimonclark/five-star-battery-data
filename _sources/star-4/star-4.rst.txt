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

   <!-- Replace VIDEO_ID_STAR4 with the unlisted YouTube ID for Star 4 -->
   <div class="video-container" style="position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden; max-width: 100%;">
     <iframe src="https://www.youtube.com/embed/VIDEO_ID_STAR4" title="Star 4: Semantic Metadata" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;"></iframe>
   </div>

.. note::

   Add your unlisted YouTube URL by replacing ``VIDEO_ID_STAR4`` in the embed above.

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
