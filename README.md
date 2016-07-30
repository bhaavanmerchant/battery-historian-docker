# battery-historian-docker

A docker image to run battery-historian, a tool to monitor your Android battery usage.

A single docker image to avoid the need to install a very dependency heavy software, It includes:

- Battery Historian (https://github.com/google/battery-historian)
- Go runtime
- Closure dependencies
- Java runtime
- Python 2.7

To run, execute:
`docker run -d -p 9999:9999 bhaavan/battery-historian`

You can then go to `http://localhost:9999` on your browser and upload your Android bugreports.

