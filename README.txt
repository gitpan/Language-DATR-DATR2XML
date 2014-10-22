README File For Convert::DATR2XML.pm
====================================

	* INSTALLATON
	* MANIFEST
	* COPYING
	* MORE INFO
	* AUTHOR

The DATR2XML package is a colleciton of files
to provide XML support for Sussex-standard DATR.

INSTALLATION
------------
perl Makefile.PL
make
make test
make install

MANIFEST
--------
You should recieve the following files in various directories
within this package:

	*	DATR2XML.pm
		The Perl module to convert a basic set of
		Sussex-standard DATR to XML compliant with
		the DATR1.0.dtd

	*	DATR1.0.dtd
		UTF-8-encoded XML Document Type Definition
		for Sussex-standard DATR.

	*	datr.xml
		An XML Schema created on 1 July 2000,
		I think by dtd2xsd.pl, which was downloaded from
		<http://www.w3.org/2000/04/schema_hack/dtd2xsd.pl>.
		No promises on this baby.

	*	datr.xsl
		An XSLT stylesheet to convert DATR XML back to
		it's DATR source format.

	*	datrHTML.xsl
		As datr.xsl, but produces an HTML version.

	*	datrPROLOG.xsl
		An experimental XSLT stylesheet intended to render
		DATR structures in PROLOG.  Hm.

	*	COPYING
		Yes you can, but please read this first for terms.

	*	thanks.txt
		Thanks to the people named in this file for the
		contributions copied to this file.

	*	README.txt
		You know about this one already.

	*	MANIFEST, Makefile.PL, test.pl
		Perl installation files.

COPYING
-------
Please see the included file, COPYING.

MORE INFO
---------
For more info, extract the POD from the PM:
	%>perldoc DATR2XML.pm
or
	%>pod2html --title DATR2XML DATR2XML.pm

None of this wouldn't have happend without the
help of Prof Dr Gerald Gazdar of the
Research Centre for Cognitive Science at the
University of Sussex; check his work out at
at <http://www.cogs.sussex.ac.uk>.

AUTHOR
------
Lee Goddard             mailto:lgoddard@cpan.org
Hove, East Sussex, UK   http://www.leegoddard.com/DATR
02 November 2000

London, May 2001
