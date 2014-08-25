# cli-bp

boilerplate for commander-style node cli apps. 

## gettting started

1. Download as zip
2. npm install
3. chmod u+x ./lib/main.js
4. Run with ./lib/main.js

## make it global

`"bin": {"cli-bp": "lib/main.js"}` maps the cli-bp command 
to your main.js script. On the command-line, navigate to the 
directory which contains your files and install your script 
globally via npm (this might require using sudo): 

`sudo npm install -g`

Note that after every change to main.js you will need to re-run
the npm install -g command to see your changes reflected globally.




