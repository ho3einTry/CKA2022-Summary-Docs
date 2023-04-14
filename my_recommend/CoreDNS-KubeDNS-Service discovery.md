# CoreDNS an KubeDNS and Service Discovery
## should be use them
 ## In all of pods should be Dns address in ***/etc/resolv.conf***

 ><code> # cat /etc/resolver.conf <br>
  nameservers 10.96.0.10 <br>
  search default.svc.cluster.local svc.cluster.local cluster.local
  </code>
## better idea is  use environment variable for given server name to the pods and then set server name environment variable to the /etc/resolv.conf in dockerfile 