# Coding Companion for RevolutionEHR

A browser extension for eye-care practices that use RevolutionEHR. Build the codes for an exam type once, then add them to an encounter in one step instead of typing them in each time.

It is an independent tool by Dr. Earls Optometry Tools, in a private beta. It is not made by, endorsed by or affiliated with RevolutionEHR.

## What it does

A **Package** holds the diagnoses (ICD-10), the plan text under each diagnosis, and the services (CPT codes) with their diagnoses attached, for an exam type such as "Glaucoma Evaluation" or "Dry Eye Evaluation". Three parts work together:

- **Package Library**: a browser tab listing your Packages. Create, edit, import and export them here.
- **Package Builder**: a browser tab for building one Package. Search the full ICD-10 list by words in any order (including abbreviations like ARMD or POAG), search your practice's own service list, write plan lines with fill-in questions, and attach each diagnosis to the codes it supports.
- **Coding Companion**: a sidebar inside RevolutionEHR during an encounter. Tick the Packages you want, review every code in Coding Preview, then apply them. It also has a quick search for adding a single diagnosis by itself.

It only adds codes: nothing already on the encounter is deleted or changed, and nothing is written until you confirm.

## Download

For beta testers, on Windows with Microsoft Edge: [Download the Setup program](https://github.com/drnickearls/coding-companion/releases/latest/download/Coding-Companion-Setup.exe) (always the newest version), and read the [Beta Guide (PDF)](https://github.com/drnickearls/coding-companion/releases/latest/download/Coding.Companion.Beta.Guide.pdf) first. Earlier versions are on the [releases page](https://github.com/drnickearls/coding-companion/releases).

## FAQ

**If I make a new Package or change one, does it apply to anyone else?**

No. Packages are saved in your browser on your computer, so changes are only seen by you. Someone on another computer, another Windows account, or another browser or browser profile won't see them. Anyone using the same browser profile as you will. To share Packages, use Export and Import in the Package Library.

**Is this extension HIPAA compliant? Does it share patient data with anyone?**

It doesn't share any data with anyone, including its developer: the extension makes no network requests of its own. Your Packages stay in your browser, contain codes and plan text rather than patient information, and no one else can see them unless you export and share the file.

It also never reads who the patient is. From the page address it takes only the encounter ID, and it reads only what is already on the open encounter (its diagnoses, services and plan items) to avoid adding anything twice, without keeping or sending it. So it has no way to connect a patient with a diagnosis.

Whether a practice's use of any software meets HIPAA is for the practice to decide. The details are in the [privacy statement](https://drnickearls.github.io/coding-companion/privacy.html).

More: [front page](https://drnickearls.github.io/coding-companion/) · [FAQ page](https://drnickearls.github.io/coding-companion/faq.html) · [privacy statement](https://drnickearls.github.io/coding-companion/privacy.html)

Contact: [drnickearls@gmail.com](mailto:drnickearls@gmail.com). The extension's source code is not published here.
