# K8s-drainer

Sometimes for whatever reason K8s does not drain nodes when they remains in a not ready status.

This small script looks for not ready but not drained nodes and drains them. Vice versa if there are nodes ready but still drained they get uncordon'd.
