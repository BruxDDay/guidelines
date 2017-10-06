---
sectionid: textFront
title: Front Matter
---


<h3 id="textFront">
   <span class="headingNumber">21.6.1</span>
   <span class="head">Front Matter</span>
</h3>
By ‘front matter’ these Guidelines mean distinct sections of a text
(usually, but not necessarily, a printed one), prefixed to it by way of introduction
or
identification as a part of its production. Features such as title pages or prefaces
are
clear examples; a less definite case might be the prologue attached to a dramatic
work. The
front matter of an encoded text should not be confused with the MEI header described
in
chapter 
<span class="ptr"></span>, which provides metadata for the entire file.

An encoder may choose simply to ignore the front matter in a text, if the original
presentation of the work is of no interest. No specific tags are provided for the
various
kinds of subdivision which may appear within front matter: instead, generic 
<a class="link_odd_elementSpec" href="/v3/elements/div">div</a> (“division”) elements may be used, which should not be confused with 
<a class="link_odd_elementSpec" href="/v3/elements/mdiv">mdiv</a> (“musical division”) elements. The following suggested values for
the **@type** attribute may be used to distinguish various kinds of division
characteristic of front matter:


<span class="list">
   
   <span class="label">'preface' – </span>
   
   <span class="item">A foreword or preface addressed to the reader in which the author or publisher
      explains the content, purpose, or origin of the text. 
   </span>
   
   <span class="label">'ack' – </span>
   
   <span class="item">A formal declaration of acknowledgement by the author in which persons and
      institutions are thanked for their part in the creation of a text.
   </span>
   
   <span class="label">'dedication' – </span>
   
   <span class="item">A formal offering or dedication of a text to one or more persons or institutions by
      the author.
   </span>
   
   <span class="label">'abstract' – </span>
   
   <span class="item">A summary of the content of a text as continuous prose.</span>
   
   <span class="label">'contents' – </span>
   
   <span class="item">A table of contents, specifying the structure of a work and listing its constituents.
      The list element should be used to mark its structure.
   </span>
   
   <span class="label">'frontispiece' – </span>
   
   <span class="item">A pictorial frontispiece, possibly including some text.</span>
   
</span>
The following extended example demonstrates how various parts of the front matter
of a text
may be encoded. The front part begins with a title page, which is presented in section

<span class="ptr"></span>, below. This is followed by a dedication and a preface, each of
which is encoded as a distinct div:


{% include _plainExample.html example="./v3/examples/text/text-sample338.xml" valid="true" %}

The front matter concludes with another 
<a class="link_odd_elementSpec" href="/v3/elements/div">div</a> element, shown in the
next example, this time containing a table of contents, which contains a 
<a class="link_odd_elementSpec" href="/v3/elements/list">list</a> element (as described in chapter 
<span class="ptr"></span>). Note the use of
the 
<a class="link_odd_elementSpec" href="/v3/elements/ptr">ptr</a> element to provide page-references: the implication here is
that the target identifiers (song1, song2, etc.) will correspond with identifiers
used for
the 
<a class="link_odd_elementSpec" href="/v3/elements/mdiv">mdiv</a> elements containing the individual songs. (For a description
of the 
<a class="link_odd_elementSpec" href="/v3/elements/ptr">ptr</a> element, see chapter 
<span class="ptr"></span>.)


{% include _plainExample.html example="./v3/examples/text/text-sample339.xml" valid="true" %}

Alternatively, the pointers in the table of contents might link to the page breaks
at which
a song begins, assuming that these have been included in the markup:


{% include _plainExample.html example="./v3/examples/text/text-sample340.xml" valid="true" %}
