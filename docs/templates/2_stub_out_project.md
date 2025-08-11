# Step 2: Stub Out Project - Cortex-Native Version

TAGS: project, cortex

This template is used in the Cursor IDE environment to create a project scaffold using Cloudflare native tools.

## Goal
- Create a basic repo scaffold for the project based on the approved master plan
- Include file structure and necessary configuration files
- Use Cloudflare Workers products for initial setup (KV, D1, Queues, Durable Objects)
- Ensure MIP files are ready for implementation step

## Sections:
1. Review Master Plan
from "Reference: deployment_plan/master_plan.md"
Ensure that all core functionality and storage planning is accounted for in this stage.

- Generate basic file and folder structure for:
  - 'app/'
  - 'src/'
  - 'config/'
  - 'docs/'
  - 'tests/'
- Generate 'index.js' or 'worker.js' with a basic Workers server endpoint
- Add sample configs for KV, D1, Queues, Durable Objects as per master plan
- Create a basic readme.md in docs/sos to describe project scope and ENV mapping

3. Commit Initial Stub Artifact
Ensure all generated files are added to git and committed to a branch for easy rollback
