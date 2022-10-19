# galaxy-tool-manage-zip
tool to display zip contents, create a zip file, add items to a zip file, unpack items from a zip file,  
rename items in a zip file, delete items from a zip file or create a subset from zip.  


## Installation  
### Manual  
Clone this repo in your Galaxy ***Tools*** directory:  
`git clone https://github.com/naturalis/galaxy-tool-manage-zip`  

Make sure the script is executable:  
`chmod 755 galaxy-tool-manage-zip/manage_zip.sh`  

Append the file ***tool_conf.xml***:  
`<tool file="/path/to/Tools/galaxy-tool-manage-zip/manage_zip.xml" />`

### Ansible
Depending on your setup the [ansible.builtin.git](https://docs.ansible.com/ansible/latest/collections/ansible/builtin/git_module.html) module could be used.  
[Install the tool](https://docs.ansible.com/ansible/latest/collections/ansible/builtin/git_module.html#examples) by including the following in your dedicated ***.yml** file:  

`  - repo: https://github.com/naturalis/galaxy-tool-manage-zip`  
&ensp;&ensp;`file: manage_zip.xml`  
&ensp;&ensp;`version: master`  
