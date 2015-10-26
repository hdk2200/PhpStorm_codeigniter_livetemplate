## PhpStorm Live Template for CodeIgniter ver.3 (maybe work in ver.2) 
Jetbrain PhpStorm (IntelliJ IDEA) has a Live Template function.
Thanks to this feature, makes it very well assist the coding work.
As programming becomes more easier of CodeIgniter (ver.3), I tried to add a rule of LiveTemplate.

###1. How to install.
・Put the **CodeIgniter.xml** in the folder(see below.) .


> Windows: &lt;your home directory&gt;\.&lt;product name&gt;&lt;version number&gt;\config\templates<br>
> Linux: ~/.&lt;product name&gt;&lt;version number&gt;/config/templates<br>
> OS X: ~/Library/Preferences/&lt;product name&gt;&lt;version number&gt;/templates<br>

> ex.) Windows<br>
> C:\Users\ussername\\.WebIde90\config\templates\CodeIgniter.xml

[PhpStorm 9.0.0 Help Live Templates](https://www.jetbrains.com/phpstorm/help/live-templates.html "PhpStorm 9.0.0 Help Live Templates")


・Another way,you can import **codeigniter_livetemplate.jar** from menu( File / import settings...).

###2. Functions

Since it is troublesome to typeing "$this->", you can complete in the snippet.
Just write a snippet and Code Completion (Ctrl + Space) or LiveTemplate "COMMAND (CTRL) + J.


###3.support snippets.


snippet	| expand	
----------------| -------------------------------------
t	| $this->	
configitem	| $this->config->item("configname")	
benchmark	| $this->benchmark->	
config	| $this->config->	
controller	| $this->controller->	
hooks	| $this->hooks->	
input	| $this->input->	
lang	| $this->lang->	
load	| $this->load->	
log	| $this->log->	
output	| $this->output->	
router	| $this->router->	
security	| $this->security->	
uri	| $this->uri->	
db	| $this->db->	
dbforge	| $this->dbforge->	
dbutil	| $this->dbutil->	
calendar	| $this->calendar->	
email	| $this->email->	
encrypt	| $this->encrypt->	
encryption	| $this->encryption->	
form_validation	| $this->form_validation->	
ftp	| $this->ftp->	
image_lib	| $this->image_lib->	
migration	| $this->migration->	
pagination	| $this->pagination->	
parser	| $this->parser->	
table	| $this->table->	
trackback	| $this->trackback->	
typography	| $this->typography->	
unit_test	| $this->unit_test->	
upload	| $this->upload->	
agent	| $this->agent->	
xmlrpc	| $this->xmlrpc->	
xmlrpcs	| $this->xmlrpcs->	
zip	| $this->zip->	
cache	| $this->cache->	
session	| $this->session->	

