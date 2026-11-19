# Exploiting XXE to retrieve data by repurposing a local DTD
# Descriptiom
This lab has a "Check stock" feature that parses XML input but does not display the result. To solve the lab, trigger an error message containing the contents of the /etc/passwd file. You'll need to reference an existing DTD file on the server and redefine an entity from it. 

## Steps
I access the lab and focus on the name of this lab. This lab mentions retrieve data by repurposing a local DTD. So I have to determine the DTD file exist in this system.
First, I declared a DOCTYPE with an external entity pointing to a file that actually exist
