# splunk_private-app_template
Template layout of custom private apps to be installed to illinois.splunkcloud.com

### NOTES
1) No /local folder
2) Update /default/app.conf 's "label" & "description"
3) /lookups can be added, anything there is "permanent"
4) Name of app follows following format:
   * **AAA\_conf-\<file\>\_[stanza]\_{setting, optional}\_(value, optional)**
   * **AAA\_conf\_\<description\>\_{additional optional descriptions}**
6) Update this section with official Splunk documentation about the file & stanza that is being managed
7) Every time an app needs to be re-validated & uploaded, increment the "version" value in app.conf
8) App prefix used for different "types" of custom apss
  * **AAA** = .conf files and configurations
  * **AA** = management apps
  * **A** = sidecar apps of existing Splunkbase apps
