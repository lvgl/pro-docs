```xml title="examples/lvgl_open/project.xml" source="https://github.com/lvgl/lvgl_pro/blob/6a64e6a851619119c359a5ae0ca6e8091732a70c/examples/lvgl_open/project.xml"
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
