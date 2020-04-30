# PDF Compactor Project
a web application that allows users to upload a pdf file and return a compacted version of the file based on the user’s specified DPI. 

# Process Of the whole full_stack
<img alt="frontend-backend-diagram.png" src="./image/frontend-backend_diagram.png" width="400" text-align="center">

# Tools
## Frontend
 Bootstrap + HTML + JQuery + CSS
## Backend  
 Node.js + express + multer + Ghostscript
## The pdf compression rools URL
https://github.com/ourarash/shrinkpdf

# Start The Project
Firstly, install NodeJs (https://nodejs.org/en/download/) and Ghostscript (check this link carefully https://github.com/ourarash/shrinkpdf). 
```bash
git clone https://github.com/guiquansun/PDF-Compactor.git
cd PDF-Compactor
npm install
```

Running:
```bash
node app.js
```
Now open your browser to http://localhost:3000
<img alt="first-page" src="./image/first-page.png" width="400">
Upload a pdf file and the page is switched.
<img alt="second-page" src="./image/second-page.png" width="400">
CLick Process button to do the compression
<img alt="third-page" src="./image/third-page.png" width="400">
See your history files
<img alt="fourth-page" src="./image/fourth-page.png" width="400">

# Group members
Linxin Mai linxinma@usc.edu
Guiquan Sun  gsun@usc.edu
