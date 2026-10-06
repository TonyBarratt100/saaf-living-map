# SAAF Living Map

*Problem.* SAAF's agents live in GitHub repos and in a portal list with a review status. Maturity, phase and dependencies are tracked by hand and go stale.

*Idea.* Each agent repo carries a small agent.yaml. A GitHub Action collects them and renders one map: islands (Planning, Fieldwork, Reporting, AI Governance & QA, Monitoring, Shared Infrastructure), maturity (Draft workplan → Building → QA Assessment → Ready), dependencies and open slots. It updates when a repo changes.

*Who benefits.* Participants find an agent to reuse or join. Maintainers see gaps and plan hackathon tracks. Member organisations see what SAAF has delivered and how mature it is.

*Hackathon scope (today).*
1. Define agent.yaml (see agent.example.yaml).
2. Script that reads manifests from a list of repos and writes map.json.
3. Static page that renders map.json as the island map and an overview.

Team: Tony Barratt, Anja Nell, Bob McLaughlin

See also: the mandate guard built on this schema, in [SAAF-Project/Audit-criteria PR #1](https://github.com/SAAF-Project/Audit-criteria/pull/1).
