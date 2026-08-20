```xml title="templates/basic/components/controls/button/button.xml" source="https://github.com/lvgl/lvgl_pro/blob/ccb93b776a23f6112f664d039e9d9181ef18a761/templates/basic/components/controls/button/button.xml"
<component>
	<previews>
		<preview name="default" width="200" />
	</previews>

	<api>
		<prop name="text" type="string" default="Button" help="Button caption" />
		<prop name="icon" type="image" default="" />
		<prop name="bg_color" type="color" default="#color_accent" help="Button background color" />
		<prop name="text_color" type="color" default="#color_accent_text" help="Caption color" />
		<prop name="radius" type="int" default="#radius_default" help="Corner radius" />
	</api>

	<styles>
		<style name="style_button" pad_hor="#space_lg" pad_ver="#space_md" flex_cross_place="center" pad_gap="#space_sm" />
		<style name="style_button_pressed" recolor="#color_track" recolor_opa="40%" />
		<style name="style_button_icon" image_recolor_opa="100%" translate_y="-2" />
	</styles>

	<!-- Button with optional icon + centered caption.
	     Attach behavior as child events:
	         <button text="Save"><event_cb callback="on_save" trigger="clicked"/></button>
	     Pressed state darkens via recolor. -->
	<view
		extends="lv_button"
		style_bg_color="$bg_color"
		style_text_color="$text_color"
		style_radius="$radius"
		flex_flow="row"
	>
		<style name="style_button" />
		<style name="style_button_pressed" selector="pressed" />
		<lv_image
			src="$icon"
			hidden="{!icon}"
			style_image_recolor="$text_color"
		>
			<style name="style_button_icon" />
		</lv_image>
		<lv_label align="center" text="$text" hidden="{!text}" />
	</view>
</component>
```
