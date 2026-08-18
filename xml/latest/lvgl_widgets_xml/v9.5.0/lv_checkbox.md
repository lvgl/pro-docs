```xml title="lvgl_widgets_xml/v9.5.0/lv_checkbox.xml" source="https://github.com/lvgl/lvgl_pro/blob/c4a99074ccc701fd983c2e1e0b01b1ba7645abe7/lvgl_widgets_xml/v9.5.0/lv_checkbox.xml"
<!--
Example
<lv_checkbox text="Option 1"/>
-->

<widget>
    <api>
        <prop name="text" type="string" help="The label text shown next to the checkbox"/>

        <parts>
            <part name="main" help="The label and its area: text properties; `pad_column` sets the gap between the tick box and the text."/>
            <part name="indicator" help="The tick box: background, border, shadow and padding properties. `bg_image_src` sets the check icon. Use the 'checked' state (e.g. indicator|checked) for the checked look."/>
        </parts>
    </api>
</widget>
```
