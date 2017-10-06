---
layout: sidebar
sidebar: s1
title: "data.MIDIVALUE"

---

<div class="macroSpec">
   <h3 id="data.MIDIVALUE">data.MIDIVALUE</h3>
   <table class="wovenodd">
      <tr>
         <td colspan="2" class="wovenodd-col2">
            <span class="label">data.MIDIVALUE</span> MIDI values in the following range.
         </td>
      </tr>
      <tr>
         <td class="wovenodd-col1">
            <span class="label" lang="en">Module</span>
         </td>
         <td class="wovenodd-col2">MEI</td>
      </tr>
      <tr>
         <td class="wovenodd-col1">
            <span class="label" lang="en">Used by</span>
         </td>
         <td class="wovenodd-col2">
            <div class="parent">
               <a class="link_odd_classSpec" href="/v3/att.channelized">att.channelized</a> (@midi.port), 
               <a class="link_odd_classSpec" href="/v3/att.midiinstrument">att.midiinstrument</a> (@midi.instrnum), 
               <a class="link_odd_classSpec" href="/v3/att.midinumber">att.midinumber</a> (@num), 
               <a class="link_odd_classSpec" href="/v3/att.midivalue">att.midivalue</a> (@val), 
               <a class="link_odd_classSpec" href="/v3/att.midivalue2">att.midivalue2</a> (@val2), 
               <a class="link_odd_classSpec" href="/v3/att.midivelocity">att.midivelocity</a> (@vel)
            </div>
         </td>
      </tr>
      <tr>
         <td class="wovenodd-col1">
            <span class="label" lang="en">Declaration</span>
         </td>
         <td class="wovenodd-col2">
            <div xml:space="preserve" class="pre">
               <div class="indent1">
                  <span data-indentation="1" class="element">&lt;content&gt;</span>
                  
                  <div class="indent2">
                     <span data-indentation="2" class="element">&lt;rng:data 
                        <span class="attribute">type=</span>
                        <span class="attributevalue">"nonNegativeInteger"</span>&gt;
                     </span>
                     
                     <div class="indent3">
                        <span data-indentation="3" class="element">&lt;rng:param 
                           <span class="attribute">name=</span>
                           <span class="attributevalue">"maxInclusive"</span>&gt;
                        </span>127
                        <span data-indentation="3" class="element">&lt;/rng:param&gt;</span>
                     </div>
                     
                     <span data-indentation="2" class="element">&lt;/rng:data&gt;</span>
                  </div>
                  
                  <span data-indentation="1" class="element">&lt;/content&gt;</span>
               </div>
            </div>
         </td>
      </tr>
   </table>
</div>