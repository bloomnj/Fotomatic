# Fotomatic Landing Page

Fotomatic an offsite coding projected offered by Codecademy for their Full Stack Developer and Web-adjacent development tracks.  You are tasked with fixing a broken site according to a provided design spec.  In addition to fixing a Desktop version of the page, you must also fix the responsive Tablet and Mobile versions of the page as well.  This is a somewhat infamous project for a number of reasons.  The design spec, while detailed for the Desktop requirements, contains mistakes (including a pretty glaring copy/paste error) and ambiguities in the Tablet and Mobile sections.  The solution you can download is incomplete.  Finally, there used to be a Fotomatic forum you could go to if you had any questions.  This forum no longer exists.

Despite these drawbacks, I consider the Fotomatic project to be one of Codecademy's best projects.  Why?  It simulates real issues you will encounter on an actual dev team.  Consider the drawbacks in respect to a corporate dev team that might inherit this project from another team --

* The design spec was made by a web designer who may not be familiar with how the page actually needs to be coded, resulting in conflicting requirements.
* The broken code you receive could have been a first pass by a developer on another team that got reassigned to another project or left the company.   Now, there's no one left to explain why the code is the way it is.
* On that same note, there may have been a company reorg, so the collective knowledge of how this page was made is lost to time (in the case of the Fotomatic forum no longer being available).
* The CSS is so broken you might consider just rewriting it from the ground up, but what if this broken CSS addresses design requirements made in preivous Sprints and are not reflected in the current design doc?
* Given the ambiguities and conflicting requirements, how do you implement a solution that is clean for future development, while also staying true to the design spec?
* In the case where you must diverge from the design spec, how would you defend this change when the web designer asks about it?

These are real issues developers face on a day-to-day basis.  I can't imagine a better project to give to a student who is considering a career in software development.  

This project contains a repaired version of the Fotomatic landing page. The original page was visually broken because the main stylesheet was not linked, some image paths were incorrect, and several layout selectors did not match the HTML structure.

## What was fixed

- Reviewed and cleaned up the responsive layout for desktop, tablet, and mobile views.
- Improved the header and navigation structure so product detail, About us, and follow links display correctly across breakpoints.
- Ensured the sign-up / waiting list CTA section is visible and legible on smaller screens.
- Verified feature and filter images scale responsively using fluid image containers.
- Confirmed footer and fixed header spacing works with the page content.

## Project structure

- `index.html` — main landing page markup.
- `resources/css/reset.css` — base reset styles.
- `resources/css/style.css` — page styling and responsive rules.
- `resources/images/` — image assets used throughout the landing page.

## Notes

This respository contains both the original broken code (on a branch named "broken") and my fixes (in the "main" and "fixed") branches respectively.

## Demo

You can access a working demo of the fixes for Fotomatic at https://fotomatic.suntheory.net