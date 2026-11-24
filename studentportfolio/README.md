# Yarrow-Mullein Bank Application

**Sania Parvej**  
Application Design and Delivery, RRC Polytech  
COMP-4001 — Module 6, Part 3

This project runs a banking application with a student portfolio frontend. NGINX routes requests to the application services, and MongoDB stores account and transaction data. The banking app supports registration, login, deposits, withdrawals, and monthly transaction reports.

In Part 3, I’m setting up GitHub Actions to build and publish container images and update the Kubernetes manifests in a separate GitOps repository. Argo CD will watch that repository and deploy updates to Minikube.

GitHub: [rrc-w2025-sparvej](https://github.com/rrc-w2025-sparvej)