<dl>
<dt>NAME</dt>
	<dd>svg2slides - export inkscape svg layers to individual files</dd>
<dt>SYNOPSIS</dt>
	<dd>svg2slides [-f &lt;format&gt;] inkscape.svg</dd>
<dt>DESCRIPTION</dt>
	<dd>Exports all layers of an inkscape.svg that contain labels
    in the format 'slide[0-9]+' to individual files in &lt;format&gt;.
    &lt;format&gt; can be png or pdf. If it's pdf the individual slides
    are also concatenated in the order in which they appear in
    the inkscape file (depends on pdfunite)</dd>
<dt>DEPENDENCIES</dt>
	<dd><ul>
        <li>Depends:  (1) inkscape (2) xlsproc</li>
	    <li>Optional: (1) pdfunite</li>
        </ul>
   </dd>
 </dl>
