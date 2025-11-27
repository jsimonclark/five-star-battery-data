Star Five: Linked Data
==========================================

.. include:: /_course_toc.rst

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

   <!-- Replace VIDEO_ID_STAR5 with the unlisted YouTube ID for Star 5 -->
   <div class="video-container" style="position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden; max-width: 100%;">
     <iframe src="https://www.youtube.com/embed/qS4qWPDYq_s" title="Star 5: Linked Data" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;"></iframe>
   </div>


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
