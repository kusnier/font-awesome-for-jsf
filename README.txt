To use the files you must define some mime types.
Add this to your web.xml


<!-- Needed for Awesome Font/Icons -->
<mime-mapping>
  <extension>eot</extension>
  <mime-type>application/vnd.ms-fontobject</mime-type>
</mime-mapping>
<mime-mapping>
  <extension>otf</extension>
  <mime-type>font/opentype</mime-type>
</mime-mapping>
<mime-mapping>
  <extension>ttf</extension>
  <mime-type>application/x-font-ttf</mime-type>
</mime-mapping>
<mime-mapping>
  <extension>woff</extension>
  <mime-type>application/x-font-woff</mime-type>
</mime-mapping>
<mime-mapping>
  <extension>svg</extension>
  <mime-type>image/svg+xml</mime-type>
</mime-mapping>
