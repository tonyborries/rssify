rssify.py
=========

Rssify builds an RSS Feed from a directory of files. 

    Usage: /opt/rssify/rssify.py [ -h ] [ -v ] -o outfile -i inputdir -b url
    -h, --help        Show this usage message and exit.
    -v, --verbose     Verbose Output to StdErr.
    -i, --inputdir    Source Directory of files to build into RSS.
    -o, --output      Output File - where to store the RSS File.
    -b, --basepath    URL path prepended to files to build the full path


### Example Invocation

rssify.py -o tonyb.xml -i files/ -b "http://example.com/rss/files"

* tonyb.xml - The output RSS XML
* files/ - directory of media files
* http://example.com/rss/files - URL corresponding to the files/ directory


### Compatibility

Not seeking to necessarily be a full-featured tool, compatibility may vary 
among RSS aggregators - this has currently only been tested with Casts on iOS. 


### Required Modules

(See requirements.txt for a complete listing.) This script uses: 

* PyRSS2Gen (https://pypi.python.org/pypi/PyRSS2Gen/1.1)


### Notes and Known Issues

None.


### License

The MIT License (MIT)

Copyright (c) 2015-2016 tonyborries

Permission is hereby granted, free of charge, to any person obtaining a copy of
this software and associated documentation files (the "Software"), to deal in
the Software without restriction, including without limitation the rights to
use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of
the Software, and to permit persons to whom the Software is furnished to do so,
subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS
FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR
COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER
IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN
CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

