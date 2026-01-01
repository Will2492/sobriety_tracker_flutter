# SobriOK UX Flow

This document describes the user experience flow and screen structure of the SobriOK app.

---

## 1. App launch

### First launch
- App opens on Home screen
- If no start date exists → show "Start tracking" action
- Language is selected automatically (system) but can be changed manually

### Returning user
- App opens on Home screen
- Current sobriety duration is visible immediately

---

## 2. Home screen (Core screen)

### Displays
- Sobriety duration (days / hours / minutes)
- Calm label ("You have been sober for")
- Current milestone progress

### Actions
- Reset / relapse (with confirmation)
- Open detailed stats (Premium entry point)
- Open settings

---

## 3. Milestones

### General rules
- Milestones appear automatically
- Milestones are never blocked by Premium
- Tone is neutral and non-judgmental

### Milestone screens
- 90 days
- 180 days
- 270 days
- 365 days

Each milestone screen includes:
- Title
- Short reflective message
- Optional action to receive Telegram message

---

## 4. Premium flow

### Entry points
- Attempt to open advanced analytics
- Optional banner on Home screen (non-intrusive)

### Paywall screen
- Clear description of Premium value
- Price: €9.99 / month
- Auto-renewal explanation
- "Continue free" option always visible

---

## 5. Settings screen

### Options
- Language selection (English / Russian)
- Premium status
- Restore subscription
- About SobriOK

---

## 6. Telegram integration (later)

### Flow
- Available after milestone completion
- User receives a one-time token
- Token is used in Telegram bot
- Bot responds in user's selected language

---

## 7. Error & edge cases

- App works without internet
- No blocking dialogs
- No forced login
- Clear messaging on reset
