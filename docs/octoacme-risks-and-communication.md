# OctoAcme — Risk Management & Communication

## Purpose
Explain how to identify, manage, and communicate risks and dependencies.

## Risk Register
Maintain a simple table with:
- ID
- Description
- Impact (High/Med/Low)
- Likelihood (High/Med/Low)
- Owner
- Mitigation plan
- Status

## Risk Lifecycle
- Identify: during planning and ongoing execution
- Assess: estimate impact and likelihood
- Mitigate: reduced via actions, contingency plans
- Monitor: review at weekly syncs and update status

## Stakeholder Communication
- Identify stakeholder groups and communication needs (e.g., engineering, sales, support)
- Provide regular updates (weekly or milestone-based)
- Use a single source of truth (project README or release doc) for status

## Communication Templates

### Weekly Status Template
```
**Progress this week:**
- [Completed items with links to PRs/artifacts]

**Next steps:**
- [Planned work for upcoming week]

**Risks & blockers:**
- [Current risks with severity and status]

**Ask / decisions needed:**
- [Specific questions or approvals required]

**Metrics:**
- [Key success metrics from Project One-pager]
```

### Incident Communication Template
```
**Incident Summary:**
- [Brief description of the issue]

**Impact:**
- [Affected users/systems/features]

**Actions Being Taken:**
- [Current mitigation steps]

**Expected Timeline:**
- [ETA for resolution or next update]

**Next Steps:**
- Post-incident blameless retrospective scheduled for [date/time]
- Root cause analysis owner: [name]
```

See also: [Stakeholder Communication Summary Template](stakeholder-communication-template.md) for comprehensive stakeholder updates.

## Escalation Paths
Clear escalation paths ensure risks and blockers are addressed quickly and transparently:

### Standard Escalation Ladder
1. **Team-level**: Team discusses and attempts to resolve in daily standup
2. **PM level**: PM coordinates across teams, evaluates impact, updates stakeholders
3. **Product Lead**: For strategic decisions or resource reallocation
4. **Sponsor**: For business-impacting issues requiring executive decision

### When to Escalate
- Blocker unresolved after 2 business days
- Risk impact upgraded to High
- Dependency on external team not responding
- Budget or timeline variance >20%
- Security or compliance concerns

### Escalation Best Practices
- Document the issue, impact, and attempted resolutions before escalating
- Provide specific ask or decision needed
- Set a response deadline appropriate to urgency
- Follow up in writing with outcomes and next steps

For security incidents, follow the security incident runbook and notify Security on-call immediately.

See also: [Risk Escalation Checklist](risk-escalation-checklist.md)
