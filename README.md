# WordpressUser-Enumeration-Using-ID
User Enumeration 

this script takes advantage of the vulnerability in wordpress where an individual can enumerate all the WordPress
usernames iterating through the author archives.  Whenever a post is published, the username or alias is shown as the author.

For example, the URL http://site.com/?author=1 will show all the posts from user id 1.

to do list:
all you need to do is configure your proxychain in /etc/proxychains.conf before starting the script.

if you want you can reduce or increase the number of users to enumerate by reducing the value in the while loop (n <= 10) 


NOTE: the larger the number the increase in number of tabs firefox will open
