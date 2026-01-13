# Model Security CI/CD Pipeline demo

This repo contains a simple demo of Prisma AIRS model security being applied to a sample model deployment lifecycle to implement MLSecOps.

## How to use

Go to "Actions" in this repo, and trigger the workflow using a valid Security Group UUID & Model URI. The repo is configured with credentials for the TSG ID `1645884875`, so all security groups should live in that TSG and all scans will be sent to that TSG.
