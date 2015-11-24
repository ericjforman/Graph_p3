# graph-p3
Update on Arduino to Processing Graph example

In Processing 3, it seems draw functions no longer work inside of serialEvent(). This update to the example code resolves this issue.

Note this causes the graph to move at the constant framerate of the Processing sketch, NOT at the rate of serial data coming in. (Sometimes this is useful to see.)
