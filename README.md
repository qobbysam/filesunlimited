
### FilesUnlimited
This is a file server written in GO. This is a good base for a micro service file server.
This can fit in any other projects.



This application uses Minio for the the data location.

You can serve files from data location by rest server

You can write files to data location  by rpc 




The Rpc and Fileservers can be started on different machines.

This can scale horizontally really well for both rpc and restserver.



### Basic Start

Create a copy of config.Json


Start with "./main -st=all -c=path_to_config" 


#### -st

options <br>
    rest <br>
        restserver

options <br>
    rpc <br>
        rpc server


#### -c 
ignore if config.json is in the same dir as executable


### Already  in production