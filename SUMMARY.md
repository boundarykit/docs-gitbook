# Table of contents

* [BoundaryKit](README.md)

## Documentation

* Overview
  * [BoundaryKit overview](index.md)
  * [Make your first decision](quickstart.md)
  * [Runtime architecture](architecture.md)
  * [Decision vocabulary](glossary.md)
  * [Release changes](changelog.md)

* documentation
  * [Core concepts](documentation/core-concepts.md)
  * [Authenticate requests](documentation/authenticate-requests.md)
  * [Design boundaries](documentation/design-boundaries.md)
  * [Compose policies](documentation/compose-policies.md)
  * [Isolate sandboxes](documentation/isolate-sandboxes.md)
  * [Rate limits](documentation/rate-limits.md)
  * [Migrate from v1 to v2](documentation/migrate-from-v1-to-v2.md)
  * [Security model](documentation/security-model.md)
  * [Session lifecycle](documentation/session-lifecycle.md)
  * [Token scopes](documentation/token-scopes.md)

* test
  * [Policy fixtures](test/policy-fixtures.md)
  * [Golden decisions](test/golden-decisions.md)
  * [Replay sessions](test/replay-sessions.md)
  * [Negative cases](test/negative-cases.md)
  * [Nested rule tests](test/nested-rule-tests.md)
  * [Sandbox isolation tests](test/sandbox-isolation-tests.md)
  * [Token expiry tests](test/token-expiry-tests.md)
  * [Tenant separation tests](test/tenant-separation-tests.md)
  * [Baseline comparisons](test/baseline-comparisons.md)
  * [Latency budgets](test/latency-budgets.md)
  * [Evaluation reports](test/evaluation-reports.md)
  * [Release acceptance](test/release-acceptance.md)

* cookbook
  * [Limit tool access](cookbook/limit-tool-access.md)
  * [Scope a support bot](cookbook/scope-a-support-bot.md)
  * [Isolate a preview agent](cookbook/isolate-a-preview-agent.md)
  * [Rotate an API key](cookbook/rotate-an-api-key.md)
  * [Export audit evidence](cookbook/export-audit-evidence.md)
  * [Replay a denied call](cookbook/replay-a-denied-call.md)
  * [Detect a noisy agent](cookbook/detect-a-noisy-agent.md)
  * [Review policy drift](cookbook/review-policy-drift.md)
  * [Expire a session](cookbook/expire-a-session.md)
  * [Route an alert](cookbook/route-an-alert.md)
  * [Test nested rules](cookbook/test-nested-rules.md)
  * [Trace a webhook](cookbook/trace-a-webhook.md)
  * [Inspect usage spikes](cookbook/inspect-usage-spikes.md)
  * [Stage a policy rollout](cookbook/stage-a-policy-rollout.md)

* integrations
  * [OpenAI](integrations/openai.md)
  * [Anthropic](integrations/anthropic.md)
  * [LangChain](integrations/langchain.md)
  * [CrewAI](integrations/crewai.md)
  * [Cloudflare Workers](integrations/cloudflare-workers.md)
  * [AWS Lambda](integrations/aws-lambda.md)
  * [Datadog](integrations/datadog.md)
  * [PagerDuty](integrations/pagerduty.md)
  * [Slack](integrations/slack.md)
  * [Okta](integrations/okta.md)
  * [GitHub Actions](integrations/github-actions.md)
  * [Terraform](integrations/terraform.md)

* administration
  * [Workspace provisioning](administration/workspace-provisioning.md)
  * [RBAC](administration/rbac.md)
  * [SSO and SAML](administration/sso-and-saml.md)
  * [Audit exports](administration/audit-exports.md)
  * [Workspace isolation](administration/workspace-isolation.md)
  * [Retention](administration/retention.md)
  * [Billing](administration/billing.md)
  * [Service accounts](administration/service-accounts.md)
  * [Membership reviews](administration/membership-reviews.md)
  * [Organization settings](administration/organization-settings.md)

