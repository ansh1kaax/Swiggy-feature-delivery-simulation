# Escalation Flow – Swiggy Feature Delivery Simulation (Draft v1)

**Disclaimer:** This is a solo simulation project. The following flow is designed to mirror real-world product escalation mechanisms.

## Escalation Triggers

* Critical bug in any core feature (ML Joke Generator, Dark Mode, Mini-Games)
* Feature not deployable within allocated sprint timeline
* QA fails or success metric deviations by over 20%
* Fallback logic also fails during testing phase

## Escalation Chain

1. **Owner (Simulated PM – Anshika)**

   * Reviews blocker via Trello (`🚨BLOCKED` label)
   * Initial resolution attempt within 24 hours

2. **Primary Stakeholder Escalation (Simulated Functional Owner)**

   * iOS: Sarthak (iOS UI/logic issues)
   * ML: Akhil (ML joke generator logic)
   * UX: Rhea (UI/animation breakdown)
   * QA: Priya (bug or metric failure)

3. **Slack Escalation Trigger**

   * Slack channel ping auto-initiated when `🚨BLOCKED` label is added on Trello
   * Manual update also posted for timeline risks

## Escalation Timeline

* **0–1 day**: Trello update → Slack alert → PM review
* **1–2 days**: Stakeholder troubleshooting + resolution plan
* **2–5 days**: Escalation resolved or fallback logic deployed

## Notes

* Escalation is always reviewed and resolved within the sprint
* All escalations tracked in Trello card comments for transparency
* No severity labels used in simulation; all escalations treated with equal priority due to solo workflow

---

These plans ensure realistic SDLC and Agile simulation, while allowing for proactive troubleshooting in the feature delivery flow.
