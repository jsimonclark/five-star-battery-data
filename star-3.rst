Star Three: Open Formats
==========================================

.. contents:: Module outline
   :depth: 1
   :local:

Learning objectives
-------------------
- Choose open, non-proprietary formats for data and metadata.
- Convert legacy/binary exports into interoperable files.
- Verify files remain readable without specialized software.

Watch
-----

.. raw:: html

   <video controls width="100%" preload="metadata">
     <source src="star-3-video.mov" type="video/quicktime">
     Your browser does not support the video tag.
   </video>

:download:`Download the video <star-3-video.mov>`

Read (key points)
-----------------
- Preferred formats: CSV/TSV, JSON, Parquet for data; JSON-LD/YAML for metadata.
- Avoiding lock-in: why not XLSX-only or proprietary binaries.
- Round-tripping: ensure conversions preserve types, units, and encoding.

Do: hands-on
------------
- :doc:`Run the notebook <star-3-notebook>` to convert binary exports into open formats.
- :download:`Exercise worksheet <star-3-exercises.md>` to plan format choices for your lab.

Checklist
---------
- [ ] Core data available in at least one open, documented format.
- [ ] Character encoding is UTF-8.
- [ ] Conversions validated (row counts, checksums, spot checks on types/units).
- [ ] No required proprietary reader to access the data.

Further resources
-----------------
- Open data format guides.
- Parquet/Arrow basics for columnar data.
- Encoding and locale pitfalls to watch for.

.. toctree::
   :hidden:
   :maxdepth: 1

   star-3-notebook