* monitor
  * [Live telemetry](monitor/live-telemetry.md)
  * [Anomaly alerts](monitor/anomaly-alerts.md)
  * [Decision SLOs](monitor/decision-slos.md)
  * [Request traces](monitor/request-traces.md)
  * [Delivery latency](monitor/delivery-latency.md)
  * [Error budgets](monitor/error-budgets.md)
  * [Triage dashboards](monitor/triage-dashboards.md)
  * [Usage reports](monitor/usage-reports.md)

* Start here
  * [Documentation overview](start/documentation.md)

## API

* Start here
  * [API overview](start/api.md)

* v1 boundaries
  * [List boundaries](api/get_v1_boundaries.md)
  * [Create boundary](api/post_v1_boundaries.md)
  * [Get boundary](api/get_v1_boundaries_id.md)
  * [Update boundary](api/patch_v1_boundaries_id.md)
  * [Delete boundary](api/delete_v1_boundaries_id.md)
  * [Search boundaries](api/get_v1_boundaries_search.md)
  * [Read revision history](api/get_v1_boundaries_id_history.md)

* v1 policies
  * [List policies](api/get_v1_policies.md)
  * [Create policy](api/post_v1_policies.md)
  * [Get policy](api/get_v1_policies_id.md)
  * [Update policy](api/patch_v1_policies_id.md)
  * [Delete policy](api/delete_v1_policies_id.md)
  * [Search policies](api/get_v1_policies_search.md)
  * [Read revision history](api/get_v1_policies_id_history.md)

* v1 agents
  * [List agents](api/get_v1_agents.md)
  * [Create agent](api/post_v1_agents.md)
  * [Get agent](api/get_v1_agents_id.md)
  * [Update agent](api/patch_v1_agents_id.md)
  * [Delete agent](api/delete_v1_agents_id.md)
  * [Search agents](api/get_v1_agents_search.md)
  * [Read revision history](api/get_v1_agents_id_history.md)

* v1 sandboxes
  * [List sandboxes](api/get_v1_sandboxes.md)
  * [Create sandbox](api/post_v1_sandboxes.md)
  * [Get sandbox](api/get_v1_sandboxes_id.md)
  * [Update sandbox](api/patch_v1_sandboxes_id.md)
  * [Delete sandbox](api/delete_v1_sandboxes_id.md)
  * [Search sandboxes](api/get_v1_sandboxes_search.md)
  * [Read revision history](api/get_v1_sandboxes_id_history.md)

* v1 tokens
  * [List tokens](api/get_v1_tokens.md)
  * [Create token](api/post_v1_tokens.md)
  * [Get token](api/get_v1_tokens_id.md)
  * [Update token](api/patch_v1_tokens_id.md)
  * [Delete token](api/delete_v1_tokens_id.md)
  * [Search tokens](api/get_v1_tokens_search.md)
  * [Read revision history](api/get_v1_tokens_id_history.md)

* v1 sessions
  * [List sessions](api/get_v1_sessions.md)
  * [Create session](api/post_v1_sessions.md)
  * [Get session](api/get_v1_sessions_id.md)
  * [Update session](api/patch_v1_sessions_id.md)
  * [Delete session](api/delete_v1_sessions_id.md)
  * [Search sessions](api/get_v1_sessions_search.md)
  * [Read revision history](api/get_v1_sessions_id_history.md)

* v1 evaluations
  * [List evaluations](api/get_v1_evaluations.md)
  * [Create evaluation](api/post_v1_evaluations.md)
  * [Get evaluation](api/get_v1_evaluations_id.md)
  * [Update evaluation](api/patch_v1_evaluations_id.md)
  * [Delete evaluation](api/delete_v1_evaluations_id.md)
  * [Search evaluations](api/get_v1_evaluations_search.md)
  * [Read revision history](api/get_v1_evaluations_id_history.md)

