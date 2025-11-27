Star Five: Linked Data
==========================================

.. contents:: Module outline
   :depth: 1
   :local:

Learning objectives
-------------------
- Link your dataset to external knowledge graphs and identifiers.
- Publish resolvable URIs for entities in your data.
- Expose machine-readable endpoints or files that enable federation.

Watch
-----

.. raw:: html

   <video controls width="100%" preload="metadata">
     <source src="star-5-video.mov" type="video/quicktime">
     Your browser does not support the video tag.
   </video>

:download:`Download the video <star-5-video.mov>`

Read (key points)
-----------------
- What “linking” means: outbound links to DOIs, Wikidata, CHEBI, ORCID.
- Stable, resolvable identifiers for your own entities.
- Lightweight publishing patterns: JSON-LD with @id, small SPARQL endpoints, or static RDF dumps.

Do: hands-on
------------
- :doc:`Work through the notebook <star-5-notebook>` to add outbound links and IDs.
- :download:`Exercise worksheet <star-5-exercises.md>` to plan link targets and persistence.

Checklist
---------
- [ ] Entities in your data have stable, resolvable URIs.
- [ ] Outbound links to authoritative identifiers added where possible.
- [ ] Machine-readable export (JSON-LD/RDF) published with the dataset.
- [ ] Links validated (no broken or non-resolving IDs).

Further resources
-----------------
- Linked Data principles.
- URI design guidelines.
- Examples of linked battery and materials datasets.

.. toctree::
   :hidden:
   :maxdepth: 1

   star-5-notebook
