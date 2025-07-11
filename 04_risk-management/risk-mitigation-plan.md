# Risk Mitigation Plan – Swiggy Feature Delivery Simulation (Draft v1)

**Disclaimer:** This is a solo simulation project. Risk ownership is mapped hypothetically to reflect real-world structures.

## Top Risks Identified

| Risk ID | Category      | Description                                                           | Severity | Likelihood |
| ------- | ------------- | --------------------------------------------------------------------- | -------- | ---------- |
| R-001   | Feature Bugs  | Dark Mode UI inconsistencies across screens                           | High     | High       |
| R-002   | Logic Failure | ML Joke Generator returns irrelevant or failed output                 | Critical | High       |
| R-003   | Game Logic    | Reward farming in "Spin-the-Wheel" or multiplayer logic syncing fails | High     | Medium     |
| R-004   | API Sync      | Mini-games multiplayer gameplay not synced properly                   | High     | Medium     |
| R-005   | UI Breakdown  | Game visuals or joke module crash due to design mismatch              | Medium   | Medium     |

## Mitigation Strategies

| Risk ID | Mitigation Strategy                                                                                     |
| ------- | ------------------------------------------------------------------------------------------------------- |
| R-001   | Regular Figma reviews with UX team, and cross-screen UI testing before release                          |
| R-002   | Simulate joke responses with JSON logic fallback; use pre-written jokes based on order type if ML fails |
| R-003   | Define strict reward caps (5,000 Swag Coins/day); test logic with mock data per stakeholder role        |
| R-004   | Develop bot fallback mode for games like Tic-Tac-Toe in case multiplayer logic fails                    |
| R-005   | Conduct design handoff reviews and QA verification on multiple resolutions                              |

## Testing Plan

* Stakeholders simulate different user types (e.g., repeat user, new user)
* Ensure ML logic shows \~80% relevant joke placement via mock test cases
* Reward module is tested for thresholds and abuse control
* ML and UI fallbacks (static joke or idle animation) in case of API or logic failure

## Contingency Planning

* If a module fails, deploy fallback static logic (e.g., default joke or static screen)
* Games fall back to solo/bot play if multiplayer mode fails
* Maintain stakeholder communication via Slack with Trello status card updates

---