* v1 audits
  * [List audits](api/get_v1_audits.md)
  * [Create audit](api/post_v1_audits.md)
  * [Get audit](api/get_v1_audits_id.md)
  * [Update audit](api/patch_v1_audits_id.md)
  * [Delete audit](api/delete_v1_audits_id.md)
  * [Search audits](api/get_v1_audits_search.md)
  * [Read revision history](api/get_v1_audits_id_history.md)

* v1 alerts
  * [List alerts](api/get_v1_alerts.md)
  * [Create alert](api/post_v1_alerts.md)
  * [Get alert](api/get_v1_alerts_id.md)
  * [Update alert](api/patch_v1_alerts_id.md)
  * [Delete alert](api/delete_v1_alerts_id.md)
  * [Search alerts](api/get_v1_alerts_search.md)
  * [Read revision history](api/get_v1_alerts_id_history.md)

* v1 monitors
  * [List monitors](api/get_v1_monitors.md)
  * [Create monitor](api/post_v1_monitors.md)
  * [Get monitor](api/get_v1_monitors_id.md)
  * [Update monitor](api/patch_v1_monitors_id.md)
  * [Delete monitor](api/delete_v1_monitors_id.md)
  * [Search monitors](api/get_v1_monitors_search.md)
  * [Read revision history](api/get_v1_monitors_id_history.md)

* v1 webhooks
  * [List webhooks](api/get_v1_webhooks.md)
  * [Create webhook](api/post_v1_webhooks.md)
  * [Get webhook](api/get_v1_webhooks_id.md)
  * [Update webhook](api/patch_v1_webhooks_id.md)
  * [Delete webhook](api/delete_v1_webhooks_id.md)
  * [Search webhooks](api/get_v1_webhooks_search.md)
  * [Read revision history](api/get_v1_webhooks_id_history.md)

* v1 integrations
  * [List integrations](api/get_v1_integrations.md)
  * [Create integration](api/post_v1_integrations.md)
  * [Get integration](api/get_v1_integrations_id.md)
  * [Update integration](api/patch_v1_integrations_id.md)
  * [Delete integration](api/delete_v1_integrations_id.md)
  * [Search integrations](api/get_v1_integrations_search.md)
  * [Read revision history](api/get_v1_integrations_id_history.md)

* v1 organizations
  * [List organizations](api/get_v1_organizations.md)
  * [Create organization](api/post_v1_organizations.md)
  * [Get organization](api/get_v1_organizations_id.md)
  * [Update organization](api/patch_v1_organizations_id.md)
  * [Delete organization](api/delete_v1_organizations_id.md)
  * [Search organizations](api/get_v1_organizations_search.md)
  * [Read revision history](api/get_v1_organizations_id_history.md)

* v1 usage
  * [List usage](api/get_v1_usage.md)
  * [Create usage-record](api/post_v1_usage.md)
  * [Get usage-record](api/get_v1_usage_id.md)
  * [Update usage-record](api/patch_v1_usage_id.md)
  * [Delete usage-record](api/delete_v1_usage_id.md)
  * [Search usage](api/get_v1_usage_search.md)
  * [Read revision history](api/get_v1_usage_id_history.md)

* v2 boundaries
  * [List boundaries](api/get_v2_boundaries.md)
  * [Create boundary](api/post_v2_boundaries.md)
  * [Get boundary](api/get_v2_boundaries_id.md)
  * [Update boundary](api/patch_v2_boundaries_id.md)
  * [Delete boundary](api/delete_v2_boundaries_id.md)
  * [Search boundaries](api/get_v2_boundaries_search.md)
  * [Read revision history](api/get_v2_boundaries_id_history.md)

* v2 policies
  * [List policies](api/get_v2_policies.md)
  * [Create policy](api/post_v2_policies.md)
  * [Get policy](api/get_v2_policies_id.md)
  * [Update policy](api/patch_v2_policies_id.md)
  * [Delete policy](api/delete_v2_policies_id.md)
  * [Search policies](api/get_v2_policies_search.md)
  * [Read revision history](api/get_v2_policies_id_history.md)
  * [Import policy bundle](api/post_v2_policies_import.md)

