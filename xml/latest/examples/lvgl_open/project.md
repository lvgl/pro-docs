```xml title="examples/lvgl_open/project.xml" source="https://github.com/lvgl/lvgl_pro/blob/e56c9b98c7af2f263a49f8b0fe5756d8aee2ff5a/examples/lvgl_open/project.xml"
<project lvgl_version="9.6.0" name="lvgl_open_examples">
	<targets>
		<target name="large">
			<display width="600" height="320" />
			<memory
				bandwidth="2MB/s"
				name="ospi"
				size="4MB"
				section="the_ospi_section"
			/>
		</target>
	</targets>
</project>
```
