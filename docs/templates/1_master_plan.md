# Step 1: Master Plan - Cortex-Native Version

Tags: project, cortex

This template is used in the Codex environment to generate a complete master plan for a pnew Project Cortex application.

## Goal
- Provide a structured overview of the problem to solve
- Include how the solution will be implemented using Cloudflare Workers products (KV, D1, R2, Durable Objects, Queues)
- Ensure MDP-first approach, allowing for future iteration
- Define possible cross-project integrations if relevant

## Sections:
1. Project Name
2. Problem Statement
3. Proposed Solution
4. Functional Requirements
5. Non-functional Requirements (eg. security, compliance)
6. System Architecture overview
7. Data Storage Plan
  - Use Cloudflare KV or D1 as appropriate
  (e.g. app key-v-alue cache in KV)
8. Architecture Plan
  - Workers runtime with routes, bindings, and product components
  (e.g. app entry points, api endpoints, webhook routes)
9. Tech Stack  
  - Workers AI model or other language processing with integration points
technical details.

## Notes 
- Adapt all Claude-specific steps to Cloudflare Workers AI constructs
- Ensure the plan can be executed in the Codex environment
