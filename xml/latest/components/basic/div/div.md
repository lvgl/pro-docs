```xml title="examples/components/basic/div/div.xml" source="https://github.com/lvgl/lvgl/blob/98c975f3a279fd3db99ac75c6c250b36e25aec5a/examples/components/basic/div/div.xml"
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
