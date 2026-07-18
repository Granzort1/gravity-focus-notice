---
title: Update Notices
---

# Update Notices

## 2026-07-18 Update Notice

Hello, I'm the app developer.

This update makes it easier to get started when your "Timetable" is empty, with new one-tap quick-add buttons, and also refreshes the design of the "Journal" menu. The changes are included in **version 1.0.69**, so please update to the latest version.

## Update Details

1. **When the "Timetable" menu is empty, you can now add common tasks with a single tap.**
   - Tap Take meds · Meal · Work/Study · Exercise · Break, and a time block is created automatically based on the current time. Tap "Custom" to create your own task as before.
   - Tapped by mistake? Use "Undo" at the bottom to cancel right away, and if you don't need the buttons, hide them for the day with the ✕ button.
   - When a blank timetable feels overwhelming, start your day with just one easy block.
2. **The "Journal" menu design has been improved.** The list/calendar toggle has moved into the top bar so you get more room on screen, and the journal cards and calendar display have been tidied up.

Thank you.

---

## 2026-07-14 Update Notice

Hello, I'm the app developer.

This update expands widget functionality and improves overall app quality. The changes are included in **version 1.0.68 on both Android and Windows**, so please update to the latest version.

## Update Details

1. To make widgets more useful in the Windows app, we've added a new desktop widget that displays the **"Weekly Timetable" from the "Timetable" menu**. We hope it makes checking your weekly schedule easier and more convenient.
2. We've improved **sync reliability**.
3. We've changed the app's **default font** and made other quality and usability improvements throughout the app.
4. For the time being, we'll focus on **stability and usability improvements** rather than adding new features.

Thank you.

---

## 2026-07-12 Update Notice

Hello, I'm the app developer.

This update improves overall app quality and reduces excessive visual indicators in the "Timetable" menu so you can focus better on planning. The changes are included in **version 1.0.65**, so please update to the latest version.

## Update Details

1. In the "Timetable" menu, when you use **a due date together with a repeat cycle, recurring tasks are now created only up to the due date**.
2. For those who'd like these recurring tasks to remind them every day, you can now set a reminder for all tasks at once in the **"Time Block Notification" setting in the More menu (Android)** (e.g., a reminder 5 minutes before every task starts).
3. The **red-dot count on the next-day reward box** (earned by completing tasks in the Timetable) could pull your attention away — from now on, **it appears only on days you can open a box**. If you see the box, you can open it right away.
4. This box was made in the hope that you'll **plan your tasks again the next day**, so today's completion reward (the box) can be opened **the next day, after your wake-up time** (it appears after you wake up the next day).
5. A few other bugs have also been fixed.

Thank you.

---

## 2026-07-09 Update Notice

Hello, I'm the app developer.

I wanted to add a little fun to planning your day, so this update introduces a brand-new **Constellation Dex**. The changes are included in **version 1.0.63**, so please update to the latest version.

## Update Details

1. **A Constellation Dex has arrived in the "Timetable" menu** (the star icon ⭐ at the top).
   - Each day you complete tasks in the Timetable, you earn a **reward box that opens the next day**. Complete more tasks and you can earn up to 3 boxes a day.
   - The next day, create or complete one task in the Timetable to unseal your box. Inside you'll find small gifts like personal-record insights and cheer cards — and, with a bit of luck, **a star lands in your very own galaxy**.
   - When enough stars gather in the same constellation, it completes and gets registered in your dex. On Windows, hover over a star in the galaxy to see which constellation it belongs to and its progress.
   - Boxes can only be opened within two days of arriving — so complete just one thing today for tomorrow-you. I built this hoping it makes planning feel a little more fun.
2. This update also includes a few small convenience improvements throughout the app.

Thank you.

---

## 2026-07-06 Update Notice

Hello, I'm the app developer.

This update includes a few convenience improvements. The changes are included in **version 1.0.62**, so please update to the latest version.

## Update Details

1. Fixed an issue in the "Timetable" menu where tasks on past dates could not be edited — they can now be edited.
2. In the "Timetable" menu, when you change your wake-up and bedtime settings, they now apply to the day you set them and every day after it. You can also set the bedtime into the early hours of the next day (before your wake-up time).
3. Improved the "Schedule" menu so that when you change the month, the title — which used to be cut off with "…" — is now shown in full.
4. In the Android app, some bottom menu names were long enough to wrap onto two lines — they now fit on a single line by shortening the labels (e.g., "Schedule" → "Sched.", "Timetable" → "Plan").

Thank you.

---

## 2026-07-05 Update Notice

Hello, I'm the app developer.

This update broadens the "Schedule" view and adds a new weekly view to the Windows "Timetable." The changes are included in **version 1.0.61**, so please update to the latest version.

## Update Details

1. The per-day list below the calendar in the "Schedule" menu now also shows upcoming events beyond today.
2. The "Timetable" menu in the Windows app now includes a weekly timetable view. See your whole week's plan at a glance.
3. Beyond these, I fixed a "recurrence" setting error and improved the mood-selection display in the Diary menu (calendar tab), along with a few other refinements.

Thank you.

---

## 2026-06-11 Update Notice

Hello, I'm the app developer.

For this update I went through the entire app code and fixed a batch of issues that could cause data loss or freeze the screen. The fixes are included in **version 1.0.57**, so please update to the latest version.

## Issues Fixed

- Fixed an issue where, when using two devices (phone and PC), changes made on one device could be overwritten and lost during sync. Changes from both devices are now merged safely.
- Fixed an issue where monthly repeating tasks set to the 29th–31st were skipped entirely in shorter months (like February). They are now created on the last day of that month instead.
- Fixed an issue where importing a backup file failed entirely if even part of the data already existed. Re-importing the same backup no longer causes errors or duplicates.
- Fixed an issue where the update notice screen would silently do nothing if the store app could not be opened — it now shows a message and offers to open the store in your browser instead.
- Fixed an issue where the start button on the welcome screen could stop responding if the setup step failed.
- Fixed an issue where a stray-thought note written on the Pomodoro screen could be lost if you closed the screen right after typing it.
- Fixed an issue where tapping the purchase button quickly several times could trigger duplicate processing.
- Windows: fixed an issue where the routine alarm sound kept playing even after the alarm was dismissed.

Beyond these, I reviewed the whole app and hardened around 50 potential issues, and strengthened privacy protection so personal information is not included in analytics data.

Thank you.

---

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
