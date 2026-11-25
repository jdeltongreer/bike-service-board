# Bike Service Board

A small PWA for bike maintenance: equipment specs, time- and mileage-based reminders, a service log, and calendar (.ics) export for phone alerts.

- Data stays on the device (localStorage). Use **Download backup** regularly; restore with **Restore from a backup file**.
- To move data from the Claude artifact version: open it, **Copy backup**, then paste into **Or paste backup JSON** here and tap **Restore**.
- After changing any file, bump `VERSION` in `sw.js` so installed copies update.

Planned: mileage from Garmin Connect updates each bike's odometer, which drives every mile-based reminder.