* v2 agents
  * [List agents](api/get_v2_agents.md)
  * [Create agent](api/post_v2_agents.md)
  * [Get agent](api/get_v2_agents_id.md)
  * [Update agent](api/patch_v2_agents_id.md)
  * [Delete agent](api/delete_v2_agents_id.md)
  * [Search agents](api/get_v2_agents_search.md)
  * [Read revision history](api/get_v2_agents_id_history.md)

* v2 sandboxes
  * [List sandboxes](api/get_v2_sandboxes.md)
  * [Create sandbox](api/post_v2_sandboxes.md)
  * [Get sandbox](api/get_v2_sandboxes_id.md)
  * [Update sandbox](api/patch_v2_sandboxes_id.md)
  * [Delete sandbox](api/delete_v2_sandboxes_id.md)
  * [Search sandboxes](api/get_v2_sandboxes_search.md)
  * [Read revision history](api/get_v2_sandboxes_id_history.md)

* v2 tokens
  * [List tokens](api/get_v2_tokens.md)
  * [Create token](api/post_v2_tokens.md)
  * [Get token](api/get_v2_tokens_id.md)
  * [Update token](api/patch_v2_tokens_id.md)
  * [Delete token](api/delete_v2_tokens_id.md)
  * [Search tokens](api/get_v2_tokens_search.md)
  * [Read revision history](api/get_v2_tokens_id_history.md)
  * [Exchange scoped token](api/post_v2_tokens_exchange.md)

* v2 sessions
  * [List sessions](api/get_v2_sessions.md)
  * [Create session](api/post_v2_sessions.md)
  * [Get session](api/get_v2_sessions_id.md)
  * [Update session](api/patch_v2_sessions_id.md)
  * [Delete session](api/delete_v2_sessions_id.md)
  * [Search sessions](api/get_v2_sessions_search.md)
  * [Read revision history](api/get_v2_sessions_id_history.md)

* v2 evaluations
  * [List evaluations](api/get_v2_evaluations.md)
  * [Create evaluation](api/post_v2_evaluations.md)
  * [Get evaluation](api/get_v2_evaluations_id.md)
  * [Update evaluation](api/patch_v2_evaluations_id.md)
  * [Delete evaluation](api/delete_v2_evaluations_id.md)
  * [Search evaluations](api/get_v2_evaluations_search.md)
  * [Read revision history](api/get_v2_evaluations_id_history.md)

* v2 audits
  * [List audits](api/get_v2_audits.md)
  * [Create audit](api/post_v2_audits.md)
  * [Get audit](api/get_v2_audits_id.md)
  * [Update audit](api/patch_v2_audits_id.md)
  * [Delete audit](api/delete_v2_audits_id.md)
  * [Search audits](api/get_v2_audits_search.md)
  * [Read revision history](api/get_v2_audits_id_history.md)

* v2 alerts
  * [List alerts](api/get_v2_alerts.md)
  * [Create alert](api/post_v2_alerts.md)
  * [Get alert](api/get_v2_alerts_id.md)
  * [Update alert](api/patch_v2_alerts_id.md)
  * [Delete alert](api/delete_v2_alerts_id.md)
  * [Search alerts](api/get_v2_alerts_search.md)
  * [Read revision history](api/get_v2_alerts_id_history.md)

* v2 monitors
  * [List monitors](api/get_v2_monitors.md)
  * [Create monitor](api/post_v2_monitors.md)
  * [Get monitor](api/get_v2_monitors_id.md)
  * [Update monitor](api/patch_v2_monitors_id.md)
  * [Delete monitor](api/delete_v2_monitors_id.md)
  * [Search monitors](api/get_v2_monitors_search.md)
  * [Read revision history](api/get_v2_monitors_id_history.md)

* v2 webhooks
  * [List webhooks](api/get_v2_webhooks.md)
  * [Create webhook](api/post_v2_webhooks.md)
  * [Get webhook](api/get_v2_webhooks_id.md)
  * [Update webhook](api/patch_v2_webhooks_id.md)
  * [Delete webhook](api/delete_v2_webhooks_id.md)
  * [Search webhooks](api/get_v2_webhooks_search.md)
  * [Read revision history](api/get_v2_webhooks_id_history.md)

