# docker-tftp
A simple tftp container with download mapping


# TL;DR
docker run -p 69:69/udp -v tftp:/opt/tftp nightserv/tftp:latest

# Details
This tftp image is configured for uploading files (create). It also allows downloading of 
files, but only from /download subdirectory.
