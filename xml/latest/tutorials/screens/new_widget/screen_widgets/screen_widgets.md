```xml title="tutorials/screens/new_widget/screen_widgets/screen_widgets.xml" source="https://github.com/lvgl/lvgl_pro/blob/0db8cf78c5106b4829538771f6cb5d4288506cf2/tutorials/screens/new_widget/screen_widgets/screen_widgets.xml"
<screen>
	<view extends="lv_obj">
		<!-- Add your code here -->
		<!-- wd_segment is a custom widget implemented in C (see widgets/wd_segment) -->
		<wd_segment
			width="300"
			bind_value="subject_segment"
			style_pad_column="1"
		>
			<wd_segment-button text="Option 1" />
			<wd_segment-button text="Option 2" />
			<wd_segment-button text="Option 3" />
		</wd_segment>
	</view>
</screen>
```