* v2 integrations
  * [List integrations](api/get_v2_integrations.md)
  * [Create integration](api/post_v2_integrations.md)
  * [Get integration](api/get_v2_integrations_id.md)
  * [Update integration](api/patch_v2_integrations_id.md)
  * [Delete integration](api/delete_v2_integrations_id.md)
  * [Search integrations](api/get_v2_integrations_search.md)
  * [Read revision history](api/get_v2_integrations_id_history.md)

* v2 organizations
  * [List organizations](api/get_v2_organizations.md)
  * [Create organization](api/post_v2_organizations.md)
  * [Get organization](api/get_v2_organizations_id.md)
  * [Update organization](api/patch_v2_organizations_id.md)
  * [Delete organization](api/delete_v2_organizations_id.md)
  * [Search organizations](api/get_v2_organizations_search.md)
  * [Read revision history](api/get_v2_organizations_id_history.md)

* v2 usage
  * [List usage](api/get_v2_usage.md)
  * [Create usage-record](api/post_v2_usage.md)
  * [Get usage-record](api/get_v2_usage_id.md)
  * [Update usage-record](api/patch_v2_usage_id.md)
  * [Delete usage-record](api/delete_v2_usage_id.md)
  * [Search usage](api/get_v2_usage_search.md)
  * [Read revision history](api/get_v2_usage_id_history.md)

* v1 Status
  * [Get platform status](api/get_v1_status_summary.md)

* Webhook deliveries
  * [configuration.changed](events/configuration.changed.md)
  * [boundary.changed](events/boundary.changed.md)
  * [session.closed](events/session.closed.md)
  * [evaluation.completed](events/evaluation.completed.md)
  * [alert.opened](events/alert.opened.md)
  * [token.revoked](events/token.revoked.md)

## MCP

* mcp
  * [Server overview](mcp/server-overview.md)
  * [Tool catalog](mcp/tool-catalog.md)
  * [Authentication](mcp/authentication.md)
  * [Local stdio](mcp/local-stdio.md)
  * [Hosted SSE](mcp/hosted-sse.md)
  * [Claude setup](mcp/claude-setup.md)
  * [Cursor setup](mcp/cursor-setup.md)
  * [Codex setup](mcp/codex-setup.md)
  * [Resource discovery](mcp/resource-discovery.md)
  * [Tool permissions](mcp/tool-permissions.md)

* Start here
  * [MCP overview](start/mcp.md)

## BaC

* bac
  * [YAML schema](bac/yaml-schema.md)
  * [CLI installation](bac/cli-installation.md)
  * [Initialize a workspace](bac/initialize-a-workspace.md)
  * [Validate a manifest](bac/validate-a-manifest.md)
  * [Plan changes](bac/plan-changes.md)
  * [Apply revisions](bac/apply-revisions.md)
  * [Detect drift](bac/detect-drift.md)
  * [GitOps workflows](bac/gitops-workflows.md)
  * [Promote configuration](bac/promote-configuration.md)
  * [Recover a revision](bac/recover-a-revision.md)

* Start here
  * [BaC overview](start/bac.md)

## CI/CD

* cicd
  * [GitHub Actions](cicd/github-actions.md)
  * [GitLab CI](cicd/gitlab-ci.md)
  * [PR policy gates](cicd/pr-policy-gates.md)
  * [Preview environments](cicd/preview-environments.md)
  * [Rollback](cicd/rollback.md)
  * [Protected branches](cicd/protected-branches.md)
  * [Artifact promotion](cicd/artifact-promotion.md)
  * [Secret injection](cicd/secret-injection.md)
  * [Failure diagnostics](cicd/failure-diagnostics.md)
  * [Release evidence](cicd/release-evidence.md)

* Start here
  * [CI/CD overview](start/cicd.md)
