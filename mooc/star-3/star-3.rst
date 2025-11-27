Star Three: Open Formats
==========================================

.. include:: /_course_toc.rst

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

   <!-- Replace VIDEO_ID_STAR3 with the unlisted YouTube ID for Star 3 -->
   <div class="video-container" style="position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden; max-width: 100%;">
     <iframe src="https://www.youtube.com/embed/giL9KwJi8BI" title="Star 3: Open Formats" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;"></iframe>
   </div>


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
