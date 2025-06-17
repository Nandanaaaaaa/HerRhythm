# 🔄 HerRhythm – Development Workflow

This document describes the development roadmap, features, and UI flows for HerRhythm.

---

## ✅ Current Features

- ✅ Onboarding & cycle configuration
- ✅ Period & ovulation prediction
- ✅ Symptom, mood, and flow logging
- ✅ Local database storage
- ✅ Smart reminders
- ✅ Calendar and insights visualization
- ✅ Biometric lock support

---

## 📆 Development Phases

### Phase 1: Core Tracker MVP
- [x] Onboarding screen
- [x] Period logging interface
- [x] Local state and database logic
- [x] Calendar visualization
- [x] Notifications (Expo)

### Phase 2: Symptom Logging & Insights
- [ ] Multi-symptom logging screen
- [ ] Emotion/mood tracker
- [ ] Charts & analytics (line graph, pie, trends)

### Phase 3: Personalization + Security
- [ ] Biometric auth
- [ ] Local-only vs cloud-sync toggle
- [ ] Advanced cycle predictions (adaptive)

### Phase 4: Social & AI (Optional)
- [ ] Anonymous discussion forum
- [ ] AI-based symptom suggestions
- [ ] Custom goal setting and alerts

---

## 🧭 User Workflow

1. **Onboarding**
   - Select typical cycle length & flow
   - Set reminder preferences
   - Choose data storage mode

2. **Home Screen**
   - See today’s prediction
   - Quick log buttons for period, mood, and symptoms

3. **Calendar**
   - Month view
   - Color-coded:
     - Red: period
     - Green: fertile
     - Yellow: ovulation

4. **Log Screen**
   - Select date
   - Tap symptoms (e.g., bloating, headache)
   - Save to local storage

5. **Insights**
   - Show average cycle length
   - Common symptoms chart
   - Mood trends over time

6. **Settings**
   - Manage reminders
   - Switch between local/cloud
   - Enable biometric lock

---

## 🧪 QA & Testing

- Unit testing: `Jest`
- Integration testing: `React Native Testing Library`
- E2E: `Detox` (optional)
- Manual testing across Android/iOS using Expo Go

---

## 🔮 Future Ideas

- Period prediction with ML
- Companion Apple Watch / WearOS app
- Integration with Apple Health / Google Fit
- Mood-based journaling with emotion detection

