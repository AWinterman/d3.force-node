# d3.Force-nodes #

Inherits from d3.Force-links-change and d3.Force-links-status, and implements
two new methods-- one for removing all links from a node, and then an
additional method which also removes the node itself.

```
var node_manager = new Node(loops, directed, multiedge)

node_manager.orphan(lonely_node, force)
node_manager.remove(bad_node, force)
```
