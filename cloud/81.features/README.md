|            |                      | AWS                            | Azure               | GCP             |
| ---------- | -------------------- | ------------------------------ | ------------------- | --------------- |
| Infra      | Physical             | Region                         |                     | Region          |
| Infra      | Physical             | Availability Zone              | AZ, ASet            | Zone            |
| Infra      | Logical              | VPC                            | VNet                | VPC             |
| Id & AM    |                      | Role                           |                     | Service Account |
| IAM        |                      | IAM                            | Entra ID            | IAM             |
| IAM        |                      | Policy/Role                    | RBAC                | Role            |
| IAM        |                      | Organization                   | Entra ID            | Organization    |
| IAM        | AD Integration       | Directory Service AD Connector | AD Connect          |                 |
| Storage    | Object Storage       | S3                             | Block storage       | Cloud Storage   |
| Storage    | Block Storage        | EBS                            | managed disk        |                 |
| Storage    | File Storage         | EFS/FSx                        | Files               |                 |
| Management | Resource Managmenet  | Tag                            | Resource Group      | Project         |
| Network    | VPN                  | VPN Gateway                    | VPN Gateway         | HA VPN          |
| Network    | Leased line          | Direct Connect                 | ExpressRoute        |                 |
| Network    | Load Balancing       | NLB                            | Load Balancer       | Network LB      |
| Network    | Load Balancing       | ALB                            | App Gateway         | HTTP LB         |
| Network    | Global Scaleout      | Global Accelerator             | Front Door          |                 |
| Network    | DNS                  | Route53                        | Traffic Manager     | Cloud DNS       |
| Network    | Firewall             | WAF                            | WAF                 |                 |
| Compute    | Auto Scaling         | Auto Scaling Group             | VM Scale Sets       |                 |
| Compute    | Container            | EKS                            | AKS                 | GKE             |
| Compute    | Container Serverless | Fargate                        | Container Instances | GKE Autopilot   |
