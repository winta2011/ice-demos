This demo is a minimal Ice "hello world" application. Each time the
client is run a "sayHello" invocation is sent to the server.

To run the demo, first start the server:

$ python Server.py

In a separate window, start the client:

$ python Client.py

Note that this demo hardwires port 10000. If port 10000 is not
available on your machine, you need to edit both client and server
to use a free port.

To run the server with web socket support:

$ python Server.py --Ice.Default.Protocol=ws

To run the client with web socket support:

$ python Client.py --Ice.Default.Protocol=ws
