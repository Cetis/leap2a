<div id="container">

<div id="header">

[leap2](../index.html): learner-ownable information
===================================================

</div>

<div id="content">

Namespace
=========

The namespace for Leap2 from 2016 onwards is
http://www.cetis.org.uk/leap2/terms/ and that lands here on this index
page.

The conventional namespace abbreviation is **leap2:**

Table of Leap2 terms
====================

This page is informative of the terms used in the leap2: namespace.\
Along with leap2: terms, other terms from Atom used for Leap2A are
listed.

For documentation on the use of the terms in Leap2A, please click on the
link in the leftmost column.

Terms used in Leap2A with leap2: as namespace (N) or as prefix (P)
------------------------------------------------------------------

-   Terms used with leap2: as a namespace (N) occur as element or
    attribute names.
-   Terms used with leap2: as prefix (P) occur as attribute values or
    text nodes.

  -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
  Leap2A\                                                       URI\                                                         type of term                         containing element                                  degradation or more\       notes
  link                                                          link                                                                                                                                                  general type or relation   
  --------------------------------------------------------- --- ------------------------------------------------------------ ------------------------------------ --------------------------------------------------- -------------------------- --------------------------
  [ability](ability)                                        P   [uri](http://www.cetis.org.uk/leap2/terms/ability)           [item type](../a/types)              rdf:type                                            leap2:entry                 

  [achievement](achievement)                                P   [uri](http://www.cetis.org.uk/leap2/terms/achievement)       [item type](../a/types)              rdf:type                                            leap2:entry                 

  [activetime](activetime)                                  N   [uri](http://www.cetis.org.uk/leap2/terms/activetime)        [literal element](../a/literals)     atom:entry                                          append to content           

  [activity](activity)                                      P   [uri](http://www.cetis.org.uk/leap2/terms/activity)          [item type](../a/types)              rdf:type                                            leap2:entry                 

  [addressline](../a/literals#addressline)                  N   [uri](http://www.cetis.org.uk/leap2/terms/addressline)       [literal element](../a/literals)     leap2:spatial                                       append to spatial           

  [affiliation](../a/types/affiliation)                     P   [uri](http://www.cetis.org.uk/leap2/terms/affiliation)       [item type](../a/types)              rdf:type                                            leap2:entry                 

  [attended\_by](../a/relationships#attended_by)            P   [uri](http://www.cetis.org.uk/leap2/terms/attended_by)       [relationship](../a/relationships)   atom:link                                           leap2:supported\_by         

  [attends](../a/relationships#attends)                     P   [uri](http://www.cetis.org.uk/leap2/terms/attends)           [relationship](../a/relationships)   atom:link                                           leap2:supports              

  [country](../a/literals#country)                          N   [uri](http://www.cetis.org.uk/leap2/terms/country)           [literal element](../a/literals)     leap2:spatial                                       append to spatial           

  [countrycode](../a/literals#countrycode)                  N   [uri](http://www.cetis.org.uk/leap2/terms/countrycode)       attribute                            leap2:country                                       append to spatial           

  [date](../a/literals#date)                                N   [uri](http://www.cetis.org.uk/leap2/terms/date)              [literal element](../a/literals)     atom:entry                                          append to content           

  [display\_order](../a/literals#display_order)             N   [uri](http://www.cetis.org.uk/leap2/terms/display_order)     attribute                            atom:link                                           append to content           

  [entry](../a/types/entry)                                 P   [uri](http://www.cetis.org.uk/leap2/terms/entry)             [item type](../a/types)              rdf:type                                                                       see [Atom](#atomentry)

  [field](../a/literals#field)                              N   [uri](http://www.cetis.org.uk/leap2/terms/field)             attribute                            [leap2:persondata](../a/specification#data); etc.   append to content           

  [has\_agenda](../a/relationships#has_agenda)              P   [uri](http://www.cetis.org.uk/leap2/terms/has_agenda)        [relationship](../a/relationships)   atom:link                                           leap2:supported\_by         

  [has\_evidence](../a/relationships#has_evidence)          P   [uri](http://www.cetis.org.uk/leap2/terms/has_evidence)      [relationship](../a/relationships)   atom:link                                           leap2:supported\_by         

  [has\_outcome](../a/relationships#has_outcome)            P   [uri](http://www.cetis.org.uk/leap2/terms/has_outcome)       [relationship](../a/relationships)   atom:link                                           leap2:supports              

  [has\_part](../a/relationships#has_part)                  P   [uri](http://www.cetis.org.uk/leap2/terms/has_part)          [relationship](../a/relationships)   atom:link                                           leap2:relation              

  [has reply](../a/relationships#has_reply)                 P   [uri](http://www.cetis.org.uk/leap2/terms/has_reply)         [relationship](../a/relationships)   atom:link                                           leap2:relation             see [Atom](#replies)

  [in\_reply\_to](../a/relationships#in_reply_to)           P   [uri](http://www.cetis.org.uk/leap2/terms/in_reply_to)       [relationship](../a/relationships)   atom:entry                                          leap2:relation             see [Atom](#in-reply-to)

  [is\_agenda\_of](../a/relationships#is_agenda_of)         P   [uri](http://www.cetis.org.uk/leap2/terms/is_agenda_of)      [relationship](../a/relationships)   atom:link                                           leap2:supports              

  [is\_evidence\_of](../a/relationships#is_evidence_of)     P   [uri](http://www.cetis.org.uk/leap2/terms/is_evidence_of)    [relationship](../a/relationships)   atom:link                                           leap2:relation              

  [is\_outcome\_of](../a/relationships#is_outcome_of)       P   [uri](http://www.cetis.org.uk/leap2/terms/is_outcome_of)     [relationship](../a/relationships)   atom:link                                           leap2:supported\_by         

  [is\_part\_of](../a/relationships#is_part_of)             P   [uri](http://www.cetis.org.uk/leap2/terms/is_part_of)        [relationship](../a/relationships)   atom:link                                           leap2:relation              

  [label](../a/literals#label)                              N   [uri](http://www.cetis.org.uk/leap2/terms/label)             attribute                            [leap2:persondata](../a/specification#data); etc.   append to content          see [Atom](#atomlabel)

  [meeting](../a/types/meeting)                             P   [uri](http://www.cetis.org.uk/leap2/terms/meeting)           [item type](../a/types)              rdf:type                                            leap2:activity              

  [myrole](../a/literals#myrole)                            N   [uri](http://www.cetis.org.uk/leap2/terms/myrole)            [literal element](../a/literals)     atom:entry                                          append to content           

  [organization](../a/types/organization)                   P   [uri](http://www.cetis.org.uk/leap2/terms/organization)      [item type](../a/types)              rdf:type                                            leap2:entry                 

  [orgdata](../a/specification#orgdata)                     N   [uri](http://www.cetis.org.uk/leap2/terms/orgdata)           blank node                           atom:entry(organization)                            append to content           

  [person](../a/types/person)                               P   [uri](http://www.cetis.org.uk/leap2/terms/person)            [item type](../a/types)              rdf:type                                            leap2:entry                 

  [persondata](../a/specification#persondata)               N   [uri](http://www.cetis.org.uk/leap2/terms/persondata)        blank node                           atom:entry(person)                                  append to content           

  [plan](../a/types/plan)                                   P   [uri](http://www.cetis.org.uk/leap2/terms/plan)              [item type](../a/types)              rdf:type                                            leap2:entry                 

  point                                                     N   [uri](http://www.cetis.org.uk/leap2/terms/point)             attribute                            [leap2:date](../a/literals#date)                    append to date label        

  [postcode](../a/literals#postcode)                        N   [uri](http://www.cetis.org.uk/leap2/terms/postcode)          [literal element](../a/literals)     leap2:spatial                                       append to spatial           

  [publication](../a/types/publication)                     P   [uri](http://www.cetis.org.uk/leap2/terms/publication)       [item type](../a/types)              rdf:type                                            leap2:resource              

  [reflected\_on\_by](../a/relationships#reflected_on_by)   P   [uri](http://www.cetis.org.uk/leap2/terms/reflected_on_by)   [relationship](../a/relationships)   atom:link                                           leap2:relation              

  [reflects\_on](../a/relationships#reflects_on)            P   [uri](http://www.cetis.org.uk/leap2/terms/reflects_on)       [relationship](../a/relationships)   atom:link                                           leap2:relation              

  [relation](../a/relationships#relation)                   P   [uri](http://www.cetis.org.uk/leap2/terms/relation)          [relationship](../a/relationships)   atom:link                                           append link to content     see [Atom](#related)

  [resource](../a/types/resource)                           P   [uri](http://www.cetis.org.uk/leap2/terms/resource)          [item type](../a/types)              rdf:type                                            leap2:entry                 

  [roleid](../a/literals#roleid)                            N   [uri](http://www.cetis.org.uk/leap2/terms/roleid)            [literal element](../a/literals)     atom:entry                                          append to content           

  [selection](../a/types/selection)                         P   [uri](http://www.cetis.org.uk/leap2/terms/selection)         [item type](../a/types)              rdf:type                                            leap2:entry                 

  [service](../a/literals#service)                          N   [uri](http://www.cetis.org.uk/leap2/terms/service)           attribute                            [leap2:persondata](../a/specification#data); etc.   append to content           

  [spatial](../a/literals#spatial)                          N   [uri](http://www.cetis.org.uk/leap2/terms/spatial)           [literal element](../a/literals)     atom:entry                                          append to content           

  stage                                                     N   [uri](http://www.cetis.org.uk/leap2/terms/stage)             attribute                            [leap2:status](../a/literals#status)                append to content           

  [status](../a/literals#status)                            N   [uri](http://www.cetis.org.uk/leap2/terms/status)            [literal element](../a/literals)     atom:entry                                          append to content           

  [supported\_by](../a/relationships#supported_by)          P   [uri](http://www.cetis.org.uk/leap2/terms/supported_by)      [relationship](../a/relationships)   atom:link                                           leap2:relation              

  [supports](../a/relationships#supports)                   P   [uri](http://www.cetis.org.uk/leap2/terms/supports)          [relationship](../a/relationships)   atom:link                                           leap2:relation              

  [version](../a/literals#version)                          N   [uri](http://www.cetis.org.uk/leap2/terms/version)           [literal element](../a/literals)     atom:feed                                           append to atom:subtitle     

  [when\_added](../a/literals#when_added)                   N   [uri](http://www.cetis.org.uk/leap2/terms/when_added)        attribute                            atom:link (part)                                    append to content           
  -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Terms from Atom and other specifications
----------------------------------------

These terms are used in Leap2A and understood as within the source spec.

Leap2A
type of term
source
containing element
notes
[alternate](../a/relationships#alternate)
relationship
[atom](http://tools.ietf.org/html/rfc4287#page-22)
atom:link
 
[author](../a/relationships#author)
blank node
[atom](http://tools.ietf.org/html/rfc4287#section-4.2.1)
atom:feed,entry
 
[category](../a/categories)
element
[atom](http://tools.ietf.org/html/rfc4287#section-4.2.2)
atom:entry
 
[content](../a/literals#content_or_description)
element
[atom](http://tools.ietf.org/html/rfc4287#section-4.1.3)
atom:entry
 
[contributor](../a/relationships#contributor)
blank node
[atom](http://tools.ietf.org/html/rfc4287#section-4.2.3)
atom:feed,entry
 
email
literal element
[atom](http://tools.ietf.org/html/rfc4287#section-3.2.3)
atom:author,contributor
 
[enclosure](../a/relationships#enclosure)
relationship
[atom](http://tools.ietf.org/html/rfc4287#page-22)
atom:link
 
[entry](../a/types/entry)
element
[atom](http://tools.ietf.org/html/rfc4287#section-4.1.2)
atom:feed
see [leap2](#entry)
[feed](../a/introduction#feed)
element
[atom](http://tools.ietf.org/html/rfc4287#section-4.1.1)
 
 
[in-reply-to](../a/relationships#in_reply_to)
relationship
[thr](http://tools.ietf.org/html/rfc4685#section-3)
atom:entry
see [leap2](#in_reply_to)
[license](../a/relationships#license)
relationship
[atom](http://tools.ietf.org/html/rfc4946)
atom:link
 
[replies](../a/relationships#has_reply)
relationship
[atom](http://tools.ietf.org/html/rfc4685#section-4)
atom:link
see [leap2](#has_reply)
[id](../a/literals#id)
literal element
[atom](http://tools.ietf.org/html/rfc4287#section-4.2.6)
atom:feed,entry
 
[issued](../a/literals#official_publication_date)
literal element
[dcterms](http://dublincore.org/documents/dcmi-terms/#terms-issued)
atom:entry([publication](#publication))
 
[label](../a/literals#label)
attribute
[atom](http://tools.ietf.org/html/rfc4287#section-4.2.2.3)
atom:category
see [leap2](#label)
[link](../a/relationships)
element
[atom](http://tools.ietf.org/html/rfc4287#section-4.2.7)
atom:entry
 
name
literal element
[atom](http://tools.ietf.org/html/rfc4287#section-3.2.1)
atom:author,contributor
 
[published](../a/literals#published)
literal element
[atom](http://tools.ietf.org/html/rfc4287#section-4.2.9)
atom:entry
 
[related](../a/relationships#relation)
relationship
[atom](http://tools.ietf.org/html/rfc4287#page-22)
atom:link
see [leap2](#relation)
resource
attribute
[rdf](http://www.w3.org/TR/rdf-schema/)
rdf:type
 
[rights](../a/literals#rights)
literal element
[atom](http://tools.ietf.org/html/rfc4287#section-4.2.10)
atom:entry
 
scheme
attribute
[atom](http://tools.ietf.org/html/rfc4287#section-4.2.2)
[atom:category](../a/categories)
 
[self](../a/relationships#selfid)
relationship
[atom](http://tools.ietf.org/html/rfc4287#page-22)
atom:link
 
[summary](../a/literals#summary)
literal element
[atom](http://tools.ietf.org/html/rfc4287#section-4.2.13)
atom:entry
 
term
attribute
[atom](http://tools.ietf.org/html/rfc4287#section-4.2.2.1)
[atom:category](../a/categories)
 
[title](../a/literals#title)
literal element
[atom](http://tools.ietf.org/html/rfc4287#section-4.2.14)
atom:feed,entry
 
[type](../a/literals#content_or_description)
attribute
[atom](http://tools.ietf.org/html/rfc4287#section-3.1.1)
atom:content,summary,title
 
[type](../a/relationships)
attribute
[atom](http://tools.ietf.org/html/rfc4287#section-4.2.7.3)
atom:link
 
[type](../a/types)
element
[rdf](http://www.w3.org/TR/rdf-schema/#ch_type)
atom:entry
 
[updated](../a/literals#updated)
literal element
[atom](http://tools.ietf.org/html/rfc4287#section-4.2.15)
atom:feed,entry
 
uri
element
[atom](http://tools.ietf.org/html/rfc4287#section-3.2.2)
atom:author,contributor
 
### Glossary for types of term in Leap2A

attribute
:   An attribute appears within its containing element, and can take
    values particular to that attribute selected from:
    -   an integer
    -   a term from a vocabulary
    -   a date in ISO format
    -   a URI or CURIE
    -   a system-generated label

    Attributes are generally documented along with the elements that
    contain them.\
    Several are documented alongside literals as [extra
    attributes](../a/literals#Extra_attributes).\
    leap2: is used as a namespace.

blank node
:   A blank node is an element containing other elements, but no text
    nodes, and it is not referred to.\
    leap2: is used as a namespace.

item type
:   A item type is represented as a URI or CURIE in the rdf:resource
    attribute of rdf:type\
    Item types are listed in [the types page](../a/types).\
    leap2: is used as a prefix.

literal element
:   A literal element appears within its containing element, and has a
    textual value for display.\
    It may also have attributes. Most literal elements are listed in
    [the literals page](../a/literals).\
    leap2: is used as a namespace.

relationship
:   A relationship is normally represented as a URI or CURIE in the rel
    attribute of atom:link\
    Relationships are listed in [the relationships
    page](../a/relationships).\
    leap2: is used as a prefix.

See also
--------

-   [the Leap2A specification](../a/specification)
-   [the main Leap2A documentation](../a/)

</div>

</div>
