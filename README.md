# NextCRM

A unified, self-hosted Customer Relationship Management (CRM) platform designed for distributed teams.

## 🚀 Overview
NextCRM provides a centralized hub for managing leads, invoicing, and marketing campaigns. Built with a local-first philosophy, this platform empowers teams to manage customer data with high performance, security, and granular access control.



## 🏗️ Architecture
NextCRM utilizes a containerized, robust infrastructure:
* **Frontend/Backend:** Next.js (App Router, Server Actions)
* **Database:** PostgreSQL (with Prisma ORM)
* **Storage:** MinIO (S3-compatible object storage for documents and invoices)
* **Background Jobs:** Inngest (Reliable event-driven workflows)
* **Orchestration:** Docker Compose

## 🚀 Getting Started

### Prerequisites
* [Docker](https://www.docker.com/) and [Docker Compose](https://docs.docker.com/compose/)
* [pnpm](https://pnpm.io/)

### Local Deployment
1. **Clone the repository:**
   ```bash
   git clone [YOUR_REPO_URL]
   cd nextcrm-app