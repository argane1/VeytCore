# Changelog

All notable changes to this project are documented in this file.
---

## [1.0.0] – 2026-06-26

### 🚀 Release Highlights
* **Full-Stack Infrastructure:** Completed the transition to a robust, self-hosted Dockerized environment.
* **Service Orchestration:** Integrated PostgreSQL, MinIO, and Inngest into a unified, containerized deployment pipeline.
* **Developer Experience:** Streamlined build processes with automated entrypoint scripts and environment-agnostic configurations.

### 🛠️ Added
* **Docker Ecosystem:** Implemented multi-stage `Dockerfile` and comprehensive `docker-compose.yml` for simplified orchestration.
* **Storage:** Configured MinIO for persistent object storage and secure document management.
* **Automation:** Integrated Inngest worker services for reliable background job processing and event handling.
* **Environment Management:** Centralized configuration via `.env` management to decouple secrets from source code.

### ⚙️ Changed / Optimized
* **Build Pipeline:** Optimized dependency resolution and lifecycle management, reducing installation overhead.
* **Stability:** Enhanced service health checks and dependency wait-conditions for robust startup sequences.
* **Documentation:** Refactored project history for clarity and simplified maintenance.

### 🔧 Fixed
* **Dependency Management:** Resolved `pnpm` lockfile configuration mismatches during the build phase.
* **Orchestration:** Fixed container lifecycle dependency errors in the Inngest background worker service.
* **Security:** Scrubbed legacy configurations to ensure environment-driven security standards.

---

## [0.0.0] – 2026-06-25
* Initial project architecture and foundation established.