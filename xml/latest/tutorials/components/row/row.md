```xml title="tutorials/components/row/row.xml" source="https://github.com/lvgl/lvgl_pro/blob/6a64e6a851619119c359a5ae0ca6e8091732a70c/tutorials/components/row/row.xml"
<!-- Just place the children next to each other.
     The container's size will be according to the content -->
<component>
	<styles>
		<style
			name="style_base"
			width="content"
			height="content"
			layout="flex"
			flex_flow="row"
		/>
	</styles>
	<view>
		<remove_style_all />
		<style name="style_base" />
	</view>
</component>
```
