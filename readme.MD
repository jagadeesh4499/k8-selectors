# Selectors

Taint the Node
--------------
kubectl taint nodes <node_name> hardware=gpu:NoSchedule

Label the node
--------------
kubectl label nodes <node_name> hardware=gpu

Ref: https://kubernetes.io/docs/tasks/configure-pod-container/assign-pods-nodes