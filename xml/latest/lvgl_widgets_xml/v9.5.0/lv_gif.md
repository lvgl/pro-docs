```xml title="lvgl_widgets_xml/v9.5.0/lv_gif.xml" source="https://github.com/lvgl/lvgl_pro/blob/64ebc7a7b6db60ed63db7ca4dae1573c702c882a/lvgl_widgets_xml/v9.5.0/lv_gif.xml"
<!--
Example:
<lv_gif src="my_gif" loop_count="5"/>
-->

<widget>
	<api>
		<prop name="src" type="image" help="The source for the gif (raw data or a file)"/>
		<prop name="loop_count" type="int" help="Number of repeats. If not set the information form the gif will be used"/>

        <parts>
            <part name="main" help="Style the GIF: `image_recolor`, `image_recolor_opa` and `image_opa`. Background, border, etc can be added too."/>
        </parts>
	</api>
</widget>
```
