# embroider-issue-349

Demo for issue https://github.com/embroider-build/embroider/issues/349.

To see the problem, run:

```
EMBROIDER_CONCAT_STATS=true ember build
```

With `ember-table` installed you'll see the following issue:

```
Building into /private/var/folders/d8/h8767lqn0jb3h53qj9v70_l80000gn/T/embroider/1ed8e7
Environment: development
cleaning up...
Build Error (WaitForTrees)

ENOENT: no such file or directory, stat '/private/var/folders/d8/h8767lqn0jb3h53qj9v70_l80000gn/T/embroider/1ed8e7/PATH_TO_PROEJCT/embroider-issue-349/node_modules/css-element-queries/src/ResizeSensor.js'
```
