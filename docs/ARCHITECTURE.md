# SobriOK Architecture

SobriOK is structured around clarity, separation of concerns, and future scalability.

## Core layers

- Presentation (UI screens, widgets)
- Domain (business logic, calculations)
- Data (local storage, subscriptions, integrations)

## Key modules

### Sobriety
- Start date
- Duration calculation
- Relapse / reset flow
- Milestones (90 / 180 / 270 / 365)

### Localization
- English
- Russian
- Manual language selection (not system-only)

### Premium
- Optional monthly subscription
- Feature flags via isPremium
- No blocking of core functionality

### Integrations (later)
- App Store / Google Play subscriptions
- Telegram bot (milestones and messages)

## Principles
- Core functionality is always free
- Premium enhances insight, not access
- No medical claims
- Calm, neutral tone
