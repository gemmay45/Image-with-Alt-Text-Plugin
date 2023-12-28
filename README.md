To test the Plugin, follow instructions to copy plugin to the project
https://docs.craftercms.org/en/4.1/by-role/developer/composable/extensions/resources/form-control-plugins.html

Append below to after image-picker control in site-config-tools.xml (Location (In Repository) SITENAME/config/studio/administration/site-config-tools.xml)

                <control>
                    <plugin>
                        <pluginId>org.craftercms.plugin.excontrol</pluginId>
                        <type>control</type>
                        <name>image-with-alt-text</name>
                        <filename>main.js</filename>
                    </plugin>
                    <icon>
                        <class>fa-picture-o</class>
                    </icon>
                </control>
