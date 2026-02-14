# AWS Multi-Region Disaster Recovery Architecture

## Overview
The architecture leverages multi-region high availability, automated DNS failover, cross-region data replication, and infrastructure-as-code automation to minimize downtime and data loss during regional failures.

## Key Capabilities
- Multi-region high availability
- Automated disaster recovery
- Infrastructure-as-code using CloudFormation
- RTO ≤ 10 minutes, RPO ≤ 1 minute

## Architecture Highlights
- EC2 + Auto Scaling
- RDS Cross-Region Replication
- S3 Cross-Region Replication
- Route 53 DNS Failover
- Fully automated CloudFormation deployment
