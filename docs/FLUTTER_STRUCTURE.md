# SobriOK Flutter Structure

This document defines the planned Flutter project structure for SobriOK.

---

## lib/

### app/
- app.dart (MaterialApp, localization, theme)
- router.dart (navigation logic)

---

### features/

#### sobriety/
Core sobriety tracking functionality.

- presentation/
  - sobriety_home_page.dart
  - milestone_page.dart
- domain/
  - sobriety_service.dart
  - milestone_calculator.dart
- data/
  - sobriety_storage.dart

---

#### premium/
Premium-related logic.

- presentation/
  - premium_paywall_page.dart
- domain/
  - premium_service.dart
- data/
  - subscription_repository.dart (later)

---

#### settings/
User preferences and configuration.

- presentation/
  - settings_page.dart
- domain/
  - language_service.dart
- data/
  - settings_storage.dart

---

### shared/

Common reusable components.

- widgets/
- styles/
- utils/

---

## Key services (domain)

- SobrietyService
  - start date
  - duration calculation
  - reset flow

- MilestoneCalculator
  - 90 / 180 / 270 / 365 logic
  - milestone state tracking

- PremiumService
  - isPremium flag
  - feature access control

- LanguageService
  - current language
  - persistence

---

## Data layer principles

- Local-first (SharedPreferences or similar)
- No mandatory backend
- Backend only for Telegram integration (later)

---

## Architectural principles

- UI has no business logic
- Domain layer is testable
- Premium never blocks core functionality
- Localization applied everywhere
