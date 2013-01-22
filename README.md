problems_in_sessions
====================

this is the link for my gist: 
https://gist.github.com/4592835

this contains three files which i am using for my all projects. and these are working fine for individual sites. 
but today wen i used two of my project in which i used this same script for session / login. 
this script get conflict with each others session. suppose if i am logged_in in site 1 then even if i refresh on site 2 my broswer will make me logout from site 1. and vice versa. 
i think this is because of line no. 47 in session.php which checkes for the entry. 
but problem is if i logged_in in site 1 then this will add entry in table ActiveUsers but in both the databases (database 1 as well as database 2). i am confused why this is happened.
