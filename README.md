
## Pre-requisites

There is currently only 1 version of this course - in Python.  The longer term hope is for there to be an R, and perhaps other language, versions too.

### Python

I will be using Python version 3, so use `python --version` to see if your version is recent enough.  You may get a different answer running `python3 --version` - although do not worry if `python3` results in `Command not found`.

You will also need a functioning [VirtualEnv] system - make sure `virtualenv --version` says it is newer than version 1.9.  If you get `Command not found` you will need to install it.

[VirtualEnv]: https://virtualenv.pypa.io/en/latest/

We will also be using some specific libraries in addition to the ones that come with Python:
+ pandas

You do not need to worry about installing these yet - as long as Python and VirtualEnv are installed the rest in the workshop set-up.

## Dataset

For this course we will be using the [UK National Indicators data set] from October 2010.

This dataset is released under the [Open Government Licence] which permits me to "copy, publish, distribute and transmit the Information" and "exploit the Information commercially and non-commercially for example, by combining it with other Information, or by including it in your own product or application" provided I "acknowledge the source of the Information in your product or application by including or linking to any attribution statement specified by the Information Provider(s) and, where possible, provide a link to this licence".  As permitted by this licence an unmodified copy of the dataset is included in `data/HubDownloadOct2010.xls` for your convenience.

[UK National Indicators data set]: https://webarchive.nationalarchives.gov.uk/20111004125058/http:/www.places.communities.gov.uk/NewsPages/News_Documents/HubDownloadOct2010.xls
[Open Government Licence]: http://www.nationalarchives.gov.uk/doc/open-government-licence/version/3/

