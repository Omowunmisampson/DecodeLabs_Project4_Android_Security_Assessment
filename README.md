# Project 4: Android Security Assessment

## Overview
This project documents a basic security review of an Android phone, adapted from a system vulnerability checklist. The assessment records settings the user checked, observations, recommendations, and areas that could not be assessed on Android.

## Scope
Checks recorded:
- Screen lock (fingerprint and PIN enabled)
- Android security update date: 1 April 2026
- Google Play system update date: 1 July 2026; phone prompted for a restart, which was completed. Whether the displayed update date changed afterward was not confirmed.
- System update check: no new system/security update was available at the time checked
- Google Play Protect: scan reported “No harmful apps found”
- Permission Manager access counts and whether apps were recognised

This is a phone-based Android review, not a Windows/macOS PowerShell audit. Firewall configuration, disk encryption status, administrator/guest account configuration, and other platform-specific checks were not verified.

## Files
- `Vulnerability_Report.md` — findings and recommendations
- `Self-Verification.md` — checks performed and limitations

## Important note
Permission counts are descriptive, not proof of a vulnerability. Recognising an app does not by itself establish that every permission is necessary. No claim is made that the device is completely secure.
