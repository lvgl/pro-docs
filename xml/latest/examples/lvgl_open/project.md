```xml title="examples/lvgl_open/project.xml" source="https://github.com/lvgl/lvgl_pro/blob/18e1933b22cf7c1855a2e4dd6768cbc8bc703134/examples/lvgl_open/project.xml"
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
