Here we are using one Hub cluster with which we will deploy applications to multiple spoke or node clusters. We are using Github as the single source of truth. Thus no one will be able to manually change any configurations within the cluster or they will be rolled back by the ArgoCD as per the GIT configurations.

Makes sure the below components are installed for this lab:

kubectl – A command line tool for working with Kubernetes clusters. For more information, see Installing or updating kubectl. https://docs.aws.amazon.com/eks/latest/userguide/install-kubectl.html

eksctl – A command line tool for working with EKS clusters that automates many individual tasks. For more information, see Installing or updating. https://docs.aws.amazon.com/eks/latest/userguide/eksctl.html

AWS CLI – A command line tool for working with AWS services, including Amazon EKS. For more information, see Installing, updating, and uninstalling the AWS CLI https://docs.aws.amazon.com/cli/latest/userguide/cli-chap-install.html in the AWS Command Line Interface User Guide.

After installing the AWS CLI, I recommend that you also configure it. For more information, see Quick configuration with aws configure in the AWS Command Line Interface User Guide. https://docs.aws.amazon.com/cli/latest/userguide/cli-configure-quickstart.html#cli-configure-quickstart-config

Argo CD CLI(Not the actual Argo CD Installation) - https://argo-cd.readthedocs.io/en/stable/cli_installation/#installation

