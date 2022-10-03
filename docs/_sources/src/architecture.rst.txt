.. raw:: html

   <a href="https://github.com/lifespline/samples-aws-cloudFrontDocs.git"><img loading="lazy" width="149" height="149" src="https://github.blog/wp-content/uploads/2008/12/forkme_left_darkblue_121621.png?resize=149%2C149" class="attachment-full size-full" alt="Fork me on GitHub" data-recalc-dims="1"></a>

============
Architecture
============

Docstrings are extracted both from python docstrings and from typescript doctrings. It was not possible to use `typedoc <https://github.com/mozilla/sphinx-js>` to show both py and ts docstrings in the same static pages, so typedoc is building to ``docs/typedoc``, whereas sphinx is building to ``docs``. They are both published to AWS CloudFront.

S3
--

* bucket name: ``empower-insights-docs``


CloudFront
----------

