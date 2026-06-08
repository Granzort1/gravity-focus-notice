---
title: Update Notices
---

# Update Notices

## 2026-06-08 Update Notice

Hello, I'm the app developer.

This update fixes a few issues that got in the way while using the Timetable and Pomodoro, along with some small usability improvements. The fixes are included in **version 1.0.56**, so please update to the latest version.

## Issues Fixed

- Fixed an issue in a Timetable task's detail settings where editing and saving the task could fail to save after its recurring schedule had been deleted. I also fixed a related issue where re-enabling recurrence (e.g., Daily) on such a task had no effect — now a fresh repeat is created properly, so events are generated from the next day onward as well.
- When a task name was too long, it used to be cut off with "…". In the Timetable and Pomodoro, the text now scrolls gently so you can read the whole thing.
- Fixed an issue where stray-thought notes were not being saved on the Pomodoro focus screen.

I also smoothed out a number of small rough edges around the app to improve everyday usability.

Thank you.

---

## 2026-05-30 Update Notice

Hello, I'm the app developer.

This update fixes a few issues found during everyday use. The fixes are included in **version 1.0.55**, so please update to the latest version.

## Issues Fixed

- Fixed an issue where notifications kept arriving even after turning off "Task notifications" in Settings.
- Fixed an issue where plans and notes written in guest mode were not carried over after signing in.
- Fixed an issue where the stray-thought note sheet during a Pomodoro could stay locked and block further input when saving failed.
- Fixed an issue where active subscribers were incorrectly shown "Free trial: N days left."
- Fixed an issue where the daily checklist's automatic reset did not sync across devices.
- Fixed an issue where the character counter in Diary and Thought Journal did not update while typing.

I also cleaned up unused internal code to improve the app's stability.

Thank you.

---

## 2026-05-28 Update Notice

Hello, I'm the app developer.

Fixed an issue that caused errors during sync. This has been resolved in **version 1.0.54**, so please update to the latest version.

Thank you.

---

## 2026-05-25 Update Notice

Hello, I'm the app developer.

This update strengthens schedule planning, makes the Diary and Thought Journal easier to browse by date, and brings two new Windows-only features: a Pomodoro mini window and a desktop calendar widget.

## Update Details

1) New "Schedule" menu + "Daily Plan" renamed to "Timetable"
- A new "Schedule" menu lets you record events across days and date ranges on a calendar. The previous day-by-day planner was not a great fit for longer-term tracking, so I built a separate calendar-based menu just for that.
- Alongside, the existing "Daily Plan" menu was renamed to "Timetable" — to make it clear at a glance that it's for laying out the hours within a single day.

2) Date-pick calendar in Diary and Thought Journal
- Both menus now include a calendar for picking a date, so you can look back at entries from any specific day more easily.

3) New Windows-only features
- Pomodoro mini window: After starting a Pomodoro, minimize the app and a small Pomodoro window will appear on the side of your screen to show your progress. Keep the main app minimized and work freely — just glance at the mini window when you want to check the remaining time or status.
- Desktop calendar widget: You can now pin the "Schedule" calendar to your Windows desktop. Turn it on from the Windows app under *Settings → Show desktop calendar*. From here on, managing your schedule through the desktop widget should feel much more comfortable.

Going forward, the app's focus will be on usability and overall feel. If anything bothers you, or you have ideas for improvement, please reach out anytime via skadldh@gmail.com, or through the message feature at the top of the Settings menu. Real-world feedback from users makes a huge difference.

Thank you.

---

## 2026-04-30 Update Notice

Hello, I'm the app developer.

This update redesigns the Pomodoro screen and adds further improvements to sync stability.

## Update Details

1) New Pomodoro screen design
- Tap a task to enter focus mode immediately, without being asked for a duration first.
- A breathing orb sits in the middle of the screen so you can settle into a calm inhale-and-exhale rhythm.
- While paused, a stop button appears alongside; tapping the check button at the bottom right marks the task as done and lets you pick the next task right away.
- Stray thoughts that pop up mid-focus can be jotted down as a single line in the on-screen card.
- Fixed an issue where finishing a task in Pomodoro did not check it off in the Today tab.

2) Further sync stability improvements
- Patched additional edge cases where some tasks were dropped or duplicated during Windows-Android sync.
- Hardened the cleanup logic for long-deleted items so sync state stays consistent over time.

Thank you.
