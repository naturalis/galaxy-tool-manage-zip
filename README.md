# galaxy-tool-manage-zip
Manage zip tool for galaxy (transferred from old galaxy). The original github page can be found here: https://github.com/naturalis/Galaxy-Pipeline
## Getting Started
### Installing
Installing the tool for use in Galaxy  
(user: **galaxy**)
```
cd /home/galaxy/Tools
```
```
git clone https://github.com/naturalis/galaxy-tool-manage-zip 
```
Add the following line to /home/galaxy/galaxy/config/tool_conf.xml
```
<tool file="/home/galaxy/Tools/galaxy-tool-manage-zip/manage_zip.xml" />
```
