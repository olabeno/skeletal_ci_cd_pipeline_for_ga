# skeletal_ci_cd_pipeline_for_ga
This ci-cd pipeline was written for github actions workflow to deploy kubernetes containers in the k8s cluster after dockerizaion using Dockerfile build process and testing.
use the following steps to gain access to eks in aws for Kubeconfig
Explanation of Steps
OIDC Authentication → Uses GitHub’s OIDC to assume the AWS role.
Configure AWS Credentials → Uses aws-actions/configure-aws-credentials to authenticate.
Update Kubeconfig → Configures kubectl access.
Verify Access → Runs kubectl get nodes to ensure authentication works.
Deploy Application → Applies Kubernetes manifests.

You can explore other kubeconfig options depending on the k8s cluster you intend to access with the kubectl command in the github actions workflow.
Explore options using chatGPTbas per your requirements
