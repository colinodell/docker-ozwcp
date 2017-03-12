#Open Zwave Control Panel in a Docker Container


This container provides the Open Zwave Control Panel exposing the web server on the default port of 8090.

The open-zwave library used is based on [V1.5 with some additional customizations](https://github.com/colinodell/open-zwave/compare/V1.5...V1.5-with-customizations).

Example run command:
**docker run -d -p 8090:8090 --device=/dev/ttyACM0:/dev/ttyACM0 colinodell/ozwcp**
