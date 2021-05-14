# jenkins-on-k8s
Subdirectories that contain testing for the orchestration of a Jenkins Kuberenetes cluster.
helm-installation contains YAMLs to accompany the Helm packages installed, this being the Jenkins Operator for K8s.
yaml-installation contains the YAMLs needed to create a Jenkins worker pod in the 'jenkins' namespace.
nginx-pod contains the YAML files needed for a quick K8s setup of an nginx pod accesible from the internet.
