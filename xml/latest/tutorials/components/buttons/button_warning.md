```xml title="tutorials/components/buttons/button_warning.xml" source="https://github.com/lvgl/lvgl_pro/blob/9bccbd4302cf1f425d2a9790d8b6133170e81650/tutorials/components/buttons/button_warning.xml"
<!-- Create a new button variant based on the normal button
	 just by overwriting a single color.  -->
<component>
	<!-- The API is not inherited from  "button_normal"
	     so describe the API of the warning button here-->
	<api>
		<prop name="label_text" type="string" default="Warning!" />
	</api>

	<!-- Extend the normal button, and use its API to pass properties -->
	<view extends="button_normal" style_bg_color="#yellow" label_text="$label_text" />
</component>
```
