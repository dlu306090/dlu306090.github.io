This is the DTCB website.

To upload or download files to the website, open terminal and type: ssh dtcb@arizona.princeton.edu, and cd into the public_html folder (type “cd public_html” into the terminal). You should see all the files on our website, and you can use scp if you want to copy things over. (Look this up online.) Can also use FTP client instead. If you have a mac you can follow instructions here: https://princeton.service-now.com/kb_view.do?sysparm_article=9268 Annie uses the steps in the link above to get files onto the server and then uses the terminal to move things into the public_html folder. (Cause for some reason the contents of  the public_html folder aren’t visible in the Finder.)

If you accidentally ever get a 403 Forbidden error when you try to view the website, it’s probably because you didn’t change the permissions to be read-execute for the public. You can do this by going into ssh and typing this command: “chmod -R 755 public_html/”.

Sometimes the website might not update after you edit it. Try opening it in an incognito window or clear your browsing history because the pictures are probably cached.

Most edits will be done in the index.html file, especially if you’re just changing text. Sometimes images and height/width of elements on the page can be changed in styles.css. The img folder contains all images used on the website.

"Boxify" One Page Website Template by Peter Finlan for Codrops

Demo: http://tympanus.net/Freebies/Boxify/
Download and article: http://tympanus.net/codrops/?p=22554

Use it freely but please do not redistribute or sell.
Read more here: http://tympanus.net/codrops/licensing/

Enjoy!