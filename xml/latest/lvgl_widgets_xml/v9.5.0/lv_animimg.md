```xml title="lvgl_widgets_xml/v9.5.0/lv_animimg.xml" source="https://github.com/lvgl/lvgl_pro/blob/4d05fc79f26b1a8daf2c0134018f3d07c6f19286/lvgl_widgets_xml/v9.5.0/lv_animimg.xml"
<!--
Example
<lv_animimg src="img1 img2" duration="300" repeat_count="3"/>
-->

<widget>
    <api>
        <const name="infinite" help="Repeat the animation infinitely"/>
        <prop name="src" type="image_src[count]" help="Set the image sources, separated by spaces"/>
        <prop name="duration" type="int" help="Set how long one animation cycle runs (ms)"/>
        <prop name="repeat_count" type="int" help="Set how many times the animation repeats"/>

        <parts>
            <part name="main" help="Style the animated image: `image_recolor`, `image_recolor_opa`, `image_opa` and the transform properties. Background, border, etc can be added too."/>
        </parts>
    </api>
</widget>
```
