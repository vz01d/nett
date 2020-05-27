# nett
The new Internet. Built with vlang

nett is entirely running in your client it has a running webserver, p2p database and an interface.

This **REALLY** serverless architecture prevents censorship while maintaining security aspects of the modern web.

## How does it work?

The net(t)work is built similar to the blockchain approach connecting nodes and having an audience of nodes to verify each others messages in realtime. A node can connect to as many nodes as it "likes", a connection will be made when the user is "browsing" a node. Nodes can subscribe to each other to get notified of updates. Each node has it's own "database" and there's no such thing like REST API. One node can send an event to (n) nodes and they can decide if they want to pick it up or not.
