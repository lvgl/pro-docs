```xml title="tutorials/components/buttons/button_warning.xml" source="https://github.com/lvgl/lvgl_pro/blob/b50910a3acc7ed2355e2e41eabaca2630a9e383d/tutorials/components/buttons/button_warning.xml"
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
