---
title: "Privacy Policy: WebReg Helper for USC Students"
---

# Privacy Policy: WebReg Helper for USC Students

Last updated: October 28, 2026

WebReg Helper for USC Students is an unofficial Chrome extension made by a USC student. It is not affiliated with or endorsed by the University of Southern California.

## What stays on your computer

Everything the extension saves is kept in your browser's own extension storage (`chrome.storage`) on your computer. Apart from the Notify Me alerts you ask for (below), none of it is sent to the developer or to any server the developer runs. That includes:

- The majors, minors and catalogue year you pick, and the courses you tick as taken.
- What the extension reads from a STARS degree progress report you choose to upload: your courses, the terms you took them, your programs and their catalogue years. The PDF is read inside your browser. Your name, student ID, address and grades are not kept.
- Your course plan, myCourseBin sections, blocked-off calendar times, and panel settings.
- Cached copies of public USC Catalogue pages and RateMyProfessors scores, so they load faster next time.

Calendar export makes an .ics file on your computer. **Export to Google Calendar** then opens Google Calendar's import page, and you choose whether to upload the file there.

Removing the extension deletes all of it. **Remove STARS report** in the myRequirement panel deletes the report's data on its own.

## What the extension connects to

The extension sends no analytics or tracking data, and it shows no ads. It only talks to these sites, to show you their information:

- **webreg.usc.edu**: the WebReg pages you're already signed in to, such as other pages of a course list and your myCourseBin.
- **catalogue.usc.edu**: the 2021-22 to 2026-27 catalogues are built into the extension. Only for a catalogue year that isn't built in, the public catalogue pages for the programs you pick load in a background tab that closes by itself, because the catalogue blocks other ways of reading it.
- **usc.simplesyllabus.com**: course codes and titles, to find syllabi in USC's syllabus library. This uses your own Simple Syllabus sign-in, and the extension never sees your password.
- **ratemyprofessors.com**: instructor names from the section you're viewing, to show their public ratings.
- **usc-webreg-notify.stonewu777.workers.dev**: the developer's Notify Me server, only when you ask for a seat alert (below).

## Notify Me

**Notify Me** on a WebReg section emails you when a seat opens in it, and texts you too if you choose. When you press Notify Me, the extension sends the email address you type, your mobile number if you gave one and checked the text alert box, and that section's term, course, course title and section number to the developer's notify server (hosted on Cloudflare Workers). Every 5 minutes the server checks the section's seat count on USC's public Schedule of Classes (classes.usc.edu). Each time the section goes from full to having a seat, it sends you an email through Resend, an email delivery service, and a text through Twilio, a text messaging service, if you gave a number. That happens at most once an hour. Your alert, with your email and phone number, is deleted 120 days after you set it.

While an alert is waiting, the extension asks the server about once a minute whether it has fired, so it can also show a desktop notification. Those checks send only the alert's random ID, never your email.

Your email and phone number are used only to send those alerts. They are never used for marketing, never shared and never sold. To cancel an alert, press **Stop these alerts** at the bottom of any alert email, which deletes it with your email and number. You can also write to the contact address below.

## Text alerts

Text alerts are not switched on in the extension yet. Until they are, the Notify Me popup has no phone field and no phone numbers are collected. Once on, text alerts are optional and only sent if you enter a mobile number and check the consent box in the Notify Me popup. You get one text each time a seat opens in a section you're watching, at most once an hour, for up to 120 days. Msg & data rates may apply. Reply **STOP** to stop all texts, or **HELP** for help. No mobile information will be shared with third parties or affiliates for marketing or promotional purposes. Text messaging opt-in data and consent are not shared with any third parties, except Twilio, which delivers the texts. Full terms: https://stonewu777dw.github.io/webreg-helper-privacy/terms

## Buy me a Coffee

The **Support WebReg Helper** coffee button is a plain link that opens buymeacoffee.com/stonewu777 in a new tab. The extension sends nothing to Buy Me a Coffee. If you choose to support there, their privacy policy applies.

## Sharing

The developer receives only what you send through Notify Me (your email, and your phone number if you opt in to texts), and never sells or shares it. The sites and services above only get what's listed, and their own privacy policies apply.

## Contact

Questions: stonewu777@gmail.com
