SEHAT CARE HEALTH CAMP WEBSITE

STEP 1: Open index.html
Double-click index.html in a modern browser.

STEP 2: Real photographs
The website now displays real health-camp photographs from:
- Morpheus Foundation India
- Felix Hospital
- BEML

The image URLs are remote, so an internet connection is needed for the photos.

STEP 3: Replace the photos
Before publishing, replace the image URLs in index.html with photos that you own or have permission to use.

STEP 4: Registration
The form validates required fields, creates a registration ID, and stores demo registrations in browser localStorage.

IMPORTANT:
This is a front-end demo. Do not use browser localStorage for real patient/medical information. A production healthcare site needs a secure backend, HTTPS, access controls, appropriate privacy protections, and compliance with applicable laws and regulations.

ADD-ONS (design is unchanged)
- Appointment slots: 5 seats per time slot (change SEATS_PER_SLOT in script.js). Full slots are disabled.
- Attendance reminder: visitor picks SMS / WhatsApp / Email. Staff press "Send reminders" (demo only, nothing is really sent).
- Attendance: staff mark Pending / Present / Absent.
- Report privacy: staff PIN (demo 1234), names and phones hidden by default, health details never in the CSV, delete-all-data button.
All new code in script.js is marked with "NEW" comments.
