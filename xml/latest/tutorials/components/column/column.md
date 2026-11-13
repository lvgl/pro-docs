```xml title="tutorials/components/column/column.xml" source="https://github.com/lvgl/lvgl_pro/blob/2b291f2ba054540cc7f4397e419866f9e1f5a84f/tutorials/components/column/column.xml"
<!-- Just place the children below each other.
     The container's size will be according to the content -->
<component>
	<styles>
		<style
			name="style_base"
			width="content"
			height="content"
			layout="flex"
			flex_flow="column"
		/>
	</styles>
	<view>
		<remove_style_all />
		<style name="style_base" />
	</view>
</component>
```
