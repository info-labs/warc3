warc: Python library to work with WARC files
============================================

WARC (Web ARChive) is a file format for storing web crawls.

http://www.scribd.com/doc/4303719/WARC-ISO-28500-final-draft-v018-Zentveld-080618

The `warc` library makes it very easy to work with WARC files.

    import warc
    f = warc.open("test.warc")
    for record in f:
        print record['WARC-Target-URI'], record['Content-Length']

Documentation
-------------

The documentation of the warc library is available at http://readthedocs.org/docs/warc/en/latest/
