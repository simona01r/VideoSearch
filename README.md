# Tubifying via FancyBox
VideoSearch is a video search engine built using the Youtube API v3.
Features/Technologies:
- HTML5
- CSS3
- JavaScript
- jQuery
- Youtube Data API v3
- Fancybox

I used FancyBox plugin to open videos and prev&next paging through API Page Tokens
The results are opened and displayed in a lightbox from FancyBox, otside of Youtube

Create GET request on Youtube API through JQuery
Loop throuh ResultSet and insert into HTML dinamically
Select Youtube API from Developer Google Console & create credential for the project

Resource type: search; 
method: list; 
parameters:  part,
             q,
             type,
             nextPageToken,
             prevPageToken     
values:      snippet,
             query, 
             video
             retreive the next page in the ResultSet
             retreive the next page in the ResultSet             
