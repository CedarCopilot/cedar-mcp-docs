# Refresh Cedar MCP documentation

Original request: find and refresh the stale Cedar MCP documentation at https://docs.cedarcopilot.com.

Scope: source-reviewed updates to external agent initialization/KPIs, pilot Task Views, canonical task lifecycle, research, Slack, LinkedIn profile-visit and CRM handoff contracts, and app-only website/durable research boundaries. Preserve the Mintlify information architecture. No backend, database, account or deployment changes.

Source: CedarCopilot/cedar-mail production branch revision `881368f41aca7568c804b4bb44090d050d2d31aa`, compared with staging `e1e9640486e0bff72f845f56bb33e6ca65ca2a52`. Source availability is distinct from verification of an authenticated deployed tool session. Retained schema branches remain explicitly labeled snapshots, not a newly generated exhaustive export.

Acceptance: correct operation names and parameter keys; explicit scopes and feature/app boundaries; no claim that initialization activates an agent or that a handoff performs delivery; synchronized changed downloadable/catalog schemas; valid MDX/JSON, navigation and links.

Verification: compile the changed MDX files; parse changed JSON; resolve navigation and local links; compare refreshed task/agent schemas with catalog entries; inspect source-based action inventory. Read-only live checks verified the production MCP 401 challenge and S256 OAuth metadata on November 11, 2026. Authenticated tool execution and Mintlify deployment are untested. No runtime telemetry changes are needed for documentation-only edits. Full application test suites are deferred to GitHub CI.

Delivery: unmerged docs PR against `main`, explicitly approved by Isabelle for this repository because it has no staging branch. Existing Cedar board card: https://mail.cedarcopilot.com/brain/knowledge?documentId=7dd4f070-9d6f-43d8-b4a6-2e96bd94b22f. The shared handoff helper hardcodes staging; record its result rather than bypassing it. Hosted checks remain unapproved until the post-merge choice.
