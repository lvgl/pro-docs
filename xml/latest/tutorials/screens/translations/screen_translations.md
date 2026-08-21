```xml title="tutorials/screens/translations/screen_translations.xml" source="https://github.com/lvgl/lvgl_pro/blob/91553dccc827bdbb5d49302579f6a8df95e2db84/tutorials/screens/translations/screen_translations.xml"
<screen>
	<!-- Create some label with translated text.
		 Try out the "Translations" panel under the Preview
	     See translations.xml to see from where the translations are coming. 
		 Also globals.xml for the font where the German characters are also added -->
	<view flex_flow="column" style_text_font="montserrat_14_c_array">
		<lv_label translation_tag="dog" />
		<lv_label translation_tag="cat" />
		<lv_label translation_tag="house" />
		<lv_label translation_tag="person" />
	</view>
</screen>
```
