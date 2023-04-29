# Akamai_Hackathon
Akamai Hackathon explores Terraform with Linode for automated deploy to Akamai using infrastructure-as-code (IaC).

Follow the guide to use Terraform with Linode:
https://blog.kr4ntz.com/linode/2023/03/24/Terraform-Linode-LKE.html
No need to create a firewall as said in the blog.

It would be great to install the following software on your laptop:

· Terraform - https://developer.hashicorp.com/terraform/tutorials/aws-get-started/install-cli
· Akamai provider for Terraform - https://github.com/akamai/terraform-provider-akamai
· Linode provide for Terraform - https://www.linode.com/docs/guides/how-to-build-your-infrastructure-using-terraform-and-linode/#building-with-the-linode-provider
· Akamai CLI - https://github.com/akamai/cli
· Akamai Terraform CLI - https://github.com/akamai/cli-terraform
· Powershell - https://github.com/PowerShell/PowerShell
· Akamai Powershell plugin - https://github.com/akamai/akamaipowershell

You have to customize the code where prompts are provided to successfuly implement the following:
-Have an Akamai Account.
-Provision a Linode origin (target: Kubernetes) with a typical OWASP weak origin and simulate an attack (SQLi, XSS, etc.)
-Provision a delivery CDN config through Terraform, push it to prod
-Provision a security configuration through Terraform, push it to prod and realise the security vulnerability is gone

