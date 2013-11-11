<h3>MARC4J.Net</h3>
==============================

<h4>About</h4>

The goal of MARC4J.Net is to provide an easy to use Application Programming Interface (API) for working with MARC and MARCXML in C#. This project is C# translation of MARC4J project(see https://github.com/marc4j/marc4j).
MARC stands for MAchine Readable Cataloging and is a widely used exchange format for bibliographic data. MARCXML provides a loss-less conversion between MARC (MARC21 but also other formats like UNIMARC) and XML.

<h4>Features</h4>

The MARC4J.Net library includes:
<ul>
<li>An easy to use interface that can handle large record sets.</li>
<li>Readers and writers for both MARC and MARCXML.</li>
<li>A MARC record object model (like DOM for XML) for in-memory editing of MARC records.</li>
<li>Support for data conversions from MARC-8 ANSEL, ISO5426 or ISO6937 to UCS/Unicode and back.</li>
<li>A forgiving reader which can handle and recover from a number of structural or encoding errors in records.</li>
<li>Support for conversions between MARC and MARCXML.</li>
</ul>

MARC4J.Net provides readers and writers for MARC and MARCXML. A IMarcReader implementation parses input data and provides an iterator over a collection of IRecord objects. The record object model is also suitable for in-memory editing of MARC records, just as DOM is used for XML editing purposes. Using a IMarcWriter implementation it is possible to create MARC or MARCXML.

<h4>Install</h4>

Nuget package available here nuget.org/packages/MARC4J.Net:

    Install-Package MARC4J.Net

<h4>About MARC format</h4>

MARC stands for MAchine Readable Cataloguing. The MARC format is a popular exchange format for bibliographic records. The structure of a MARC record is defined in the ISO 2709:1996 (Format for Information Exchange) standard (or ANSI/NISO Z39.2-1994, available online from NISO). The MARC4J.Net API is not a full implementation of the ISO 2709:1996 standard. The standard is implemented as it is used in the MARC formats.

The most popular MARC formats are MARC21 and UNIMARC. The MARC21 format is maintained by the Library of Congress . If you’re not familiar with MARC21, you might want to read Understanding MARC Bibliographic , “a brief description and tutorial” on the standard. For more information on the MARC21 format, visit the MARC formats home page at the Library of Congress Web site. For more information about UNIMARC visit the UNIMARC Manual .
Related resources

