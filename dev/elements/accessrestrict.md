---
layout: sidebar
sidebar: s1
version: "dev"
title: "accessRestrict"
---
<div class="elementSpec">
   <h3 id="accessRestrict">&lt;accessRestrict&gt;</h3>
   <table class="wovenodd">
      <tr>
         <td colspan="2" class="wovenodd-col2">(access restriction) – Describes the conditions that affect the accessibility of
            material.
         </td>
      </tr>
      <tr>
         <td class="wovenodd-col1"><strong>Module</strong></td>
         <td class="wovenodd-col2">MEI.header</td>
      </tr>
      <tr>
         <td class="wovenodd-col1"><strong>Attributes</strong></td>
         <td class="wovenodd-col2">
            <table class="table table-striped">
               <thead>
                  <tr>
                     <th></th>
                  </tr>
               </thead>
               <tbody>
                  <tr>
                     <td>
                        <div class="attributeDef"><span class="attribute"><strong>@analog</strong></span><span class="attributeUsage">(optional)</span><span class="attributeDesc">Contains a reference to a field or element in another descriptive encoding system
                              to
                              which this MEI element is comparable.</span>
                           Value is plain text.
                           <span class="attributeClasses"><a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.bibl.html">att.bibl</a></span></div>
                     </td>
                  </tr>
                  <tr>
                     <td>
                        <div class="attributeDef"><span class="attribute"><strong>@auth</strong></span><span class="attributeUsage">(optional)</span><span class="attributeDesc">A name or label associated with a controlled vocabulary or other authoritative source
                              for this element or its content.</span>
                           Value is plain text.
                           <span class="attributeClasses"><a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.authorized.html">att.authorized</a></span></div>
                     </td>
                  </tr>
                  <tr>
                     <td>
                        <div class="attributeDef"><span class="attribute"><strong>@auth.uri</strong></span><span class="attributeUsage">(optional)</span><span class="attributeDesc">A web-accessible location of the controlled vocabulary or other authoritative source
                              for this element or its content.</span>
                           Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.uri.html">data.URI</a>.
                           <span class="attributeClasses"><a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.authorized.html">att.authorized</a></span></div>
                     </td>
                  </tr>
                  <tr>
                     <td>
                        <div class="attributeDef"><span class="attribute"><strong>@class</strong></span><span class="attributeUsage">(optional)</span><span class="attributeDesc">Contains one or more URIs which denote classification terms that apply to the entity
                              bearing this attribute.</span>
                           One or more values from <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.uri.html">data.URI</a>, separated by spaces.
                           <span class="attributeClasses"><a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.classed.html">att.classed</a></span></div>
                     </td>
                  </tr>
                  <tr>
                     <td>
                        <div class="attributeDef"><span class="attribute"><strong>@codedval</strong></span><span class="attributeUsage">(optional)</span><span class="attributeDesc">A value that represents or identifies other data. Often, it is a primary key in the
                              database or a unique value in the coded list identified by the <span class="att">auth</span> or
                              <span class="att">auth.uri</span> attributes.</span>
                           One or more values of datatype <span style="font-weight: 500;">NMTOKEN</span>, separated by spaces.
                           <span class="attributeClasses"><a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.canonical.html">att.canonical</a></span></div>
                     </td>
                  </tr>
                  <tr>
                     <td>
                        <div class="attributeDef"><span class="attribute"><strong>@copyof</strong></span><span class="attributeUsage">(optional)</span><span class="attributeDesc">Points to an element of which the current element is a copy.</span>
                           Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.uri.html">data.URI</a>.
                           <span class="attributeClasses"><a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.linking.html">att.linking</a></span></div>
                     </td>
                  </tr>
                  <tr>
                     <td>
                        <div class="attributeDef"><span class="attribute"><strong>@corresp</strong></span><span class="attributeUsage">(optional)</span><span class="attributeDesc">Used to point to other elements that correspond to this one in a generic
                              fashion.</span>
                           One or more values from <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.uri.html">data.URI</a>, separated by spaces.
                           <span class="attributeClasses"><a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.linking.html">att.linking</a></span></div>
                     </td>
                  </tr>
                  <tr>
                     <td>
                        <div class="attributeDef"><span class="attribute"><strong>@label</strong></span><span class="attributeUsage">(optional)</span><span class="attributeDesc">Captures text to be used to generate a label for the element to which it's attached,
                              a
                              "tool tip" or prefatory text, for example. Should not be used to record document
                              content.</span>
                           Value is plain text.
                           <span class="attributeClasses"><a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.labelled.html">att.labelled</a></span></div>
                     </td>
                  </tr>
                  <tr>
                     <td>
                        <div class="attributeDef"><span class="attribute"><strong>@n</strong></span><span class="attributeUsage">(optional)</span><span class="attributeDesc">Provides a number-like designation that indicates an element's position in a sequence
                              of similar elements. May not contain space characters.</span>
                           Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.word.html">data.WORD</a>.
                           <span class="attributeClasses"><a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.nnumberlike.html">att.nNumberLike</a></span></div>
                     </td>
                  </tr>
                  <tr>
                     <td>
                        <div class="attributeDef"><span class="attribute"><strong>@next</strong></span><span class="attributeUsage">(optional)</span><span class="attributeDesc">Used to point to the next event(s) in a user-defined collection.</span>
                           One or more values from <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.uri.html">data.URI</a>, separated by spaces.
                           <span class="attributeClasses"><a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.linking.html">att.linking</a></span></div>
                     </td>
                  </tr>
                  <tr>
                     <td>
                        <div class="attributeDef"><span class="attribute"><strong>@prev</strong></span><span class="attributeUsage">(optional)</span><span class="attributeDesc">Points to the previous event(s) in a user-defined collection.</span>
                           One or more values from <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.uri.html">data.URI</a>, separated by spaces.
                           <span class="attributeClasses"><a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.linking.html">att.linking</a></span></div>
                     </td>
                  </tr>
                  <tr>
                     <td>
                        <div class="attributeDef"><span class="attribute"><strong>@sameas</strong></span><span class="attributeUsage">(optional)</span><span class="attributeDesc">Points to an element that is the same as the current element but is not a literal
                              copy
                              of the current element.</span>
                           One or more values from <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.uri.html">data.URI</a>, separated by spaces.
                           <span class="attributeClasses"><a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.linking.html">att.linking</a></span></div>
                     </td>
                  </tr>
                  <tr>
                     <td>
                        <div class="attributeDef"><span class="attribute"><strong>@synch</strong></span><span class="attributeUsage">(optional)</span><span class="attributeDesc">Points to elements that are synchronous with the current element.</span>
                           One or more values from <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.uri.html">data.URI</a>, separated by spaces.
                           <span class="attributeClasses"><a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.linking.html">att.linking</a></span></div>
                     </td>
                  </tr>
                  <tr>
                     <td>
                        <div class="attributeDef"><span class="attribute"><strong>@translit</strong></span><span class="attributeUsage">(optional)</span><span class="attributeDesc">Specifies the transliteration technique used.</span>
                           Value is a <a target="_blank" href="https://www.w3.org/TR/xmlschema11-2/#NMTOKEN">NMTOKEN</a>.
                           <span class="attributeClasses"><a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.lang.html">att.lang</a></span></div>
                     </td>
                  </tr>
                  <tr>
                     <td>
                        <div class="attributeDef"><span class="attribute"><strong>@type</strong></span><span class="attributeUsage">(optional)</span><span class="attributeDesc">Designation which characterizes the element in some sense, using any convenient
                              classification scheme or typology that employs single-token labels.</span>
                           One or more values of datatype <span style="font-weight: 500;">NMTOKEN</span>, separated by spaces.
                           <span class="attributeClasses"><a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.typed.html">att.typed</a></span></div>
                     </td>
                  </tr>
                  <tr>
                     <td>
                        <div class="attributeDef"><span class="attribute"><strong>@xml:base</strong></span><span class="attributeUsage">(optional)</span><span class="attributeDesc">Provides a base URI reference with which applications can resolve relative URI
                              references into absolute URI references.</span>
                           Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.uri.html">data.URI</a>.
                           <span class="attributeClasses"><a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.basic.html">att.basic</a></span></div>
                     </td>
                  </tr>
                  <tr>
                     <td>
                        <div class="attributeDef"><span class="attribute"><strong>@xml:id</strong></span><span class="attributeUsage">(optional)</span><span class="attributeDesc">Regularizes the naming of an element and thus facilitates building links between it
                              and other resources. Each id attribute within a document must have a unique value.</span>
                           Value is a valid <a target="_blank" href="https://www.w3.org/TR/xml-id/">xml:id</a>.
                           <span class="attributeClasses"><a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.id.html">att.id</a></span></div>
                     </td>
                  </tr>
                  <tr>
                     <td>
                        <div class="attributeDef"><span class="attribute"><strong>@xml:lang</strong></span><span class="attributeUsage">(optional)</span><span class="attributeDesc">Identifies the language of the element's content. The values for this attribute are
                              language 'tags' as defined in BCP 47. All language tags that make use of private use
                              sub-tags must be documented in a corresponding language element in the MEI header
                              whose id
                              attribute is the same as the language tag's value.</span>
                           Value is a <a target="_blank" href="https://www.w3.org/TR/xmlschema11-2/#language">language</a>.
                           <span class="attributeClasses"><a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.lang.html">att.lang</a></span></div>
                     </td>
                  </tr>
               </tbody>
            </table>
         </td>
      </tr>
      <tr>
         <td class="wovenodd-col1"><strong>Member of</strong></td>
         <td class="wovenodd-col2">
            <div class="parent"><a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/model-classes/model.titlepagepart.html">model.titlePagePart</a></div>
         </td>
      </tr>
      <tr>
         <td class="wovenodd-col1"><strong>Contained by</strong></td>
         <td class="wovenodd-col2">
            <div class="parent">
               <div class="specChildren">
                  <div class="specChild"><span class="specChildModule">MEI.header</span><span class="specChildElements"><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/availability.html">availability</a></span></div>
                  <div class="specChild"><span class="specChildModule">MEI.shared</span><span class="specChildElements"><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/titlepage.html">titlePage</a></span></div>
               </div>
            </div>
         </td>
      </tr>
      <tr>
         <td class="wovenodd-col1"><strong>May contain</strong></td>
         <td class="wovenodd-col2">
            <div class="specChild"><span class="specChildModule">Empty</span><span class="specChildElements"></span></div>
         </td>
      </tr>
      <tr>
         <td class="wovenodd-col1"><strong>Declaration</strong></td>
         <td class="wovenodd-col2">
            <div class="code" xml:space="preserve" data-lang="ODD"><code>
                  <div class="indent1 indent"><span data-indentation="1" class="element">&lt;classes&gt;</span>
                     
                     <div class="indent2 indent"><span data-indentation="2" class="element">&lt;memberOf
                           <span class="attribute">key=<span class="attributevalue">"<a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.common.html">att.common</a>"</span></span>/&gt;</span></div>
                     
                     <div class="indent2 indent"><span data-indentation="2" class="element">&lt;memberOf
                           <span class="attribute">key=<span class="attributevalue">"<a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.authorized.html">att.authorized</a>"</span></span>/&gt;</span></div>
                     
                     <div class="indent2 indent"><span data-indentation="2" class="element">&lt;memberOf
                           <span class="attribute">key=<span class="attributevalue">"<a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.bibl.html">att.bibl</a>"</span></span>/&gt;</span></div>
                     
                     <div class="indent2 indent"><span data-indentation="2" class="element">&lt;memberOf
                           <span class="attribute">key=<span class="attributevalue">"<a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.lang.html">att.lang</a>"</span></span>/&gt;</span></div>
                     
                     <div class="indent2 indent"><span data-indentation="2" class="element">&lt;memberOf
                           <span class="attribute">key=<span class="attributevalue">"<a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/model-classes/model.titlepagepart.html">model.titlePagePart</a>"</span></span>/&gt;</span></div>
                     <span data-indentation="1" class="element">&lt;/classes&gt;</span></div>
                  <div class="indent1 indent"><span data-indentation="1" class="element">&lt;content&gt;</span>
                     
                     <div class="indent2 indent"><span data-indentation="2" class="element">&lt;rng:ref
                           
                           <span class="attribute">name=<span class="attributevalue">"<a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/data-types/macro.struc-unstruccontent.html">macro.struc-unstrucContent</a>"</span></span>
                           /&gt;</span></div>
                     <span data-indentation="1" class="element">&lt;/content&gt;</span></div></code></div>
         </td>
      </tr>
      <tr>
         <td class="wovenodd-col1"><strong>Remarks</strong></td>
         <td class="wovenodd-col2">
            <p>May indicate the nature of restrictions or the lack of restrictions. Do not confuse
               this
               element with <a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/userestrict.html">useRestrict</a> (usage restrictions), which captures
               information about limitations on the <span class="hi">use</span> of material, such as those
               afforded by copyright.This element is modelled on an element in the Encoded Archival
               Description (EAD)
               standard.
            </p>
         </td>
      </tr>
   </table>
</div>