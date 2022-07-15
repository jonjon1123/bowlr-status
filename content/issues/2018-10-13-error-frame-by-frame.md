---
title: Error When Entering In Frame-By-Frame Scores
date: 2018-10-13 17:30:00
resolved: true
resolvedWhen: 2018-10-15 14:09:00
# Possible severity levels: down, disrupted, notice
severity: disrupted
affected:
  - iOS App
  - Android App
section: issue
---

*Resolved (iOS)* - The issue has been identified and resolved in iOS. {{< track "2018-10-15 14:09:00" >}}

*Resolved (Android)* - The issue has been identified and resolved in Android. {{< track "2018-10-13 18:00:00" >}}

*Investigating* - Some users are reporting getting the error **NoSuchMethodError: The getter 'alwaysShowFrameScores' was called on null.**. A bug has been identified that presents the above mentioned error when a user tries to enter in scores in frame-by-frame mode. To work around this error, users can open up the app settings and toggle the "Always show frame scores" switch from off to on and the back to off. {{< track "2018-10-13 17:30:00" >}}
