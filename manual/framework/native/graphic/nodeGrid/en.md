#How to use NodeGrid

The `grid` feature has been removed from Node, together with function `Node::setGrid()` and `Node::getGrid()`
The alternative way to use `grid` feature is using the new class `NodeGrid`

serveral steps are involved in using `NodeGrid`
1. create a instance of `NodeGrid`
2. call `NodeGrid::setGrid` function to set a grid to the instance
3. call `Node::addChild` or `NodeGrid::setTarget` to add children or target to the instance

`grid` feature will affect both children and target of the NodeGrid `target`.
