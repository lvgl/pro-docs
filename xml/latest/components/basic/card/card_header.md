```xml title="examples/components/basic/card/card_header.xml" source="https://github.com/lvgl/lvgl/blob/e673591c69899a4fedd86f8d85cc59a0c06415b1/examples/components/basic/card/card_header.xml"
<!-- This component is not visible as it has zero size by default -->
<component>
	<api>
		<prop name="title" type="string" default="Title" />
	</api>
	<styles>
		<style
			name="style_main"
			width="100%"
			height="content"
			text_font="geist_semibold_20"
			layout="flex"
			flex_flow="row"
			flex_main_place="space_between"
			flex_cross_place="center"
			radius="0"
		/>
	</styles>

	<view>
		<remove_style_all />
		<style name="style_main" />

		<lv_label text="$title" />
	</view>
</component>
```
