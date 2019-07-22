# Background
So I get this massive (1 inch thick) catalog mailed to me every
few months. Its full of stuff I'll probably never buy like 
industrial poly bags, stackable office chairs, 100's of different 
kinds of latex gloves.. you name it. Anyways, it's all on their 
website too so this thing is a waste of resources so I decide to 
get myself off their mailing list. I find their "mailing 
preferences" webpage and as I complete the first field which is a 
10 digit Customer # they assigned to me, all the rest of the 
fields including my address get auto populated. I'm creeped out 
because I didnt have to do any validation or complete any 
captchas. I haven't dont any more investigating but I'm fairly 
sure I just stumbled into a terribly unprotected api. 

# Propsition
I propose we explore how the auto population works. And then 
discover what kinds of limitations it has (max tries per minute, 
max tries per IP, etc). If there are no limitations, I 
subsequently propose we create a python script to try every 10 
digit combonation, and record the results to a database.

# Vector 
**URL:** https://www.uline.com/CustomerService/CustomizeMailing  
**Company #:** ########## (hidden for my own privacy)  