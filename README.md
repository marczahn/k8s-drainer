# K8s-drainer

Sometimes for whatever reason K8s does not drain nodes when they remain not ready.

This script looks for not ready but not drained nodes and drains them. Vice versa if there are nodes ready but still drained they get uncordon'd.

The script can be run as a cron job or manually.
