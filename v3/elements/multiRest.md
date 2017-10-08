---
layout: sidebar
sidebar: s1
version: "v3"
title: "multiRest"

---

<div class="elementSpec">
   <h3 id="multiRest">&lt;multiRest&gt;</h3>
   <table class="wovenodd">
      <tr>
         <td colspan="2" class="wovenodd-col2">(multiple rest) – Multiple measures of rest compressed into a single symbol, frequently
            found in performer parts.
         </td>
      </tr>
      <tr>
         <td class="wovenodd-col1">
            <strong>Module</strong>
         </td>
         <td class="wovenodd-col2">MEI.cmn</td>
      </tr>
      <tr>
         <td class="wovenodd-col1">
            <strong>Attributes</strong>
         </td>
         <td class="wovenodd-col2">
            <table class="table table-striped table-hover">
               <thead>
                  <tr>
                     <th></th>
                  </tr>
               </thead>
               <tbody>
                  <tr>
                     <td>
                        <div class="attributeDef">
                           <span class="attribute">
                              <strong>@altsym</strong>
                           </span>
                           <span class="attributeUsage">(optional)</span>
                           <span class="attributeDesc">Provides a way of pointing to a user-defined symbol. It must contain an ID of a
                              &lt;symbolDef&gt; element elsewhere in the document.
                           </span>
                           Value conforms to 
                           <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.URI.html">data.URI</a>.
                           
                           <span class="attributeClasses">
                              <a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.altsym.html">att.altsym</a>
                           </span>
                        </div>
                     </td>
                  </tr>
                  <tr>
                     <td>
                        <div class="attributeDef">
                           <span class="attribute">
                              <strong>@block</strong>
                           </span>
                           <span class="attributeUsage">(optional)</span>
                           <span class="attributeDesc">When the block attribute is used, combinations of the 1, 2, and 4 measure rest forms
                              (Read, p. 104) should be rendered instead of the modern form or an alternative
                              symbol.
                           </span>
                           Value conforms to 
                           <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.BOOLEAN.html">data.BOOLEAN</a>.
                           
                           <span class="attributeClasses">
                              <a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.multiRest.vis.html">att.multiRest.vis</a>
                           </span>
                        </div>
                     </td>
                  </tr>
                  <tr>
                     <td>
                        <div class="attributeDef">
                           <span class="attribute">
                              <strong>@copyof</strong>
                           </span>
                           <span class="attributeUsage">(optional)</span>
                           <span class="attributeDesc">Points to an element of which the current element is a copy.</span>
                           Value conforms to 
                           <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.URI.html">data.URI</a>.
                           
                           <span class="attributeClasses">
                              <a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.common.anl.html">att.common.anl</a>
                           </span>
                        </div>
                     </td>
                  </tr>
                  <tr>
                     <td>
                        <div class="attributeDef">
                           <span class="attribute">
                              <strong>@corresp</strong>
                           </span>
                           <span class="attributeUsage">(optional)</span>
                           <span class="attributeDesc">Used to point to other elements that correspond to this one in a generic
                              fashion.
                           </span>
                           One or more values from
                           <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.URI.html">data.URI</a>, separated by spaces.
                           
                           <span class="attributeClasses">
                              <a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.common.anl.html">att.common.anl</a>
                           </span>
                        </div>
                     </td>
                  </tr>
                  <tr>
                     <td>
                        <div class="attributeDef">
                           <span class="attribute">
                              <strong>@dur.ges</strong>
                           </span>
                           <span class="attributeUsage">(optional)</span>
                           <span class="attributeDesc">Records performed duration information that differs from the written duration. Its
                              value may be expressed in several forms; that is, ppq (MIDI clicks and MusicXML
                              'divisions'), Humdrum **recip values, beats, seconds, or mensural duration
                              values.
                           </span>
                           Value conforms to 
                           <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.DURATION.gestural.html">data.DURATION.gestural</a>.
                           
                           <span class="attributeClasses">
                              <a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.duration.performed.html">att.duration.performed</a>
                           </span>
                        </div>
                     </td>
                  </tr>
                  <tr>
                     <td>
                        <div class="attributeDef">
                           <span class="attribute">
                              <strong>@facs</strong>
                           </span>
                           <span class="attributeUsage">(optional)</span>
                           <span class="attributeDesc">Permits the current element to reference a facsimile surface or image zone which
                              corresponds to it.
                           </span>
                           One or more values from
                           <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.URI.html">data.URI</a>, separated by spaces.
                           
                           <span class="attributeClasses">
                              <a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.facsimile.html">att.facsimile</a>
                           </span>
                        </div>
                     </td>
                  </tr>
                  <tr>
                     <td>
                        <div class="attributeDef">
                           <span class="attribute">
                              <strong>@fontfam</strong>
                           </span>
                           <span class="attributeUsage">(optional)</span>
                           <span class="attributeDesc">Contains the name of a font-family.</span>
                           Value conforms to 
                           <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.FONTFAMILY.html">data.FONTFAMILY</a>.
                           
                           <span class="attributeClasses">
                              <a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.typography.html">att.typography</a>
                           </span>
                        </div>
                     </td>
                  </tr>
                  <tr>
                     <td>
                        <div class="attributeDef">
                           <span class="attribute">
                              <strong>@fontname</strong>
                           </span>
                           <span class="attributeUsage">(optional)</span>
                           <span class="attributeDesc">Holds the name of a font.</span>
                           Value conforms to 
                           <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.FONTNAME.html">data.FONTNAME</a>.
                           
                           <span class="attributeClasses">
                              <a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.typography.html">att.typography</a>
                           </span>
                        </div>
                     </td>
                  </tr>
                  <tr>
                     <td>
                        <div class="attributeDef">
                           <span class="attribute">
                              <strong>@fontsize</strong>
                           </span>
                           <span class="attributeUsage">(optional)</span>
                           <span class="attributeDesc">Indicates the size of a font expressed in printers' points, i.e., 1/72nd of an inch,
                              relative terms, e.g., "small", "larger", etc., or percentage values relative to "normal"
                              size, e.g., "125%". 
                           </span>
                           Value conforms to 
                           <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.FONTSIZE.html">data.FONTSIZE</a>.
                           
                           <span class="attributeClasses">
                              <a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.typography.html">att.typography</a>
                           </span>
                        </div>
                     </td>
                  </tr>
                  <tr>
                     <td>
                        <div class="attributeDef">
                           <span class="attribute">
                              <strong>@fontstyle</strong>
                           </span>
                           <span class="attributeUsage">(optional)</span>
                           <span class="attributeDesc">Records the style of a font, i.e, italic, oblique, or normal.</span>
                           Value conforms to 
                           <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.FONTSTYLE.html">data.FONTSTYLE</a>.
                           
                           <span class="attributeClasses">
                              <a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.typography.html">att.typography</a>
                           </span>
                        </div>
                     </td>
                  </tr>
                  <tr>
                     <td>
                        <div class="attributeDef">
                           <span class="attribute">
                              <strong>@fontweight</strong>
                           </span>
                           <span class="attributeUsage">(optional)</span>
                           <span class="attributeDesc">Used to indicate bold type.</span>
                           Value conforms to 
                           <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.FONTWEIGHT.html">data.FONTWEIGHT</a>.
                           
                           <span class="attributeClasses">
                              <a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.typography.html">att.typography</a>
                           </span>
                        </div>
                     </td>
                  </tr>
                  <tr>
                     <td>
                        <div class="attributeDef">
                           <span class="attribute">
                              <strong>@glyphname</strong>
                           </span>
                           <span class="attributeUsage">(optional)</span>
                           <span class="attributeDesc">Glyph name.</span>
                           Value of datatype 
                           <span style="font-weight: 500;">string</span>.
                           
                           <span class="attributeClasses">
                              <a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.extsym.html">att.extsym</a>
                           </span>
                        </div>
                     </td>
                  </tr>
                  <tr>
                     <td>
                        <div class="attributeDef">
                           <span class="attribute">
                              <strong>@glyphnum</strong>
                           </span>
                           <span class="attributeUsage">(optional)</span>
                           <span class="attributeDesc">Numeric glyph reference in hexadecimal notation, e.g. "#xE000" or "U+E000". N.B.
                              SMuFL version 1.18 uses the range U+E000 - U+ECBF.
                           </span>
                           Value of datatype 
                           <span style="font-weight: 500;">
                              a string matching the following regular expression: "(#x|U\+)[A-F0-9]+"
                              
                           </span>.
                           
                           <span class="attributeClasses">
                              <a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.extsym.html">att.extsym</a>
                           </span>
                        </div>
                     </td>
                  </tr>
                  <tr>
                     <td>
                        <div class="attributeDef">
                           <span class="attribute">
                              <strong>@instr</strong>
                           </span>
                           <span class="attributeUsage">(optional)</span>
                           <span class="attributeDesc">Provides a way of pointing to a MIDI instrument definition. It must contain the ID
                              of an &lt;instrDef&gt; element elsewhere in the document.
                           </span>
                           Value conforms to 
                           <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.URI.html">data.URI</a>.
                           
                           <span class="attributeClasses">
                              <a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.instrumentident.html">att.instrumentident</a>
                           </span>
                        </div>
                     </td>
                  </tr>
                  <tr>
                     <td>
                        <div class="attributeDef">
                           <span class="attribute">
                              <strong>@label</strong>
                           </span>
                           <span class="attributeUsage">(optional)</span>
                           <span class="attributeDesc">Provides a name or label for an element. The value may be any string.</span>
                           Value of datatype 
                           <span style="font-weight: 500;">string</span>.
                           
                           <span class="attributeClasses">
                              <a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.commonPart.html">att.commonPart</a>
                           </span>
                        </div>
                     </td>
                  </tr>
                  <tr>
                     <td>
                        <div class="attributeDef">
                           <span class="attribute">
                              <strong>@layer</strong>
                           </span>
                           <span class="attributeUsage">(optional)</span>
                           <span class="attributeDesc">Identifies the layer to which a feature applies.</span>
                           One or more values of datatype 
                           <span style="font-weight: 500;">positiveInteger</span>, separated by spaces.
                           
                           <span class="attributeClasses">
                              <a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.layerident.html">att.layerident</a>
                           </span>
                        </div>
                     </td>
                  </tr>
                  <tr>
                     <td>
                        <div class="attributeDef">
                           <span class="attribute">
                              <strong>@loc</strong>
                           </span>
                           <span class="attributeUsage">(optional)</span>
                           <span class="attributeDesc">Holds the staff location of the feature.</span>
                           Value conforms to 
                           <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.STAFFLOC.html">data.STAFFLOC</a>.
                           
                           <span class="attributeClasses">
                              <a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.staffloc.html">att.staffloc</a>
                           </span>
                        </div>
                     </td>
                  </tr>
                  <tr>
                     <td>
                        <div class="attributeDef">
                           <span class="attribute">
                              <strong>@n</strong>
                           </span>
                           <span class="attributeUsage">(optional)</span>
                           <span class="attributeDesc">Provides a number-like designation for an element.</span>
                           Value conforms to 
                           <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/token.html">token</a>.
                           
                           <span class="attributeClasses">
                              <a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.common.html">att.common</a>
                           </span>
                        </div>
                     </td>
                  </tr>
                  <tr>
                     <td>
                        <div class="attributeDef">
                           <span class="attribute">
                              <strong>@next</strong>
                           </span>
                           <span class="attributeUsage">(optional)</span>
                           <span class="attributeDesc">Used to point to the next event(s) in a user-defined collection.</span>
                           One or more values from
                           <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.URI.html">data.URI</a>, separated by spaces.
                           
                           <span class="attributeClasses">
                              <a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.common.anl.html">att.common.anl</a>
                           </span>
                        </div>
                     </td>
                  </tr>
                  <tr>
                     <td>
                        <div class="attributeDef">
                           <span class="attribute">
                              <strong>@num</strong>
                           </span>
                           <span class="attributeUsage">(optional)</span>
                           <span class="attributeDesc">Records a number or count accompanying a notational feature.</span>
                           Value of datatype 
                           <span style="font-weight: 500;">positiveInteger</span>.
                           
                           <span class="attributeClasses">
                              <a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.numbered.html">att.numbered</a>
                           </span>
                        </div>
                     </td>
                  </tr>
                  <tr>
                     <td>
                        <div class="attributeDef">
                           <span class="attribute">
                              <strong>@oloc</strong>
                           </span>
                           <span class="attributeUsage">(optional)</span>
                           <span class="attributeDesc">Records staff location in terms of written octave.</span>
                           Value conforms to 
                           <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.OCTAVE.html">data.OCTAVE</a>.
                           
                           <span class="attributeClasses">
                              <a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.staffloc.pitched.html">att.staffloc.pitched</a>
                           </span>
                        </div>
                     </td>
                  </tr>
                  <tr>
                     <td>
                        <div class="attributeDef">
                           <span class="attribute">
                              <strong>@ploc</strong>
                           </span>
                           <span class="attributeUsage">(optional)</span>
                           <span class="attributeDesc">Captures staff location in terms of written pitch name.</span>
                           Value conforms to 
                           <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.PITCHNAME.html">data.PITCHNAME</a>.
                           
                           <span class="attributeClasses">
                              <a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.staffloc.pitched.html">att.staffloc.pitched</a>
                           </span>
                        </div>
                     </td>
                  </tr>
                  <tr>
                     <td>
                        <div class="attributeDef">
                           <span class="attribute">
                              <strong>@prev</strong>
                           </span>
                           <span class="attributeUsage">(optional)</span>
                           <span class="attributeDesc">Points to the previous event(s) in a user-defined collection.</span>
                           One or more values from
                           <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.URI.html">data.URI</a>, separated by spaces.
                           
                           <span class="attributeClasses">
                              <a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.common.anl.html">att.common.anl</a>
                           </span>
                        </div>
                     </td>
                  </tr>
                  <tr>
                     <td>
                        <div class="attributeDef">
                           <span class="attribute">
                              <strong>@sameas</strong>
                           </span>
                           <span class="attributeUsage">(optional)</span>
                           <span class="attributeDesc">Points to an element that is the same as the current element but is not a literal
                              copy of the current element.
                           </span>
                           One or more values from
                           <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.URI.html">data.URI</a>, separated by spaces.
                           
                           <span class="attributeClasses">
                              <a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.common.anl.html">att.common.anl</a>
                           </span>
                        </div>
                     </td>
                  </tr>
                  <tr>
                     <td>
                        <div class="attributeDef">
                           <span class="attribute">
                              <strong>@staff</strong>
                           </span>
                           <span class="attributeUsage">(optional)</span>
                           <span class="attributeDesc">Signifies the staff on which a notated event occurs or to which a control event
                              applies. Mandatory when applicable.
                           </span>
                           One or more values of datatype 
                           <span style="font-weight: 500;">positiveInteger</span>, separated by spaces.
                           
                           <span class="attributeClasses">
                              <a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.staffident.html">att.staffident</a>
                           </span>
                        </div>
                     </td>
                  </tr>
                  <tr>
                     <td>
                        <div class="attributeDef">
                           <span class="attribute">
                              <strong>@synch</strong>
                           </span>
                           <span class="attributeUsage">(optional)</span>
                           <span class="attributeDesc">Points to elements that are synchronous with the current element.</span>
                           One or more values from
                           <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.URI.html">data.URI</a>, separated by spaces.
                           
                           <span class="attributeClasses">
                              <a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.common.anl.html">att.common.anl</a>
                           </span>
                        </div>
                     </td>
                  </tr>
                  <tr>
                     <td>
                        <div class="attributeDef">
                           <span class="attribute">
                              <strong>@tstamp</strong>
                           </span>
                           <span class="attributeUsage">(optional)</span>
                           <span class="attributeDesc">Encodes the onset time in terms of musical time, i.e.,
                              beats[.fractional_beat_part].
                           </span>
                           Value conforms to 
                           <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.BEAT.html">data.BEAT</a>.
                           
                           <span class="attributeClasses">
                              <a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.timestamp.musical.html">att.timestamp.musical</a>
                           </span>
                        </div>
                     </td>
                  </tr>
                  <tr>
                     <td>
                        <div class="attributeDef">
                           <span class="attribute">
                              <strong>@tstamp.ges</strong>
                           </span>
                           <span class="attributeUsage">(optional)</span>
                           <span class="attributeDesc">Captures performed onset time in several forms; that is, ppq (MIDI clicks and
                              MusicXML 'divisions'), Humdrum **recip values, beats, seconds, or mensural duration
                              values.
                           </span>
                           Value conforms to 
                           <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.DURATION.gestural.html">data.DURATION.gestural</a>.
                           
                           <span class="attributeClasses">
                              <a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.timestamp.performed.html">att.timestamp.performed</a>
                           </span>
                        </div>
                     </td>
                  </tr>
                  <tr>
                     <td>
                        <div class="attributeDef">
                           <span class="attribute">
                              <strong>@tstamp.real</strong>
                           </span>
                           <span class="attributeUsage">(optional)</span>
                           <span class="attributeDesc">Used to record the onset time in terms of ISO time.</span>
                           Value conforms to 
                           <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.ISOTIME.html">data.ISOTIME</a>.
                           
                           <span class="attributeClasses">
                              <a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.timestamp.performed.html">att.timestamp.performed</a>
                           </span>
                        </div>
                     </td>
                  </tr>
                  <tr>
                     <td>
                        <div class="attributeDef">
                           <span class="attribute">
                              <strong>@when</strong>
                           </span>
                           <span class="attributeUsage">(optional)</span>
                           <span class="attributeDesc">Indicates the point of occurrence of this feature along a time line. Its value must
                              be the ID of a 
                              <a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/when.html">when</a> element elsewhere in the document.
                           </span>
                           Value conforms to 
                           <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.URI.html">data.URI</a>.
                           
                           <span class="attributeClasses">
                              <a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.alignment.html">att.alignment</a>
                           </span>
                        </div>
                     </td>
                  </tr>
                  <tr>
                     <td>
                        <div class="attributeDef">
                           <span class="attribute">
                              <strong>@xml:base</strong>
                           </span>
                           <span class="attributeUsage">(optional)</span>
                           <span class="attributeDesc">Provides a base URI reference with which applications can resolve relative URI
                              references into absolute URI references.
                           </span>
                           Value conforms to 
                           <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.URI.html">data.URI</a>.
                           
                           <span class="attributeClasses">
                              <a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.commonPart.html">att.commonPart</a>
                           </span>
                        </div>
                     </td>
                  </tr>
                  <tr>
                     <td>
                        <div class="attributeDef">
                           <span class="attribute">
                              <strong>@xml:id</strong>
                           </span>
                           <span class="attributeUsage">(optional)</span>
                           <span class="attributeDesc">Regularizes the naming of an element and thus facilitates building links between it
                              and other resources. Each id attribute within a document must have a unique
                              value.
                           </span>
                           Value of datatype 
                           <span style="font-weight: 500;">ID</span>.
                           
                           <span class="attributeClasses">
                              <a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.id.html">att.id</a>
                           </span>
                        </div>
                     </td>
                  </tr>
               </tbody>
            </table>
         </td>
      </tr>
      <tr>
         <td class="wovenodd-col1">
            <strong>Member of</strong>
         </td>
         <td class="wovenodd-col2">
            <div class="parent">
               <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/model-classes/model.eventLike.measureFilling.html">model.eventLike.measureFilling</a>
            </div>
         </td>
      </tr>
      <tr>
         <td class="wovenodd-col1">
            <strong>Contained by</strong>
         </td>
         <td class="wovenodd-col2">
            <div class="parent">
               <div class="specChildren">
                  <div class="specChild">
                     <span class="specChildModule">MEI.cmn</span>
                     <span class="specChildElements">
                        <a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/mRest.html">mRest</a> 
                        <a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/mRpt.html">mRpt</a> 
                        <a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/mRpt2.html">mRpt2</a> 
                        <a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/mSpace.html">mSpace</a> 
                        <a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/multiRest.html">multiRest</a> 
                        <a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/multiRpt.html">multiRpt</a>
                     </span>
                  </div>
                  <div class="specChild">
                     <span class="specChildModule">MEI.critapp</span>
                     <span class="specChildElements">
                        <a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/lem.html">lem</a> 
                        <a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/rdg.html">rdg</a>
                     </span>
                  </div>
                  <div class="specChild">
                     <span class="specChildModule">MEI.edittrans</span>
                     <span class="specChildElements">
                        <a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/abbr.html">abbr</a> 
                        <a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/add.html">add</a> 
                        <a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/corr.html">corr</a> 
                        <a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/damage.html">damage</a> 
                        <a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/del.html">del</a> 
                        <a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/expan.html">expan</a> 
                        <a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/orig.html">orig</a> 
                        <a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/reg.html">reg</a> 
                        <a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/restore.html">restore</a> 
                        <a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/sic.html">sic</a> 
                        <a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/supplied.html">supplied</a> 
                        <a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/unclear.html">unclear</a>
                     </span>
                  </div>
                  <div class="specChild">
                     <span class="specChildModule">MEI.mensural</span>
                     <span class="specChildElements">
                        <a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/ligature.html">ligature</a>
                     </span>
                  </div>
                  <div class="specChild">
                     <span class="specChildModule">MEI.shared</span>
                     <span class="specChildElements">
                        <a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/layer.html">layer</a>
                     </span>
                  </div>
               </div>
            </div>
         </td>
      </tr>
      <tr>
         <td class="wovenodd-col1">
            <strong>May contain</strong>
         </td>
         <td class="wovenodd-col2">
            <div class="specChild">
               <span class="specChildModule">Empty</span>
               <span class="specChildElements"></span>
            </div>
         </td>
      </tr>
      <tr>
         <td class="wovenodd-col1">
            <strong>Declaration</strong>
         </td>
         <td class="wovenodd-col2">
            <div class="code" xml:space="preserve" data-lang="ODD">
               <code>
                  <div class="indent1 indent">
                     <span data-indentation="1" class="element">&lt;classes&gt;</span>
                     
                     <div class="indent2 indent">
                        <span data-indentation="2" class="element">&lt;memberOf
                           
                           <span class="attribute">key=
                              <span class="attributevalue">"
                                 <a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.common.html">att.common</a>"
                              </span>
                           </span>/&gt;
                        </span>
                     </div>
                     
                     <div class="indent2 indent">
                        <span data-indentation="2" class="element">&lt;memberOf
                           
                           <span class="attribute">key=
                              <span class="attributevalue">"
                                 <a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.facsimile.html">att.facsimile</a>"
                              </span>
                           </span>/&gt;
                        </span>
                     </div>
                     
                     <div class="indent2 indent">
                        <span data-indentation="2" class="element">&lt;memberOf
                           
                           <span class="attribute">key=
                              <span class="attributevalue">"
                                 <a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.multiRest.log.html">att.multiRest.log</a>"
                              </span>
                           </span>/&gt;
                        </span>
                     </div>
                     
                     <div class="indent2 indent">
                        <span data-indentation="2" class="element">&lt;memberOf
                           
                           <span class="attribute">key=
                              <span class="attributevalue">"
                                 <a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.multiRest.vis.html">att.multiRest.vis</a>"
                              </span>
                           </span>/&gt;
                        </span>
                     </div>
                     
                     <div class="indent2 indent">
                        <span data-indentation="2" class="element">&lt;memberOf
                           
                           <span class="attribute">key=
                              <span class="attributevalue">"
                                 <a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.multiRest.ges.html">att.multiRest.ges</a>"
                              </span>
                           </span>/&gt;
                        </span>
                     </div>
                     
                     <div class="indent2 indent">
                        <span data-indentation="2" class="element">&lt;memberOf
                           
                           <span class="attribute">key=
                              <span class="attributevalue">"
                                 <a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.multiRest.anl.html">att.multiRest.anl</a>"
                              </span>
                           </span>/&gt;
                        </span>
                     </div>
                     
                     <div class="indent2 indent">
                        <span data-indentation="2" class="element">&lt;memberOf
                           
                           <span class="attribute">key=
                              <span class="attributevalue">"
                                 <a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/model-classes/model.eventLike.measureFilling.html">model.eventLike.measureFilling</a>"
                              </span>
                           </span>/&gt;
                        </span>
                     </div>
                     
                     <span data-indentation="1" class="element">&lt;/classes&gt;</span>
                  </div>
                  <div class="indent1 indent">
                     <span data-indentation="1" class="element">&lt;content&gt;</span>
                     
                     <div class="indent2 indent">
                        <span data-indentation="2" class="element">&lt;rng:empty/&gt;</span>
                     </div>
                     
                     <span data-indentation="1" class="element">&lt;/content&gt;</span>
                  </div>
               </code>
            </div>
         </td>
      </tr>
   </table>
</div>