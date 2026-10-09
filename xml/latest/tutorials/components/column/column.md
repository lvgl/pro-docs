```xml title="tutorials/components/column/column.xml" source="https://github.com/lvgl/lvgl_pro/blob/4d7ba569dca8c4f02e925c92a83dad5beedb3ad9/tutorials/components/column/column.xml"
<!-- Just place the children below each other.
     The container's size will be according to the content -->
<component>
	<styles>
		<style name="style_base" width="content" height="content" layout="flex" flex_flow="column" />
	</styles>
	<view>
		<remove_style_all />
		<style name="style_base" />
	</view>
</component>
```
