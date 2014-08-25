The important part here is "bin": {"gitsearch": "gitsearch.js"} as this maps the gitsearch command to your gitsearch.js script. On the command-line, navigate to the directory which contains your files and install your script globally via npm (this might require using sudo).

The only draw back to this is after every change to gitsearch.js you will need to re-run the npm install -g command to see your changes reflected globally.

Command-line utilities are particularly useful when it comes to input and output operations. Options and arguments passed into a command can be accessed via process.argv. Adding console.log(process.argv); to your script and running your command with an option should return something like this:


