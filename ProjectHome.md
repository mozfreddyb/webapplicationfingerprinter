WAFP is a Web Application Finger Printer written in ruby using a SQLite3 DB.

How it works?
--
WAFP fetches the files given by the Finger Prints from a webserver and
checks if the checksums of those files are matching to the given checksums from the
Finger Prints. This way it is able to detect the detailed version and
even the build number of a Web Application.

In detail?
--
A Web Application Finger Print consits of a set of relative file locations
in conjunction with their md5sums. It is made based on a production or example
installation of a Web Application or just out of an extracted Web Application
install files tarball.