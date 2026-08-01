```xml title="lvgl_widgets_xml/v9.5.0/lv_led.xml" source="https://github.com/lvgl/lvgl_pro/blob/64ebc7a7b6db60ed63db7ca4dae1573c702c882a/lvgl_widgets_xml/v9.5.0/lv_led.xml"
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
