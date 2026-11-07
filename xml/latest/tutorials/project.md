```xml title="tutorials/project.xml" source="https://github.com/lvgl/lvgl_pro/blob/e56c9b98c7af2f263a49f8b0fe5756d8aee2ff5a/tutorials/project.xml"
<project name="tutorials" lvgl_version="9.6.0" theme="default">
	<targets>
		<target name="target1">
			<display width="480" height="320" />
			<memory name="int_ram" size="1MB" />
			<memory name="int_flash" size="2MB" bandwidth="100MB/s" />
		</target>
	</targets>
</project>
```
