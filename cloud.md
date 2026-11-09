# Cloud Computing certification roadmap

AWS, Azure and Google Cloud paths, plus the tools most cloud teams use.

```mermaid
flowchart LR
  subgraph L0["Entry"]
    clo00["AWS Cloud Practitioner"]
    clo01["AZ-900"]
  end
  subgraph L1["Practitioner"]
    clo10["AWS SAA"]
    clo11["AZ-104"]
    clo12["GCP ACE"]
    clo13["Terraform Associate"]
  end
  subgraph L2["Leader"]
    clo20["AWS SA Professional"]
    clo21["AZ-305"]
  end
  L0 --> L1
  L1 --> L2
```

| Certification | Issuer | Level | Good for | Free readiness check |
| --- | --- | --- | --- | --- |
| AWS Certified Cloud Practitioner | AWS | Entry | Cloud basics for any role | [Check readiness](https://edureify.com/certification/cloud-computing/aws-cloud-practitioner/readiness-test?utm_source=github&utm_medium=repo&utm_campaign=gh_roadmaps_cloud) |
| Azure Fundamentals (AZ-900) | Microsoft | Entry | Cloud basics on Azure | [Check readiness](https://edureify.com/certification/cloud-computing/azure-fundamentals-az-900/readiness-test?utm_source=github&utm_medium=repo&utm_campaign=gh_roadmaps_cloud) |
| AWS Solutions Architect Associate | AWS | Practitioner | Designing systems on AWS | [Check readiness](https://edureify.com/certification/cloud-computing/aws-solution-architect/readiness-test?utm_source=github&utm_medium=repo&utm_campaign=gh_roadmaps_cloud) |
| Azure Administrator (AZ-104) | Microsoft | Practitioner | Running Azure environments | [Check readiness](https://edureify.com/certification/cloud-computing/azure-admin-az-104/readiness-test?utm_source=github&utm_medium=repo&utm_campaign=gh_roadmaps_cloud) |
| Google Associate Cloud Engineer | Google Cloud | Practitioner | Deploying and operating on GCP | [Check readiness](https://edureify.com/certification/cloud-computing/gcp-associate-cloud-engineer/readiness-test?utm_source=github&utm_medium=repo&utm_campaign=gh_roadmaps_cloud) |
| HashiCorp Terraform Associate | HashiCorp | Practitioner | Infrastructure as code | [Check readiness](https://edureify.com/certification/cloud-computing/terraform-associate/readiness-test?utm_source=github&utm_medium=repo&utm_campaign=gh_roadmaps_cloud) |
| AWS Solutions Architect Professional (SAP-C02 until Nov 16, 2026; then SAP-C03) | AWS | Leader | Complex, multi-account AWS architecture | [Check readiness](https://edureify.com/certification/cloud-computing/aws-solutions-architect-professional/readiness-test?utm_source=github&utm_medium=repo&utm_campaign=gh_roadmaps_cloud) |
| Azure Solutions Architect (AZ-305) | Microsoft | Leader | Azure architecture design | [Check readiness](https://edureify.com/certification/cloud-computing/azure-solutions-architect-az-305/readiness-test?utm_source=github&utm_medium=repo&utm_campaign=gh_roadmaps_cloud) |

## How to choose

- Pick the cloud your current or target employer uses. Skills transfer, exam details don't.
- Associate-level certs are where most job posts start asking.
- AWS is updating the Solutions Architect Professional exam: the last day to take SAP-C02 is November 16, 2026, and SAP-C03 replaces it. Most older study guides target SAP-C02, so read AWS's SAP-C02 vs SAP-C03 comparison before you pick materials or a date.
- Pair any cloud cert with Terraform or Kubernetes skills; that's what interviews test.

## Official sources

Always confirm exam details, fees and eligibility with the issuer:

- [AWS](https://aws.amazon.com/certification/)
- [AWS SAP-C02 vs SAP-C03 comparison](https://docs.aws.amazon.com/aws-certification/latest/solutions-architect-professional-03/sap-03-comparison.html)
- [Microsoft](https://learn.microsoft.com/credentials/)
- [Google Cloud](https://cloud.google.com/learn/certification)
- [HashiCorp](https://developer.hashicorp.com/certifications)

---
[Back to all roadmaps](../README.md)
