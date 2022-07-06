Bootstrap= html +css+ javascript
 HTML= struccture
 CSS= Presentation
 Javascript= dynamic brhavior
 
 javascript is a programming language
 50+ frameworks
 over 97% websites are using javascript
 
 To execute javascript code:
 
 1. include js code need to be put inside <script> tag within html page
 2. can be written in <head> or <body>
 3. create external .js filesand include them in the html files
 by using <script> tag
 4. <script> tag not needed in external .js file
 5. keep all the .css anad .js files inside the body section
 <script>
 
 //javascript code
 
 </script>
 
 install node.js in the machine
 create a .js file to run in the command:
 node<file-name>.js
 
 Transpilers: used to convert TypeScript code to javascript because broweser can only parse javascript
 -git
 -operators
 -conditional constructs (if-else, switch)
 -loops
 --while
 --do-while
 --for
 -functions
 -storage in html 5 (local and session storage)
 -callback functions
 
 
 GIT
 ----------------
 -open source
 -scalable
 -secure
 -speed
 
 
 Github/bitbucket/ git lab
 
 -create a git repository in the local machine 
 -open the cmd/termainal from the git repository folder
 -intilize the git repository
	$ git init (the folder will be converted to a git repository)
-Keep the files/folder in the git repository
-See the status of the git repository
	if any files/folder added/updated
	$ git status
-To add files in the git:
	$ git add <file-name> --> for 1 file only
	$ git add .[current working directory] --> >1 files
	$ git add *.html
-after adding the file/folder to git, commit to rep.
	$ git commit -m "Commiting HTML Files"
	
Remote Rpository:
Github:
	-Public repository
	-Private repository //commercial
	9.1 create an account on guthub
	9.2 create a rep. on the github
	9.3 connectthe local rep. with the remote rep.
		$ git remote add origin
		https://github.com/berrybore/Java-fullstack-rep.git
	9.4 push the changes in the git hub
		$ git push -u origin master
		
		*REEAD ABOUT MARKDO*