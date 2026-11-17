---
title: Deployment
status: published
---

# Deployment

Deployments follow a fixed rhythm so that every change is attributable.

1. Open a change record against the service being touched.
2. Build the candidate artefact and record its digest.
3. Deploy to staging first and leave it running for one full shift.
4. Promote to production in the quiet window agreed with the account lead.

Rollbacks reverse the same steps and never bypass the change record.
