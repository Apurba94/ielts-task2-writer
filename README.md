# Task 2 Essay Writer

Write a Task 2 essay of at least 250 words in 40 minutes, with original prompts of every type.

Part of the [IELTS Study Suite](https://github.com/Apurba94/ielts-study-suite): 100 free study apps for IELTS. This one is for the IELTS Academic and General Training test. It works offline, as a Windows program or in the browser.

## Download and run

- **Windows:** download `Task 2 Essay Writer.exe` from the [latest release](https://github.com/Apurba94/ielts-task2-writer/releases/latest) and open it. Nothing to install. It opens in its own window and saves your progress in your user folder.
- **Browser:** open it online in the suite's web edition at https://ielts-study-suite.vercel.app/apps/ielts-task2-writer/ . Progress stays in that browser.
- **From source:** `python launcher.py` (Python 3.10 or later, no packages needed).

## What it does

Writing Task 2 is an essay of at least 250 words, with about 40 minutes for it, and it counts for more than Task 1. This app has 48 original prompts across the five common types: opinion, discuss both views, problem and solution, advantages and disadvantages, and two-part questions, with feedback on length, paragraphs and linking, and a checklist for each type.

Sections: Write, Progress, About.

## How to use it

1. Choose a type or topic, or take a random prompt.
2. Plan for five minutes (the Task 2 Planner helps), then write. The 40-minute timer is optional.
3. Read the feedback and tick the checklist. The feedback counts what a program can count; it is not a band.

## Good to know

- All questions, passages, recordings and definitions were written for this suite. None are official IELTS questions. For official practice, use the materials on ielts.org and from the test partners.
- It follows IELTS as delivered on computer in 2026. Formats change, so check ielts.org before your test.
- Listening uses the voices installed on your computer, which sound less natural than real test recordings.
- Feedback on writing and speaking counts what a program can count honestly, such as length and linking words. It is not an IELTS band score. Band conversions for Listening and Reading are approximate.
- Not endorsed by or affiliated with the British Council, IDP or Cambridge University Press & Assessment. IELTS is a registered trademark of its owners.

## For developers

The app is plain HTML and JavaScript in `web/`, run by a small Python launcher that serves it on 127.0.0.1 only and needs a secret token for saving. Tests: `node --test "tests/*.test.js"` (29 tests) and `python -m unittest discover -s tests`. Build the .exe with `python build_exe.py`.

Built with AI assistance (Claude Code). MIT licence. By JANIN A APURBA.
