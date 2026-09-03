```xml title="lvgl_widgets_xml/v9.4.0/lv_animimg.xml" source="https://github.com/lvgl/lvgl_pro/blob/265736d202455b16b44f0ce9f8ce8a1be1c5ed5e/lvgl_widgets_xml/v9.4.0/lv_animimg.xml"
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
    </api>
</widget>
```
