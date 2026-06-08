```xml title="examples/components/basic/div/div.xml" source="https://github.com/lvgl/lvgl/blob/7785e89ec4cef12ae82b026aa653c580dd7a2d2a/examples/components/basic/div/div.xml"
<!-- Mimic the behaviour of a HTML <div>. 100% width, 
     content height, fully transparent, flex colum layout -->
<component>
	<styles>
		<style name="style_main" width="100%" height="content" layout="flex" flex_flow="column" />
	</styles>
	<view>
		<remove_style />
		<style name="style_main" />
	</view>
</component>
```
