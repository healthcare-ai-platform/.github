# .github

# Healthcare AI Platform

B2B SaaS platform for healthcare document processing, 
extraction, and analytics.

## Repositories

| Repo | Purpose |
|------|---------|
| [backend](link) | FastAPI — uploads, auth, event publishing |
| [pipeline](link) | Airflow + dbt — extraction, transformation |
| [frontend](link) | React dashboard — analytics, monitoring |
| [infra](link) | Terraform + docker-compose — AWS + local dev |

## Architecture
(one line diagram or image here)

## Local Development

### 1. Clone all repos
mkdir healthcare-platform && cd healthcare-platform

git clone git@github.com:healthcare-ai-platform/backend.git
git clone git@github.com:healthcare-ai-platform/pipeline.git
git clone git@github.com:healthcare-ai-platform/frontend.git
git clone git@github.com:healthcare-ai-platform/infra.git

### 2. Start local infrastructure
cd infra && docker-compose up -d

### 3. Pull all updates
bash infra/pull-all.sh
