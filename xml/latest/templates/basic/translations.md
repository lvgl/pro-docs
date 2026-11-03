```xml title="templates/basic/translations.xml" source="https://github.com/lvgl/lvgl_pro/blob/e3bfb67a18d171c33904a5cb09c9848e7be73657/templates/basic/translations.xml"
<!-- Describe translations for languages.
     Use a tag with translation_tag="..." on a label-based widget and switch
     languages via lv_translation_set_language("de") in code. 
     Missing translations fall back to the tag itself.
     NOTE: non-Latin glyphs (ñ, é…) only render if added to a font range or symbol in globals.xml. -->
<translations languages="en de es">
	<translation tag="dark_theme" en="Dark theme" de="Dunkles Design" es="Tema oscuro" />
	<translation tag="buttons" en="Buttons" de="Tasten" es="Botones" />
	<translation tag="controls" en="Controls" de="Steuerelemente" es="Controles" />
	<translation tag="text_inputs" en="Text inputs" de="Texteingaben" es="Campos de texto" />
	<translation tag="selection" en="Selection" de="Auswahl" es="Seleccion" />
</translations>
```
