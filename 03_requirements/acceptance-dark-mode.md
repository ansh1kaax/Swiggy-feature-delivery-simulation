# Acceptance Criteria – Dark Mode Feature -draft v1

## Functionality
- The user can manually toggle between light and dark mode via a switch on the settings or home screen.
- The default UI mode is light.
- Once selected, the chosen mode (light or dark) persists across sessions until manually changed.
- The dark mode applies consistently across all screens, including home, cart, settings, order summary, etc.

## Scope and Coverage
- The feature covers the entire UI with no exclusions.
- Toggle switch should be accessible, intuitive, and visible in primary navigation.

## Performance and Usability
- No noticeable lag or screen flicker during theme switching.
- Visual consistency is maintained for all UI components in both modes.
- Feature is tested for accessibility compliance (contrast ratios, font readability in dark mode).

## Data Persistence
- User preference is saved on device or in app state (e.g., local storage or database).

## User Impact
- Should improve eye comfort during low light usage.
- Designed to enhance UX on OLED screens.
- Statistically expected to improve retention and engagement based on user preferences.

## Out of Scope
- Auto-sync with device settings is excluded to reduce implementation complexity and UI load.
