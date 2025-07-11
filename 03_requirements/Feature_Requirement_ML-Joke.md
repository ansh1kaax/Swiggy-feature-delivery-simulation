# ML Joke Generator – Feature Requirement

## Feature Name
Smart Food Joke Generator (ML + Rule-Based)

## Objective
Add a light, engaging touch to the user experience by showing personalized or topical food-related jokes on the home screen, based on user behavior like past orders and searches. The goal is to increase retention, in-app engagement, and order completion.

## Target Platform
- iOS App (Phase 1 simulation)
- Android (future consideration)

## When It Appears
- On the home screen after brief idle time (~3–5 seconds)
- Post-launch and/or during low-interaction sessions
- Not on the order screen or payment flow

## Tone of Voice
- Friendly
- Humorous
- Sarcastic (Zomato-style)
- Pop-culture references (Bollywood, trending reels, movie dialogues, etc.)
- Not overly personal to maintain user comfort

## Example Joke Types
- “Bhai saying 'order me a pizza', Me: Tera swiggy idhar chhod ke gaya tha ya tera instamart?!”
- “Customer: ‘Bhaiya extra chutney do!’ Delivery guy in Majnu’s voice: ‘Tu toh gaya kaam se!’”
- “Swiggy knows you better than your best friend. Go order.”

## Data Inputs
- User past order history
- Search activity
- Time of day
- Trending food items or offers
- Location metadata (optional, not precise)

## System Behavior
- New users: Use a random set of default jokes (non-personalized)
- Repeat users: Joke is picked based on past activity (rule-based)
- ML Simulation: This phase is rule-based but backend will simulate potential integration with a trained ML model (future sprints)

## Privacy & Control
- Data is anonymized, not tied to specific identity
- Users can toggle off the feature if they feel annoyed
- Once toggled off, it stays off unless manually turned back on

## ML Integration Plan
| Phase | Description |
|-------|-------------|
| Phase 1 | Rule-based joke mapping system (Pizza → random pizza joke from bank) |
| Phase 2 | ML/NLP model trained on user segmentation to generate dynamic humor tone + category-based insight |

## Edge Cases & Fallbacks
- No prior data: Show randomized neutral joke
- Data fetch fails (offline): Show a default meme quote
- Joke not shown during order/payment flow to avoid distractions

## Success Criteria (Feature-specific KPIs)

| Metric | Success Criteria |
|--------|------------------|
| Feature Engagement | 20% users click to see another joke (optional interaction) |
| Opt-Out Rate | <10% toggle off the feature |
| Retention Boost | +5% higher retention over 2 weeks among exposed users |
| Order Rate | Uplift of 3% in completed orders after exposure |

## Tools & Stack (Simulation Only)

| Layer | Simulated Tools |
|-------|------------------|
| Data Rules | JSON Mapping File (Pizza → joke array) |
| Backend Trigger | Simulated logic in Python or Firebase Rules |
| Frontend Display | iOS Swift screen with mock UI |
| Joke Source | Hardcoded joke library in JSON/CSV |
| ML Layer (Planned) | Placeholder for classification model (Python/Colab) |
| Storage | Firebase / mock backend |

## Dependencies
- Frontend dev to embed joke display area
- Content writer or joke curator
- Rule logic builder (for now, you)
- Optional: Integrator for trending Bollywood APIs or Twitter (future)

## Why This Feature?
- Helps differentiate Swiggy by building emotional loyalty
- Adds personality and delight to daily utility
- Reduces bounce rate after app open
- Drives habit loop by linking food ordering with fun

## Future Enhancements
- User can react to jokes (❤️ / 😂)
- Trending jokes based on festival/mood
- Social share button (share the joke)
- Dynamic jokes using sentiment classifier
