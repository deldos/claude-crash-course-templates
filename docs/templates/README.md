# Cortex-Native Template Blueprint
 
## Overview
 This folder contains adapted versions of the original three step templates to align with Project Cortex SOP and Cloudflare-native tech stacks.
 Structured to support:
 - MVP-first ideation and planning
 - Scaffolding
 - Implementation 
  
## Stages
 1. Make a Master Plan (Mapped to Codex)
 2. Stub out project structure in cursor IDE
 3. Fully code implementation for staging/production

## Variants from original
- Replaced all Claude-specific language with Cloudflare Workers AI guidance
- Added instructions for Using JWS Cloudflare key products (KV, D1,Durable Objects, Q2, R2) 
- Added sections in templates for ENV mapping (Codex / Cursor IDE / Cloudflare deploy)

## Directory Structure

layout:
- deployment_plan/master_plan.md
- deployment_plan/stub_out.md
- deployment_plan/implementation.md
- outputs/
- docs/templates/ 
    - 1master_plan.md
    - 2_stub_out.md
    - 3_implementation.md
