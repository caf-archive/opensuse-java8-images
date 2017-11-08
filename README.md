# openSUSE and Java 8 Runtime image

This project builds an openSUSE-based image which includes the OpenJDK 8 Runtime Environment. It can be used as a base image by projects which require Java 8.

### Startup Scripts
Any executable scripts added to the `/startup/startup.d/` directory will be automatically run each time the container is started (assuming the image entrypoint is not overwritten).

### Certificate Installation
The image comes pre-installed with several startup scripts which provide a mechanism to extend the CA certificates which should be trusted.
