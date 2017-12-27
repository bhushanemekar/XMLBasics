# XMLBasics
basics of XML, DTD, schema


======================XML Training======================
SGML
(Standard Generalized Markup Language) is a standard for how to specify a document markup language or tag set. Such a specification is itself a document type definition (DTD).

XHTML:
html pages for exchanging data. stong typing


writing well formed xml
1. root elements must be there
2. every tag should have a closing tag
3. tags are strongly case sensitive


DTD: internal or external
<!ELEMENT root (child)>

(child) only one child
(child)* one or many children
(child)? zero or one child
(child)+ atleast 1 needed

CDATA and PCDATA


http://www.quackit.com/xml/tutorial/dtd_combined_dtd.cfm

quackit.com


<!ENTITY company 'MyCompany' >

can be used at multiple places in a tag &company;
