# Mifos Summer of Code (MSOC) 2025 - Progress Blog

## 🧑‍💻 Introduction

Hi, I’m **Jilakara Revanth Kumar**, a B.Tech student in Computer Science and Engineering at **RGUKT RK Valley**. I’m passionate about Android development and excited to contribute to **Mifos Mobile Applications** as part of **Mifos Summer of Code (MSOC) 2025**.

As a part of this summer under **MSOC**, I am focusing on **migrating the Mifos Android Client Field Officer Application to Kotlin Multiplatform (KMP) and Compose Multiplatform (CMP)**. This migration will help the app become more modern, maintainable, and scalable across platforms, ultimately improving accessibility and performance for field officers and end users.

This blog will serve as a weekly progress tracker of my contributions, learnings, and challenges throughout the program. I hope it inspires and informs future contributors!

## 📱 My Project for MSOC

The goal of this project is to **migrate the existing Mifos Android Field Officer application to Kotlin Multiplatform (KMP)** while enhancing its **architecture, performance, and maintainability**.

This migration aims to make the app run seamlessly across **Android, iOS, Desktop, and Web**, reducing code duplication and improving the developer experience.

Key aspects of this project include:

- 🔁 Replacing the existing RxJava-based network layer with **`fineract-client-kmp-sdk`** using **Kotlin coroutines** and **Flow**.
- 📲 Introducing **dynamic navigation graphs** based on user roles to support **multiple user types**, not just Field Officers.
- 📡 Implementing **offline sync functionality** for uninterrupted access.
- ✅ Increasing **testing coverage** with unit and integration tests.
- 🚀 Enhancing **CI/CD automation** using GitHub Actions and Fastlane for streamlined Play Store releases.

By the end of this project, the Mifos Android Client will be a **modular, scalable, and cross-platform** solution, delivering a better experience for both developers and users.

👉 _For more details, have a look at my comprehensive proposal submitted as a [GSoC Proposal to Mifos](https://docs.google.com/document/d/1FNdjwGb5TuSHlhU9c36e7Gx1ERgx3xaPfkTysbKuhw8/edit?usp=sharing)._ 

## 🚀 Pre-MSOC Journey

Before officially beginning my Mifos Summer of Code (MSOC) 2025 journey, I actively contributed to the **Mifos Mobile Applications** for over **7 months**. My focus was primarily on:

- Migrating the existing Mifos Android applications to **Kotlin Multiplatform (KMP)**.
- Fixing **UI/UX bugs** and improving **code structure** across modules.

📌 **Highlights:**
- **19 Pull Requests** successfully merged before MSOC.
- Migrated **7 modules** in the `mifos-mobile` repository.
- Contributed to **2 modules** in the legacy `android-client` project.

---

I’m incredibly thankful to the amazing **Mifos community** for their constant support and guidance throughout this journey.

Thanks to Mifos:
- I gained in-depth knowledge of **Kotlin Multiplatform (KMP)**.
- Improved significantly in **Android architecture patterns**, **SOLID principles**, and **clean code practices**.
- Sharpened my **version control** and **collaborative development** skills.

This strong foundation has set me up to confidently take on the challenges of MSOC!


## 📅 Weekly Progress

This section will document my weekly progress throughout the Mifos Summer of Code (MSOC) 2025 journey. Each row summarizes the work done during a specific week, and links to a dedicated README for more in-depth insights.


| Week   | Timeline           | Worked On                                                                                                            | Detailed Explanation       |
|--------|--------------------|----------------------------------------------------------------------------------------------------------------------|-----------------------------|
| Week 0 | May 25 – May 31    | Setup application modules for CMP, Migrated Home Drawer to Compose Multiplatform                                    | [Week 0 Details](./week0.md) |
| Week 1 | June 1 – June 7    | Resolved unauthenticated error, started migrating Collection Sheet, Center, and Document modules (draft PRs); Search module migrated | [Week 1 Details](./week1.md) |
| Week 2 | June 8 – June 14   | Migrated Center, Collection Sheet, and enhanced Settings module; reviewed 5+ module migration PRs                   | [Week 2 Details](./week2.md) |


---
## 📊 My Merged Pull Requests During MSOC

| S.No | Title                                            | JIRA Ticket                                                                          | Pull Request Link                                                         | Week   |
|------|--------------------------------------------------|--------------------------------------------------------------------------------------|---------------------------------------------------------------------------|--------|
| 1    | SetUp Application Modules                        | [MIFOSAC-446](https://mifosforge.jira.com/browse/MIFOSAC-446)                       | [PR #2375](https://github.com/openMF/android-client/pull/2375)           | Week 0 |
| 2    | Home Drawer migrated to CMP                      | [MIFOSAC-447](https://mifosforge.jira.com/browse/MIFOSAC-447)                       | [PR #2387](https://github.com/openMF/android-client/pull/2387)           | Week 0 |
| 3    | Activate module migrated to CMP                  | [MIFOSAC-413](https://mifosforge.jira.com/browse/MIFOSAC-413)                       | [PR #2388](https://github.com/openMF/android-client/pull/2388)           | Week 0 |
| 4    | Settings module migrated to CMP (Co-Authored)    | [MIFOSAC-429](https://mifosforge.jira.com/browse/MIFOSAC-429)                       | [PR #2390](https://github.com/openMF/android-client/pull/2390)           | Week 1 |
| 5    | Resolve UnAuthorized error                       | *No JIRA ticket created*                                                            | [PR #2397](https://github.com/openMF/android-client/pull/2397)           | Week 1 |
| 6    | Search module migrated to CMP                    | [MIFOSAC-428](https://mifosforge.jira.com/browse/MIFOSAC-428)                       | [PR #2399](https://github.com/openMF/android-client/pull/2399)           | Week 1 |
| 7    | Center module migrated to CMP                    | [MIFOSAC-415](https://mifosforge.jira.com/browse/MIFOSAC-415)                       | [PR #2391](https://github.com/openMF/android-client/pull/2391)           | Week 2 |
| 8    | Collection Sheet module migrated to CMP          | [MIFOSAC-418](https://mifosforge.jira.com/browse/MIFOSAC-418)                       | [PR #2396](https://github.com/openMF/android-client/pull/2396)           | Week 2 |
| 9    | Settings Module Enhancements (Theme Change and Clean Up) | [MIFOSAC-450](https://mifosforge.jira.com/browse/MIFOSAC-450)              | [PR #2403](https://github.com/openMF/android-client/pull/2403)           | Week 2 |


---


