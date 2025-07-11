# Feature Summary – Swiggy Feature Delivery Simulation

This project delivers three user-facing features designed to improve engagement, personalization, and usability within the Swiggy app. Each feature is scoped with functional and non-functional criteria and aligned with product and user goals.

---

## 1. Dark Mode (Manual Toggle)

**Goal**: Enhance user comfort and visual experience, particularly in low-light environments and on OLED devices.

**Key Points**:
- Users can manually enable or disable dark mode from settings.
- Default mode is Light; toggle persists across sessions.
- Applies uniformly across all app sections.
- No sync with system theme settings.

**Non-functional expectations**:
- <300ms toggle response time.
- High accessibility and contrast.
- Seamless UI transition.

**KPIs**:
- Dark Mode Adoption Rate
- Toggle Click Responsiveness
- Retention Boost Among Dark Mode Users

---

## 2. Smart Food Joke Generator (ML + Rule-Based)

**Goal**: Add personalized, contextual humor to the app to improve user retention and session quality.

**Key Points**:
- Jokes are shown on the home screen after brief inactivity.
- Rule-based system maps user behavior (orders/searches) to joke categories.
- Users can toggle this feature off if desired.
- Joke source includes pop-culture, food humor, and Bollywood references.

**Data Privacy**:
- Fully anonymized user data.
- No sensitive information is collected.

**ML Plan**:
- Current version: Rule-based
- Future version: ML/NLP model to segment users and generate humor

**KPIs**:
- Joke Engagement Rate (click/interact)
- Opt-out rate
- Retention uplift among exposed users

---

## 3. Mini-Games (Fun Zone + Post-Order Engagement)

**Goal**: Increase app retention, reduce boredom during wait-time, and drive micro-rewards via gamification.

**Game Types**:
- Hangman
- Spin-the-Wheel
- Tic-Tac-Toe
- Dot and Line

**Reward Logic**:
- Win-based Swag Coins
- Max 5,000 coins/day
- Redemption: ₹25 OFF (25k coins), Free Delivery (50k coins)

**Access Points**:
- Home Screen (Fun Zone button)
- Post-Order Screen ("Join 10,000+ people playing now")

**UI Expectations**:
- Animated, brand-consistent games
- Optional sounds and engagement visuals
- HTML5 games embedded via WebView (iOS simulated)

**Data Privacy**:
- Only game interaction is logged
- No user identity or sensitive data tracked

**KPIs**:
- Game Participation Rate
- Swag Coin Redemptions
- Re-visit rate for Fun Zone

---

Each feature is planned with technical, user, and business alignment in mind, scoped across Sprints 1–4 under Agile SDLC.
