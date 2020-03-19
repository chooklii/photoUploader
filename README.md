# photoUploader

React FrontEnd and Express BackEnd. FrontEnd build with Webpack and served through Express Server.

Default folder for saves is within usb - Can be changed within server.js

# first time:

1. Create own config.js - Template is given inside src/

2. Run "npm install" to install all dependencies (If not there install needed stuff like node and so on) 

# to run:

1. "run npm run build" to put all JS-Files together 
-> Not needed, if there are no changes inside of those files

2. "node server.js" to run Server

# Endpoints:

GET /             -> Photo-Upload Page

GET /healthcheck  -> Healthcheck if USB is there
GET /photofolders      -> Get all Photo-Folders
GET /filefolder        -> Get all File-Folders

GET /photonames?folder=Name -> Get all File-Names for one folder
GET /photo?path="PATH_TO_PHOTO -> Get one Foto

POST /fileupload      -> Endpoint for File-Upload
POST /photoupload      -> Endpoint for Foto-Upload

