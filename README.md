# node-red-to-online.wonderware.com
This is a node-red example of sending data to online.wonderware.com's REST API using the JSON format.

It is an intentionally simple example (without caching, queueing, buffering, store-forward, etc.).

Note: First install node-red-contrib-credentials via "Manage Palette" (thank you Mike Wagner!).

Then import the flow.

Then you need to supply a Bearer token, generated from YOUR online Insight solution, and put it in the Credentials node in the form:
"Bearer XXX"
See the insight help under Acquire an API Key:
https://online.wonderware.com/help/#390551.htm
and enter it in the credentials node.

Note: the below image doesn't show at flows.nodered.org nor the does the "view at github" link in the upper right corner because it somehow created a gist.github.com instead of regular github entry and those don't seem to be able to host screen shots.

If you want to see the below screenshot view it on: https://github.com/jtmoderate876/node-red-to-online.wonderware.com

![screen shot of example](https://github.com/jtmoderate876/node-red-to-online.wonderware.com/blob/master/screenshot.png)
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTEyOTU4ODUxMSwxMjY1MjM2MDkxXX0=
-->
