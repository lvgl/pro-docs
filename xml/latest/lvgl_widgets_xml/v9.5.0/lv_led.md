```xml title="lvgl_widgets_xml/v9.5.0/lv_led.xml" source="https://github.com/lvgl/lvgl_pro/blob/ccb93b776a23f6112f664d039e9d9181ef18a761/lvgl_widgets_xml/v9.5.0/lv_led.xml"
<!--
Example
<lv_led color="0xff0000" brightness="70%" />
-->

<widget>
    <api>
        <prop name="color" type="color" help="Set the color of the LED"/>
        <prop name="brightness" type="opa" help="Set how dark or bright the LED should be"/>

        <parts>
            <part name="main" help="Style the LED: background, border, `radius` and shadow properties. `bg_color`, shadow and border colors are overridden by `color`, and `brightness` scales the overall look."/>
        </parts>
    </api>
</widget>
```
