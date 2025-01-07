# CI-CD-Pipeline-Jenkin-X

# 1 Download and Setup Kubernetes cluster
https://kubernetes.io/docs/tutorials/hello-minikube/

# 2 Download jenkin X from this url
https://jenkins-x.io/v3/admin/setup/jx3/

click on the download link to download a binary

# 3 Extract .exe from zip and keep in a folder and add its path to environment variables

# 4 Verify your install
jx version 

# 5 Installing the operator
1 -- Run jx admin operator command inside the git clone of the git repository you created previously:
jx admin operator --url=https://github.com/myorg/env-mycluster-dev.git --username <mygituser> --token <mygittoken>

2 -- If you are not inside the git clone of the git repository you will need to specify the --url parameter for the git URL:
jx admin operator --url=https://github.com/myorg/env-mycluster-dev.git --username <mygituser> --token <mygittoken>