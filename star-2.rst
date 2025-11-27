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

   <video controls width="100%" preload="metadata">
     <source src="star-2-video.mp4" type="video/mp4">
     Your browser does not support the video tag.
   </video>

:download:`Download the video <star-2-video.mp4>`

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
