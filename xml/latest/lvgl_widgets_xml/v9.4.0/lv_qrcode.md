```xml title="lvgl_widgets_xml/v9.4.0/lv_qrcode.xml" source="https://github.com/lvgl/lvgl_pro/blob/64ebc7a7b6db60ed63db7ca4dae1573c702c882a/lvgl_widgets_xml/v9.4.0/lv_qrcode.xml"
<!--
Example
<lv_qrcode size="150" dark_color="0x2596be" light_color="0xffffff" data="https://lvgl.io"/>
-->

<widget>
    <api>
        <prop name="size" type="int" help="Set the QR code size in pixels (instead of width/height)"/>
        <prop name="dark_color" type="color" help="Set the foreground color"/>
        <prop name="light_color" type="color" help="Set the background color"/>
        <prop name="data" type="string" help="Set the encoded UTF-8 data"/>
        <prop name="quiet_zone" type="bool" help="Add margin around the QR code"/>
    </api>
</widget>
```
