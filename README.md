# HTML-parser

Early in 2015, DMA had to do a massive curriculum migration into a new format that was, among other things, more modern and mobile-responsive. Source curriculum 
would be coming in an old template, or from google docs, where new material was being created. Rather than port it all manually (copy paste ad nauseum),
I wrote a script to automate as much of the process as could be. 

This is an early version - still using Regex and for loops to parse html. Later versions used jQuery to display old content (which was all, in some way or another, 
in a table), and grab .innerHTML as a means of detecting table rows and copying content. 
