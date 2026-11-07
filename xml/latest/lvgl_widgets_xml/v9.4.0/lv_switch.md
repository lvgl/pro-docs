```xml title="lvgl_widgets_xml/v9.4.0/lv_switch.xml" source="https://github.com/lvgl/lvgl_pro/blob/e56c9b98c7af2f263a49f8b0fe5756d8aee2ff5a/lvgl_widgets_xml/v9.4.0/lv_switch.xml"
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
