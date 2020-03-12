<!-- http file server writen by Go -->

1. run on docker:
   share the specific path: docker run --rm -p 8000:8000 -v path-you-want-to-share:/file sevendollar/http-file-server
   share the current path: docker run --rm -p 8000:8000 -v $(pwd):/file sevendollar/http-file-server

2. go to release, download macos executable file and run:
   - http-file-server-darwin

3. go to release, download linux executable file and run:
   - http-file-server-linux
