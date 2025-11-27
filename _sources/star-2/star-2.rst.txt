Star Two: Structured Data
==========================================

.. contents:: Module outline
   :depth: 1
   :local:

Learning objectives
-------------------
- Reshape raw battery data into tidy, well-typed tables.
- Separate data from presentation (no merged cells, no embedded charts).
- Capture units and measurement context alongside values.

Watch
-----

.. raw:: html

   <!-- Replace VIDEO_ID_STAR2 with the unlisted YouTube ID for Star 2 -->
   <div class="video-container" style="position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden; max-width: 100%;">
     <iframe src="https://www.youtube.com/embed/VIDEO_ID_STAR2" title="Star 2: Structured Data" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;"></iframe>
   </div>

.. note::

   Add your unlisted YouTube URL by replacing ``VIDEO_ID_STAR2`` in the embed above.

Read (key points)
-----------------
- Principles of tidy data (rows = observations, columns = variables).
- Consistent headers, units, and value types.
- Recording provenance: instrument, operator, and run parameters.

Do: hands-on
------------
- :doc:`Follow the notebook <star-2-notebook>` to structure a raw cycler export.
- :download:`Exercise worksheet <star-2-exercises.md>` to design your table schema.

Checklist
---------
- [ ] One row per observation, one column per variable.
- [ ] Units documented and consistent.
- [ ] Provenance (who, when, how) recorded with the dataset.
- [ ] No embedded formulas or charts in the data file.

Further resources
-----------------
- Tidy data primer.
- Example structured battery cycling dataset.
- Checklist for provenance capture.

.. toctree::
   :hidden:
   :maxdepth: 1

   star-2-notebook
