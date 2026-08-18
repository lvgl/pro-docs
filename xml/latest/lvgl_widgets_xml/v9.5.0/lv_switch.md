```xml title="lvgl_widgets_xml/v9.5.0/lv_switch.xml" source="https://github.com/lvgl/lvgl_pro/blob/c4a99074ccc701fd983c2e1e0b01b1ba7645abe7/lvgl_widgets_xml/v9.5.0/lv_switch.xml"
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

        <parts>
            <part name="main" help="The background track: background properties. padding shrinks the indicator."/>
            <part name="indicator" help="The fill that shows the on/off state: background properties. Use the 'checked' state (e.g. indicator|checked) for the ON color."/>
            <part name="knob" help="The sliding handle: background, border, shadow and padding properties."/>
        </parts>
    </api>
</widget>
```
