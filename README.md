# bgg-rules
Enter the id of a game on Boardgamegeek.com and receive a compilation of discussions in its rules forum

# How it works
Input a game's id and this app will use boardgamegeek.com's XML api (described in detail here: https://boardgamegeek.com/wiki/page/BGG_XML_API2) in order to fetch all the threads from the game's rules forum. It will then compile all the threads into a plain text format, where each thread is delimited by the thread's subject, and where each comment therein is delimited by the comment author's user name. This single text file will then be offered for download.
