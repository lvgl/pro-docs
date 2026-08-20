```xml title="examples/lvgl_open/project.xml" source="https://github.com/lvgl/lvgl_pro/blob/ccb93b776a23f6112f664d039e9d9181ef18a761/examples/lvgl_open/project.xml"
<project lvgl_version="9.5.0" name="lvgl_open_examples">
	<targets>
		<target name="large">
			<display width="600" height="320" />
			<memory bandwidth="2MB/s" name="ospi" size="4MB" section="the_ospi_section" />
		</target>
	</targets>
</project>
```
