```xml title="tutorials/components/column/column.xml" source="https://github.com/lvgl/lvgl_pro/blob/4411bce793c8d14a40694953502f8f6a168cb348/tutorials/components/column/column.xml"
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
