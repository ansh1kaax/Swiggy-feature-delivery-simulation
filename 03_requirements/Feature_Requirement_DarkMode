Feature Name:
Dark Mode (Manual Toggle)

Purpose & Goal:
Introduce a manual toggle for Dark Mode in the Swiggy app to enhance user comfort, reduce eye strain, and align with modern user interface trends—especially on OLED displays. This feature supports improved user engagement and long-term retention.

User Story:
As a user, I want to enable dark mode inside the Swiggy app manually so that I can reduce eye strain during low-light usage and enjoy a visually comfortable experience.

Functional Requirements:
Requirement ID	Description
DRK-001	Add a toggle switch in the app settings labeled “Dark Mode”
DRK-002	Default setting should be Light Mode for all users
DRK-003	When user toggles to Dark Mode, all screens should adopt dark-themed UI
DRK-004	User preference should persist across app sessions (stored locally)
DRK-005	UI elements including homepage, order screen, cart, and settings should all switch to dark mode
DRK-006	There should be no partial or screen-specific exclusions
DRK-007	Toggle must not sync with system dark/light mode settings (for now)

Non-Functional Requirements:
NFR ID	Description
NFR-01	App performance should not degrade when switching modes
NFR-02	Dark Mode must render with accessibility contrast standards (if feasible)
NFR-03	Toggle should switch modes in < 300ms for seamless UX

Design Guidelines:
Product manager will provide final dark theme mockups via Figma.

Use dark greys (#121212) and avoid pure black for OLED-friendliness.

Icons and text must invert colors properly for visibility.

Dependencies:
Theme toggling logic handled via frontend state manager (e.g., Redux/React Context)

Persistence via local storage or Shared Preferences (iOS/Android)

Success Criteria (KPIs):
Dark mode toggle adoption rate (% of users enabling it)

Retention rate among dark mode users (weekly/monthly)

Error logs or crashes post dark mode release = 0

UI toggle switch click responsiveness (< 300ms)

Notes:
This version does not auto-switch with system theme.

If user switches back to light mode, their new preference should override past settings.

