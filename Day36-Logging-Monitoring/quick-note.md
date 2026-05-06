K8s not offer monitoring and logging by default.

Metrics Server:
We install Metrics Server to monitor and logging the resources in k8s cluster.

CRICTL:
When API server not respond -> kubectl client will not work.
So, we use crictl. (will work at container level)
Ex: crictl ps

we are using “containerd” instead of Docker.
- We troubleshoot the cluster at the c**ontainer level.**
- In the case of **Docker runtime**, we use client: docker `docker ps.`
- In the case of **containerd**, we use client: critcl `crictl ps`