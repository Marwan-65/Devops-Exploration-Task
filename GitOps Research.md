The  word  GitOps,  which  was  first  used  by  Alexis Richardson, refers  to a paradigm shift  in IT operations, specifically  in  the  field  of  DevOps.  It's  a  model  where operational  workflows  are  based  on  the  distributed version  control  system  Git.  The  need  for  a  more effective,  dependable,  and  secure  framework  for managing  intricate  modern  infrastructures  and applications led to the creation of GitOps. <sup>[1]</sup>

# Practices

here are some of the most important practices that are used in GitOps.

- **Git for Everything:**
GitOps extends the practice of using Git for the source code of an application to the application’s configuration, infrastructure, and operational procedures. It stores every aspect of a project’s infrastructure, including infrastructure as code files, configuration files, and application code files, in Git repositories, making it easy to manage software deployment and infrastructure provisioning. 

- **V for Versioning:**
Declarative descriptions stored within the repository supports immutability, versioning, and versioning history. For example, using Git for the declarations mentioned above, allows you a single place from which everything for your application is derived and driven. This allows you to easily pinpoint any changes made at any time. Don’t try to understand what is different between two environments by hand. Just look at all changes found in version control history, having the guarantee that the platform always matches what is described there.

- **Auto-Pull:**
Using GitOps means that you employ software agents that are always running in the cluster, automatically pulling Git state at regular intervals and checking it against the live cluster state. This way you always know if the version in Git is the same as the live state or not. <sup>[2]</sup>

- **Immutable Infrastructure:** GitOps encourages the practice of immutable infrastructure, where changes are made not by modifying the existing infrastructure but by replacing it  with  a  new  one  defined  in  the  Git  repository.  This reduces  inconsistencies  and  potential  drifts  in  the environment.

- **Pull Requests and Code Reviews:** These  practices  are  borrowed from  the  software  development  lifecycle  and  applied  to infrastructure management. Pull requests are used to suggest modifications  to  applications  or  infrastructure configurations.  This  enables  discussion and  review  of  the changes made by  team members  before their merging into the  main  branch.  Code  reviews  in  the context of GitOps extend beyond reviewing  code for bugs. They  encompass reviewing  configuration  changes for  best practices,  compliance  with  policies,  and  potential  security implications. <sup>[3]</sup>





# Benefits
- **Enhanced  Operational  Efficiency:** since the differences between the production and development environments are eliminated because Git becomes the only source for the infrastructure and application configurations, hence the time spent debugging and solving merging issues decreases. Also, since GitOps is based on automation, the deployment process is less manual and has less human error.

- **Improved  Security and  Compliance:** as the whole framework is build on Git, every modification is auditable,  traceable, and reversible. Every change is reviewed before merging and deployment, this guarantees that the changes are following the standards agreed upon.<sup>[4]</sup>

- **Improved stability:**
In a GitOps workflow, audit logs are automatically created for reviewing and monitoring all changes. With details such as who commits the changes and the results of those changes recorded every step of the way, you can ensure greater stability of the system.

- **Increased reliability:**
With Git's revert/rollback capabilities, rolling back to the last known good configuration when you experience problems is straightforward. Since your entire system is defined in Git, you can quickly recover during an incident by rolling back. <sup>[5]</sup> 

# Tools

- **Argo CD**
Argo CD is a tool for Kubernetes that operates on the principles of GitOps continuous delivery. It streamlines the process of deploying apps on numerous Kubernetes clusters from a Git repository. By doing this, it guarantees that your live apps align with the planned state stored in Git.
Argo CD also has the capability to visually manage multi-cluster deployments. Thus, it provides an intuitive user interface and extensive command-line interface for operations teams. It's compatible with various configuration management tools and easily integrates with current workflows, which is why it's a popular option for applications based on Kubernetes.

- **Terraform**
Terraform is a software tool for IaC that allows infrastructure to be defined and provisioned using code. It can handle cloud and on-premises resources using a declarative configuration language. In the realm of GitOps, Terraform enables the automation of infrastructure provisioning by using code from your version control. This ensures uniformity and reproducibility throughout different environments. Terraform is a fundamental component of numerous GitOps pipelines due to its network of service providers. It enables the management of a diverse range of services.<sup>[6]</sup>

- **Flux:** Flux is a group of flexible and progressive delivery tools for open and extensible Kubernetes projects. It empowers teams to use GitOps to manage the deployment of applications and the infrastructure. It provides a simple interface for setting up a GitOps workflow.

- **Jenkins X:** it is a comprehensive and powerful open-source cloud-native solution that automates the CI/CD and testing workflows for applications on Kubernetes. The solution uses DevOps best practices automation and tooling to improve speed and workflows. <sup>[7]</sup>

- **CodeFresh:** it is an independent Continuous Delivery tool powered by Argo. The wraparound solution CodeFresh created serves to manage new and existing Argo instances for increased visibility and security. It offers users a way to use ArgoCD with enhanced enterprise-grade controls and visibility. CodeFresh offers security, centralized management, and audit trails for compliance.<sup>[8]</sup> 


# References
[2] [Team, C. O. (2024, July 17). GitOps. Codefresh.]( https://codefresh.io/learn/gitops/)

[1] [3] [4] [Chittibala, D. R. (2024). GITOps: Revolutionizing configuration management in DevOps. ResearchGate.](https://doi.org/10.21275/SR24203190625)

[5] [Kuruvilla, J. (2022, December 19). Top 10 benefits of GitOps. Benefits of GitOps.](https://www.adaptavist.com/blog/top-10-benefits-of-gitops)

[6] [6 GITOPs Tools You should know about in 2024. (n.d.).](https://www.devzero.io/blog/gitops-tools)

[7] [Kingatua, A. (2023, August 14). 17 Promising GItOPs tools to explore. Geekflare. ](https://geekflare.com/gitops-tools/)

[8] [Lamm, D. (2024, June 17). GitOps Tools & Kubernetes Gitops Tools. Harness.io.](https://www.harness.io/blog/gitops-tools)
