.. raw:: html

   <a href="https://github.com/lifespline/samples-aws-cloudFrontDocs.git"><img loading="lazy" width="149" height="149" src="https://github.blog/wp-content/uploads/2008/12/forkme_left_darkblue_121621.png?resize=149%2C149" class="attachment-full size-full" alt="Fork Me On Github" data-recalc-dims="1"></a>

===========
Development
===========

Docs Structure
--------------

.. code-block::

   docs
    ├── sphinx
    │   ├── src
    │   ├── static
    │   ├── index.rst
    │   └── <sphinx files>
    ├── .nojekyll
    └── <build static files>

Images
------

Images are contained in ``docs/sphinx/static/img/``.

Task Runner
-----------

`invoke <https://www.pyinvoke.org/>`_ is the task runner used to build the docs.
