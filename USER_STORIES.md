# AgentWeave — User stories

**Product:** [PRODUCT.md](./PRODUCT.md)


### Smart-city operator

- As an operator, I want context-triggered reconfiguration proposals for a street-light agent group, so energy and safety modes track weather/traffic without rewriting firmware.
- As an operator, I want canary rollout, so a bad config cannot darken a whole district.
- As an operator, I want a kill-switch to last-safe config, so incidents stop quickly.

### Agent developer

- As a developer, I want a variability model of bodies and behaviors, so I stop forking code per hardware SKU.
- As a developer, I want evaluative feedback attached to config versions, so learning is grounded in field outcomes.

### Safety reviewer

- As a safety reviewer, I want mandatory approval on traffic-signal agent changes, so ML suggestions never go live unreviewed.
- As a safety reviewer, I want an audit of approvals and KPI evidence for each change.

### Systems integrator

- As an integrator, I want to reuse a street-light variability model across municipalities with local overrides, so delivery margins improve.
- As an integrator, I want per-site isolation, so one city’s learning does not leak into another’s production.

### Citizen experience / complaints desk

- As a complaints owner, I want feedback events (e.g., glare, unsafe darkness) to enter the evaluative loop, so configuration learning includes lived experience.
