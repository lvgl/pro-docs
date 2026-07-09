```xml title="examples/components/basic/div/div.xml" source="https://github.com/lvgl/lvgl/blob/d8e8c86508ddcabc4bf27676b63fa2ad0a7626fb/examples/components/basic/div/div.xml"
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
