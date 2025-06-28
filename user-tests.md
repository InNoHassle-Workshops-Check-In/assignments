# User Tests for InNoHassle Workshops

## Workshop Creation (Admin)

- Log in as admin
- Navigate to “Workshops” page
- Fill in all required fields: title, description, location, date, capacity
- Submit the form

---

## Workshop Editing (Admin)

- Log in and open existing workshop via dashboard
- Click edit button
- Change title and location
- Submit updated info

---

## Workshop Listing (Public)

- Log in as regular user
- Open workshop listing page
- See list of workshops sorted by date
- Each workshop displays: title, date, location
- Past workshops should not allow check-in

---

## Check-In (User)

- Log in as regular user
- Visit workshop page one day before the event
- Click “Check In”
- Expect success message
- Refresh page — check-in button should show status

---

## Admin View of Check-Ins

- Log in as admin
- Open a workshop's check-in dashboard
- See list of checked-in users email

---

## Mobile Responsiveness

- Open check-in page on phone (or mobile dev tools)
- All buttons and lists must be visible and usable
- No horizontal scroll or overflow should occur

---

## Telegram Alias Click

- Log in and open workshop details page
- Organizer's Telegram alias should be visible (e.g., @khaertdinovr)
- Click the alias
- Expect new tab to open: https://t.me/khaertdinovr
- Telegram web or app should handle the link

---

## Location Click → InNoHassle Map

- Open workshop details page
- Location should be displayed as a clickable link (e.g., "108")
- Click the location
- Expect redirect or new tab to open InNoHassle map
