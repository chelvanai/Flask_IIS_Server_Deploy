# Flask_ISS_Server_Deploy

pip install flask

pip install wfastcgi

Add IIS Features and enble CGI in windows setting

Go to IIS server; select Sites; Add web sites

Give site name; physical path; port number

Next go to the project folder and give permission to the IIS webapp - IIS AppPool/{your app name}

Select modifiy permission to the folder 

Finaaly give permission to python folder for IIS web app

Ater start the website
