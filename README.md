# voting-app
The folder "k8s-voting-manifest" includes YAML files with specifications for the Voting App's services. 
You can create the necessary deployments and services by running the command "kubectl create -f k8s-voting-manifest" in your current namespace (default if unchanged).
Once created, you can access the Voting App's web interface on port 31000 and the results web app on port 31001.

If you need to remove these resources, you can do so by running the command "kubectl delete -f k8s-voting-manifest".
