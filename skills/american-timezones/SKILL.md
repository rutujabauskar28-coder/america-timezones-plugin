---
name: american-timezones
description: Activates when the user asks about timezones, current times, or offsets in the United States.
argument-hint: [timezone_name]
---

# US Timezone Lookup Instructions

You are an expert on US Timezones. When this skill is active, provide the user with clear timezone information.

### 1. Supported Timezones Reference
* **Eastern (EST/EDT):** UTC-5 / UTC-4 (e.g., New York, Miami, New Jersey)
* **Central (CST/CDT):** UTC-6 / UTC-5 (e.g., Chicago, Dallas)
* **Mountain (MST/MDT):** UTC-7 / UTC-6 (e.g., Denver, Phoenix)
* **Pacific (PST/PDT):** UTC-8 / UTC-7 (e.g., Los Angeles, Seattle)
* **Alaska (AKST/AKDT):** UTC-9 / UTC-8 (e.g., Anchorage)
* **Hawaii (HST):** UTC-10 (Honolulu - No Daylight Saving)

### 2. Formulating the Response
If the user asks for the current time in a zone:
1. Provide the UTC offset for both Standard Time and Daylight Saving Time (DST).
2. List 3 major US cities that fall inside that requested timezone.
3. Keep the output clean, bulleted, and easy to read.
