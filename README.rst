#######
LDM-129
#######

=====================================
Data Management Infrastructure Design
=====================================

This is a working repository for *LDM-129: Data Management
Infrastructure Design*.

* Read the living document on the web: http://ldm-129.readthedocs.org 
* Read the officially-approved document:
  https://docushare.lsstcorp.org/docushare/dsweb/ServicesLib/LDM-152/History

Working with this document
--------------------------

.. code::

   git clone git@github.com:lsst/LDM-129.git
   cd LDM-129
   pip install -r requirements.txt
   make html

The built site can be viewed by opening ``_build/html/index.html`` in
your web browser.

Whenever you push to ``master``, readthedocs.org will build and host the
document at http://ldm-129.readthedocs.org

Editing metadata
----------------

Metadata, such as document version, title, date of last edit, and
authors, are maintained in the ``metadata.yaml`` file
