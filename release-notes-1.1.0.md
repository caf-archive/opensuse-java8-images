#### Version Number
${version-number}

#### New Features
 - Startup script drop-in directory  
    A facility has been added for automatically running startup scripts.  Any executable scripts added to the `/startup/startup.d/` folder will automatically be run each time the container is started (assuming the image entrypoint is not overwritten).

 - Automatic certificate installation  
    Startup scripts which provide a mechanism to extend the CA certificates which should be trusted have been pre-installed.

#### Known Issues
 - None
