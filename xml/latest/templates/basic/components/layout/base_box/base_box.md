```xml title="templates/basic/components/layout/base_box/base_box.xml" source="https://github.com/lvgl/lvgl_pro/blob/ccb93b776a23f6112f664d039e9d9181ef18a761/templates/basic/components/layout/base_box/base_box.xml"
<component>
	<!-- INTERNAL — use `container`/`panel` instead. The one place
	     <remove_style_all/> runs, so the screen's bound text_color can
	     inherit down. Kept separate so extenders' locals apply AFTER the
	     wipe (same-view locals would be erased by it). -->
	<styles>
		<!-- Transparent + flex; hugs content until a size is set. -->
		<style name="style_base_box" width="content" height="content" layout="flex" flex_flow="column" />
	</styles>

	<view extends="lv_obj">
		<remove_style_all />
		<style name="style_base_box" />
		<style name="style_scrollbar" selector="scrollbar" />
	</view>
</component>
```
