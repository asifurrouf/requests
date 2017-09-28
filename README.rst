Requests: HTTP for Humans
=========================

Behold, the power of Requests:

.. code-block:: python

    >>> r = requests.get('https://api.github.com/user', auth=('user', 'pass'))
    >>> r.status_code
    200
    >>> r.headers['content-type']
    'application/json; charset=utf8'
    >>> r.encoding
    'utf-8'
    >>> r.text
    u'{"type":"User"...'
    >>> r.json()
    {u'disk_usage': 368627, u'private_gists': 484, ...}

See `the similar code, sans Requests <https://gist.github.com/973705>`_.

Feature Support
---------------

Requests is ready for today's web.

- International Domains and URLs
- Keep-Alive & Connection Pooling
- Sessions with Cookie Persistence
- Browser-style SSL Verification
- Basic/Digest Authentication
- Elegant Key/Value Cookies
- Automatic Decompression
- Automatic Content Decoding
- Unicode Response Bodies
- Multipart File Uploads
- HTTP(S) Proxy Support
- Connection Timeouts
- Streaming Downloads
- ``.netrc`` Support
- Chunked Requests

Requests officially supports Python 2.6–2.7 & 3.3–3.7, and runs great on PyPy.

Installation
------------

To install Requests, simply use `pipenv <http://pipenv.org/>`_ (or pip, of course):

.. code-block:: bash

    $ pipenv install requests
    ✨🍰✨

Satisfaction guaranteed.

Documentation
-------------

Fantastic documentation is available at http://docs.python-requests.org/, for a limited time only.

