```xml title="lvgl_widgets_xml/v9.4.0/lv_switch.xml" source="https://github.com/lvgl/lvgl_pro/blob/0ac641547f16b87445de3e2c998c17b340844964/lvgl_widgets_xml/v9.4.0/lv_switch.xml"
<!--
Example
<lv_switch width="100" height="40"/>
-->

<widget>
    <api>
        <enumdef name="lv_switch_orientation" help="Switch orientation">
            <enum name="auto" help="Choose based on widget size"/>
            <enum name="horizontal" help="Horizontal switch"/>
            <enum name="vertical" help="Vertical switch"/>
        </enumdef>

        <prop name="orientation" type="enum:lv_switch_orientation" help="Set switch orientation"/>
    </api>
</widget>
```
