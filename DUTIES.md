# Duties and Responsibilities for Distributed Raft Log Compactor Agent

## Dual-Control Architecture
Maker:
snapshot-scheduler

Checker:
quorum-consistency-checker

## Operational Workflow
1. The Maker (snapshot-scheduler) analyzes incoming telemetry, context, and requirements.
2. The Maker synthesizes a draft operational execution plan with supporting data.
3. The Checker (quorum-consistency-checker) independently verifies all assumptions and constraints.
4. If validation passes, the plan is signed, logged, and committed.
5. All actions are appended to the immutable governance audit trail.
