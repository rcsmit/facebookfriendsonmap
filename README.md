# facebookfriendsonmap
Not so easy. And forbidden by the ToS of Facebook. But I succeeded


Steps:
1) scrape
2) geocode
3) prepare the SQL statement with http://www.convertcsv.com/csv-to-sql.htm
4) import the data in your MySQL 
5) showmap

I also saved the file produced at step one to my harddisk. 
By manipulating the html-file (don't ask me how, I think I replaced "<IMG SRC=" with xxx from the sourcefile, copied everything in a texteditor and did some manipulations, I could take the filenames of the profile photos. 

I resized the photofiles and uploaded them to my server.

I loaded the CSV file in Excel and added the filenames. I had some problems because of the accents in the names so take care! 

Excel doesn't allow you to save a CSV like we need in step 3, so I used the macro given in https://support.microsoft.com/en-us/help/291296/procedure-to-export-a-text-file-with-both-comma-and-quote-delimiters-i


