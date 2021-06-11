default.conf is tuned to work inside docker container.

This helm charts assumes that you have Nginx ingress and cert manager running to provision the tls, if you dont have cert manager controller comment the tls part.


To Apply helm chart :

helm install freshcells freshcells/ --values freshcells/values.yaml --namespace freshcells