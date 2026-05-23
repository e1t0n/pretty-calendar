# pretty-calendar

📅 iCloud Calendar Integration (Blade Template)

To make iCloud iCal feeds work with the "Pretty Calendar" template, the code was mapped to the iCal standard and the London timezone.

## Key Changes Made:

- Timezone: Updated to Europe/London (supports GMT/BST).
- Data Path: Switched from data to ical.
- Field Mapping: Mapped summary -> SUMMARY, start.dateTime -> DTSTART, etc.
- All-Day Logic: Added logic to detect 8-digit date strings (Birthdays/Holidays).

[res/pretty-calendar.png]
![iCloud calendar sample][def]

[def]: res/pretty-calendar.png "iCloud Calendar"