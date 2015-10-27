## PhpStorm Live Template for CodeIgniter ver.3 (maybe work in ver.2) 
Jetbrain PhpStorm (IntelliJ IDEA) has a Live Template function.
Thanks to this feature, makes it very well assist the coding work.
As programming becomes more easier of CodeIgniter (ver.3), I tried to add a rule of LiveTemplate.

###1. How to install.
・Put the **CodeIgniter.xml** and **CodeIgniter_validation_rules.xml** in the folder(see below.) .


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

#### CodeIgniter snippets.


snippet	| expand	
----------------| -------------------------------------
t	| $this->	
configitem	| $this->config->item("configname")	
view	| $this->load->view("name")
library	| $this->load->library("name")
helper	| $this->load->helper("name")
model	| $this->load->model("name")
database	| $this->load->database()
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


#### CodeIgniter form_validation snippets.


Type ***"rule-"*** . PhpStorm will suggest form_validation  rules.

```php
$this->form_validation->set_rules( 'v', 'somevalue', 'rule-    
```



[CodeIgniter/Form Validation/Rule Reference](http://www.codeigniter.com/user_guide/libraries/form_validation.html?highlight=validation%20rule#rule-reference "CodeIgniter/Form Validation/Rule Reference")


snippet	| expand	
----------------| -------------------------------------
rule-required	| required              
rule-alpha	| alpha                 
rule-alpha_numeric	| alpha_numeric         
rule-alpha_numeric_spaces	| alpha_numeric_spaces  
rule-alpha_dash	| alpha_dash            
rule-numeric	| numeric               
rule-integer	| integer               
rule-decimal	| decimal               
rule-is_natural	| is_natural            
rule-is_natural_no_zero	| is_natural_no_zero    
rule-valid_url	| valid_url             
rule-valid_email	| valid_email           
rule-valid_emails	| valid_emails          
rule-valid_ip	| valid_ip              
rule-valid_base64	| valid_base64          
rule-matches	| matches[form_item]    
rule-regex_match	| regex_match[/regex/]  
rule-differs	| differs[form_item]    
rule-is_unique	| is_unique[table.field]
rule-min_length	| min_length[3]         
rule-max_length	| max_length[12]        
rule-exact_length	| exact_length[8]       
rule-greater_than	| greater_than[8]       
rule-greater_than_equal_to	| greater_than_equal_to[8]
rule-less_than	| less_than[8]            
rule-less_than_equal_to	| less_than_equal_to[8]   
rule-in_list	| in_list[red,blue,green] 
	







