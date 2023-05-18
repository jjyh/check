# check
shinylive upload sandbox
Objective: create a serverless Shiny applications with Python
Preparatory:
1. cd in terminal (e.g. Anaconda prompt) to one level above the working directory
2. ensure the .py file is called app.py  
Compile & Upload:  
N.B. shiny static calls are superseded by shinylive (if not previously used, the following command will take some time to download shinylive from github e.g. to AppData\Local
3. on the terminal (in that directory) "shinylive export _inputdir_ _outputdir_" e.g. in our case "shinylive export check doc"
4. upload doc file in entirety to github
5. set up github pages "Build and Deployment" to main branch, doc folder
6. access page at _username_.github.io/_repository_
