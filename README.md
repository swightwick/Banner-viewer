# Banner-viewer

Node script to create a HTML page displaying iframes of banners in a specified directory for quick comparasion. 

## Process

1. Copy files to parent directory of banners
2. Set sub folder path of the source of banners, in my case ./src. Change this in iframe.js - var dirTree
3. run 'node iframe.js' in terminal
4. The script creats a json of the sub folder specified called directory.json
4. Local server is started and iframe.html is loaded using directory.json as directory paths for the iframe sources
5. Page runs with all banners shown in iframes

## To do

1. Exclude dot files from json creation
2. Get heights of iframe content and apped to iframe html

