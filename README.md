# HIPAA-Aligned-Hub-and-Spoke-Network-on-Azure
A hub and spoke network built entirely in Terraform. A central hub provides shared security services (Azure Firewall, Bastion, Key Vault, centralized logging). Two isolated spokes host clinical (ePHI) and analytics (de-identified) workloads, with all egress and cross-spoke traffic forced through the firewall.
