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
| Week 3 | June 15 – June 21  | Migrated Document Module, Co-Authored Loan Module; reviewed 2 PRs                                                    | [Week 3 Details](./week3.md) |
| Week 4 | June 22 – June 28  | Finalized Report Module Migration, Cleaned Up Loan & Group Modules, Reviewed 8+ PRs                                 | [Week 4 Details](./week4.md) |
| Week 5 | June 29 – July 5   | Addressed Client Image Fixes, Removed unnecessary Module, Refactored SignatureScreen, Reviewed 9+ PRs                | [Week 5 Details](./week5.md) |
| Week 6 | July 6 – July 12   | Enhanced Create Client to align with development branch, fixed Create Loan API, applied Survey Screens fixes         | [Week 6 Details](./week6.md) |
| Week 7 | July 13 – July 19  | No major contributions done; no PR merged                                                                            | [Week 7 Details](./week7.md)                         |
| Week 8 | July 20 – July 26  | Implemented Transaction Screen item UI, fixed Customer Account validation, developed Charges Screen UI               | [Week 8 Details](./week8.md) |
| Week 9 | July 27 – Aug 2    | Added Charges paid/unpaid views, Payfrom Dropdown Card UI, username-to-email change, Transaction Screen & Filter UI, updated progress bars & states, QR code binding, API updates, Transaction empty UI fixes, loan account filter fixes, new Make Transfer UI | [Week 9 Details](./week9.md) |
| Week 10| Aug 3 – Aug 9      | Added Beneficiary new UI, Beneficiary details screen, removed Withdraw option from savings account details, Transaction Filter fixes, Beneficiary list filters, navigation setup from settings, new Help, About Us, App Info, Authorization Passcode, and Password UIs, fixed FAQ navigation | [Week 10 Details](./week10.md) |
| Week 11| Aug 10 – Aug 16    | Commented out unused settings options, added localization strings for Home module                                   | [Week 11 Details](./week11.md) |


---
## 📊 My Merged Pull Requests During MSOC

| S.No | Week   | Title                                            | JIRA Ticket                                                                          | Pull Request Link                                                         |
|------|--------|--------------------------------------------------|--------------------------------------------------------------------------------------|---------------------------------------------------------------------------|
| 1    | Week 0 | SetUp Application Modules                        | [MIFOSAC-446](https://mifosforge.jira.com/browse/MIFOSAC-446)                       | [PR #2375](https://github.com/openMF/android-client/pull/2375)           |
| 2    |        | Home Drawer migrated to CMP                      | [MIFOSAC-447](https://mifosforge.jira.com/browse/MIFOSAC-447)                       | [PR #2387](https://github.com/openMF/android-client/pull/2387)           |
| 3    |        | Activate module migrated to CMP                  | [MIFOSAC-413](https://mifosforge.jira.com/browse/MIFOSAC-413)                       | [PR #2388](https://github.com/openMF/android-client/pull/2388)           |
|     |  June 2025  | 1st Month of Msoc    |                        |           |
| 4    | Week 1 | Settings module migrated to CMP (Co-Authored)    | [MIFOSAC-429](https://mifosforge.jira.com/browse/MIFOSAC-429)                       | [PR #2390](https://github.com/openMF/android-client/pull/2390)           |
| 5    |        | Resolve UnAuthorized error                       | *No JIRA ticket created*                                                            | [PR #2397](https://github.com/openMF/android-client/pull/2397)           |
| 6    |        | Search module migrated to CMP                    | [MIFOSAC-428](https://mifosforge.jira.com/browse/MIFOSAC-428)                       | [PR #2399](https://github.com/openMF/android-client/pull/2399)           |
| 7    | Week 2 | Center module migrated to CMP                    | [MIFOSAC-415](https://mifosforge.jira.com/browse/MIFOSAC-415)                       | [PR #2391](https://github.com/openMF/android-client/pull/2391)           |
| 8    |        | Collection Sheet module migrated to CMP          | [MIFOSAC-418](https://mifosforge.jira.com/browse/MIFOSAC-418)                       | [PR #2396](https://github.com/openMF/android-client/pull/2396)           |
| 9    |        | Settings Module Enhancements (Theme Change and Clean Up) | [MIFOSAC-450](https://mifosforge.jira.com/browse/MIFOSAC-450)              | [PR #2403](https://github.com/openMF/android-client/pull/2403)           |
| 10   | Week 3 | Document Module Migration                        | [MIFOSAC-420](https://mifosforge.jira.com/browse/MIFOSAC-420)                       | [PR #2402](https://github.com/openMF/android-client/pull/2402)           |
| 11   |        | Loan Module Migration (Co-Authored)              | [MIFOSAC-422](https://mifosforge.jira.com/browse/MIFOSAC-422)                       | [PR #2404](https://github.com/openMF/android-client/pull/2404)           |
| 12   | Week 4 | Report Module Migration (Co-Authored)            | [MIFOSAC-426](https://mifosforge.jira.com/browse/MIFOSAC-426)                       | [PR #2392](https://github.com/openMF/android-client/pull/2392)           |
| 13   |        | fix : image rendering in client and payment screen (Co-Authored)            | [MIFOSAC-455](https://mifosforge.jira.com/browse/MIFOSAC-455)                       | [PR #2410](https://github.com/openMF/android-client/pull/2410)           |
| 14   |        | fix : Loan Module clean up (Api , Viewmodel )            | [MIFOSAC-456](https://mifosforge.jira.com/browse/MIFOSAC-456)                       | [PR #2411](https://github.com/openMF/android-client/pull/2411)           |
| 15   |        | fix : Group Module (api), added Navigations in Feature Nav Host            | [MIFOSAC-475](https://mifosforge.jira.com/browse/MIFOSAC-475)                       | [PR #2413](https://github.com/openMF/android-client/pull/2413)           |
| 16   |        | fix : UpdateServerConfig (navigation,ui)            | [MIFOSAC-476](https://mifosforge.jira.com/browse/MIFOSAC-476)                       | [PR #2414](https://github.com/openMF/android-client/pull/2414)           |
| 17   |        | fix : Replace Result With DataState in core:dataStore           | [MIFOSAC-477](https://mifosforge.jira.com/browse/MIFOSAC-477)                       | [PR #2416](https://github.com/openMF/android-client/pull/2416)           |
| 18   |        | fix : Create Client           | [MIFOSAC-469](https://mifosforge.jira.com/browse/MIFOSAC-469)                       | [PR #2420](https://github.com/openMF/android-client/pull/2420)           |
| 19   | Week 5       | fix : Client Image (Edit , Delete Dialog)           | [MIFOSAC-480](https://mifosforge.jira.com/browse/MIFOSAC-480) <br> [MIFOSAC-483](https://mifosforge.jira.com/browse/MIFOSAC-483)                       | [PR #2421](https://github.com/openMF/android-client/pull/2421)           |
| 20   |        | feat : Removed mifosng-android module           | [MIFOSAC-484](https://mifosforge.jira.com/browse/MIFOSAC-484)                       | [PR #2422](https://github.com/openMF/android-client/pull/2422)           |
|    | July 2025       | Second Month of MSOC           |                      |           |
| 21   |        | fix : SavingsAccount With Drawl and Saving Account Deposit screens not loading Serializable error           | [MIFOSAC-485](https://mifosforge.jira.com/browse/MIFOSAC-485)                       | [PR #2423](https://github.com/openMF/android-client/pull/2423)           |
| 22   |        | feat: Refactor SignatureScreen to CommonMain using Compose-Signature Library           | [MIFOSAC-482](https://mifosforge.jira.com/browse/MIFOSAC-482)                       | [PR #2425](https://github.com/openMF/android-client/pull/2425)           |
| 23   | Week 6       | fix : Enhance Create Client to Align with development Branch            | [MIFOSAC-486](https://mifosforge.jira.com/browse/MIFOSAC-486)                       | [PR #2426](https://github.com/openMF/android-client/pull/2426)           |
| 24   |        | fix: Create loan API fix            | [MIFOSAC-473](https://mifosforge.jira.com/browse/MIFOSAC-473)                       | [PR #2429](https://github.com/openMF/android-client/pull/2429)           |
| 25   |       | fix : Survey Screens Fixes          | [MIFOSAC-466](https://mifosforge.jira.com/browse/MIFOSAC-466) <br> [MIFOSAC-467](https://mifosforge.jira.com/browse/MIFOSAC-467) <br> [MIFOSAC-468](https://mifosforge.jira.com/browse/MIFOSAC-468)                       | [PR #2436](https://github.com/openMF/android-client/pull/2436)           |
| 26   | Week 8      |feat : Transaction Screen item UI        |  [MM-284](https://mifosforge.jira.com/browse/MM-284)                       | [PR #2864](https://github.com/openMF/mifos-mobile/pull/2864)           |
| 27   |       |fix: Customer Account Validation        |  No Jira Ticket Created                      | [PR #2866](https://github.com/openMF/mifos-mobile/pull/2866)           |
| 28   |       |feat : Charges Screen UI       |  [MM-280](https://mifosforge.jira.com/browse/MM-280)                       | [PR #2863](https://github.com/openMF/mifos-mobile/pull/2863)           |
| 29   | Week 9 |feat : Charges paid and unpaid views       |  [MM-287](https://mifosforge.jira.com/browse/MM-287)                       | [PR #2871](https://github.com/openMF/mifos-mobile/pull/2871)           |
| 30   |        |feat: Payfrom DropDown Card UI             |  [MM-291](https://mifosforge.jira.com/browse/MM-291)                       | [PR #2873](https://github.com/openMF/mifos-mobile/pull/2873)           |
| 31   |        |fix: changed username to email             |  No Jira Ticket Created                      | [PR #2876](https://github.com/openMF/mifos-mobile/pull/2876)           |
|    | August 2025       | Third Month of MSOC           |                      |           |
| 32   |        |feat: Transaction screen UI             |  [MM-278](https://mifosforge.jira.com/browse/MM-278)                     | [PR #2874](https://github.com/openMF/mifos-mobile/pull/2874)           |
| 33   |        |feat: Transaction screen Filter UI            |  [MM-288](https://mifosforge.jira.com/browse/MM-288)                     | [PR #2878](https://github.com/openMF/mifos-mobile/pull/2878)           |
| 34   |        |updated progess bars and states             |  [MM-296](https://mifosforge.jira.com/browse/MM-296)                     | [PR #2881](https://github.com/openMF/mifos-mobile/pull/2881)           |
| 35   |        |fix : Make Filter Checkbox Title Clickable Horizontally (Not Just Checkbox)             |  [MM-297](https://mifosforge.jira.com/browse/MM-297)                     | [PR #2882](https://github.com/openMF/mifos-mobile/pull/2882)           |
| 36   |        |feat : bind qr code with savings and loan details screens             |  [MM-302](https://mifosforge.jira.com/browse/MM-302)                     | [PR #2887](https://github.com/openMF/mifos-mobile/pull/2887)           |
| 37   |        |fix : changed apis to self             |  [MM-315](https://mifosforge.jira.com/browse/MM-315)                     | [PR #2891](https://github.com/openMF/mifos-mobile/pull/2891)           |
| 38   |        |fix : transaction_screen empty ui update             |  [MM-300](https://mifosforge.jira.com/browse/MM-300)                     | [PR #2894](https://github.com/openMF/mifos-mobile/pull/2894)           |
| 39   |        |fix: loan account Filter logic and states             |  [MM-305](https://mifosforge.jira.com/browse/MM-305)                     | [PR #2896](https://github.com/openMF/mifos-mobile/pull/2896)           |
| 40   |        |feat: new ui for make transfer             |  [MM-324](https://mifosforge.jira.com/browse/MM-324)<br>[MM-292](https://mifosforge.jira.com/browse/MM-292)                     | [PR #2893](https://github.com/openMF/mifos-mobile/pull/2893)           |
| 41   | Week 10       |feat : ADD Beneficiary new UI             |  [MM-322](https://mifosforge.jira.com/browse/MM-322)                     | [PR #2899](https://github.com/openMF/mifos-mobile/pull/2899)           |
| 42   |      |feat: beneficiary details screen             |  [MM-321](https://mifosforge.jira.com/browse/MM-321) <br> [MM-348](https://mifosforge.jira.com/browse/MM-348)                     | [PR #2905](https://github.com/openMF/mifos-mobile/pull/2905)           |
| 43   |        |fix: Remove Withdraw option from saving account details             |  [MM-335](https://mifosforge.jira.com/browse/MM-335)                     | [PR #2907](https://github.com/openMF/mifos-mobile/pull/2907)           |
| 44   |        |fix : Transaction Filter             |  [MM-334](https://mifosforge.jira.com/browse/MM-334)                     | [PR #2908](https://github.com/openMF/mifos-mobile/pull/2908)           |
| 45   |        |feat : Beneficiary List filters            |  [MM-336](https://mifosforge.jira.com/browse/MM-336)                     | [PR #2909](https://github.com/openMF/mifos-mobile/pull/2909)           |
| 46   |        |feat: navigation setup from settings screen and Help Screen UI            |  [MM-347](https://mifosforge.jira.com/browse/MM-347)                     | [PR #2911](https://github.com/openMF/mifos-mobile/pull/2911)           |
| 47   |        |feat: About us New Ui           |  [MM-343](https://mifosforge.jira.com/browse/MM-343)                     | [PR #2912](https://github.com/openMF/mifos-mobile/pull/2912)           |
| 48   |        |feat: App info New UI           |  [MM-344](https://mifosforge.jira.com/browse/MM-344)                     | [PR #2913](https://github.com/openMF/mifos-mobile/pull/2913)           |
| 49   |        |feat: Authorization Passcode New UI           |  [MM-340](https://mifosforge.jira.com/browse/MM-340)                     | [PR #2915](https://github.com/openMF/mifos-mobile/pull/2915)          |
| 50   |        |feat : Password screen UI           |  [MM-339](https://mifosforge.jira.com/browse/MM-339)                     | [PR #2920](https://github.com/openMF/mifos-mobile/pull/2920)          |
| 51   |        |fix : Home Screen Faq still navigating to old ui screen           |  [MM-353](https://mifosforge.jira.com/browse/MM-353)                     | [PR #2921](https://github.com/openMF/mifos-mobile/pull/2921)          |
| 52   | week 11       |feat: Comment settings unused options           |  [MM-338](https://mifosforge.jira.com/browse/MM-338)                     | [PR #2925](https://github.com/openMF/mifos-mobile/pull/2925)          |
| 53   |        |feat: localisation strings for home module           |  [MM-361](https://mifosforge.jira.com/browse/MM-361)                     | [PR #2927](https://github.com/openMF/mifos-mobile/pull/2927)          |
| 54   |  week 12      |chore: clean up unused dependenciese           |  [MIFOSAC-343](https://mifosforge.jira.com/browse/MIFOSAC-343)                     | [PR #2453](https://github.com/openMF/android-client/pull/2453)          |
| 55   |        |fix : enable previews in all modules           |  [MIFOSAC-511](https://mifosforge.jira.com/browse/MIFOSAC-511)                     | [PR #2454](https://github.com/openMF/android-client/pull/2454)          |
| 56   |        |feat: Add DesignToken file to adapt new ui screens          |  [MIFOSAC-515](https://mifosforge.jira.com/browse/MIFOSAC-515)                     | [PR #2455](https://github.com/openMF/android-client/pull/2455)          |
| 57   |        |feat : added listing components ui          |  [MIFOSAC-513](https://mifosforge.jira.com/browse/MIFOSAC-513)                     | [PR #2456](https://github.com/openMF/android-client/pull/2456)          |
| 58   |        |feat : added new ui components         |  [MIFOSAC-516](https://mifosforge.jira.com/browse/MIFOSAC-516)                     | [PR #2457](https://github.com/openMF/android-client/pull/2457)          |
| 59   |        |feat : Client List New U         |  [MIFOSAC-510](https://mifosforge.jira.com/browse/MIFOSAC-510)                     | [PR #2458](https://github.com/openMF/android-client/pull/2458)          |
| 60   |        |feat : Client Profile UI          |  [MIFOSAC-519](https://mifosforge.jira.com/browse/MIFOSAC-519)                     | [PR #2462](https://github.com/openMF/android-client/pull/2462)          |
| 61   |        |feat: Client Profile Details UI          |  [MIFOSAC-520](https://mifosforge.jira.com/browse/MIFOSAC-520)                     | [PR #2463](https://github.com/openMF/android-client/pull/2463)   |
| 62   | week 13 |feat :update client photo flow          |  [MIFOSAC-522](https://mifosforge.jira.com/browse/MIFOSAC-522)                     | [PR #2464](https://github.com/openMF/android-client/pull/2464)   |
| 63   |     |feat: Assign and Unassign Staff UI          |  [MIFOSAC-565](https://mifosforge.jira.com/browse/MIFOSAC-565)                     | [PR #2465](https://github.com/openMF/android-client/pull/2465)   |
| 64   |     |feat: Client Transfer New UI Screens          |  [MIFOSAC-564](https://mifosforge.jira.com/browse/MIFOSAC-564)                   | [PR #2466](https://github.com/openMF/android-client/pull/2466)   |
| 65   |     |feat: Update Default Account New Screens          |  [MIFOSAC-568](https://mifosforge.jira.com/browse/MIFOSAC-568)               | [PR #2467](https://github.com/openMF/android-client/pull/2467)   |
| 66   |     |feat : Client Closure New UI Screens          |  [MIFOSAC-563](https://mifosforge.jira.com/browse/MIFOSAC-563)                   | [PR #2468](https://github.com/openMF/android-client/pull/2468)   |
| 67   |     |feat: Client Collateral New UI Screens          |  [MIFOSAC-567](https://mifosforge.jira.com/browse/MIFOSAC-567)                 | [PR #2469](https://github.com/openMF/android-client/pull/2469)   |
| 68   |     |feat : Stepper Component           |  [MIFOSAC-526](https://mifosforge.jira.com/browse/MIFOSAC-526)                 | [PR #2473](https://github.com/openMF/android-client/pull/2473)   |
| 69   |     |fix: Firebase distribution           |  No Jira Ticket Created                 | [PR #2474](https://github.com/openMF/android-client/pull/2474)   |
| 70   |     |fix: firebase distribution           |   No Jira Ticket Created                 | [PR #2478](https://github.com/openMF/android-client/pull/2478)   |
| 71   | week 14     |feat: Migrate Navigation to Type Safe Navigation           |  [MIFOSAC-583](https://mifosforge.jira.com/browse/MIFOSAC-583)                 | [PR #2476](https://github.com/openMF/android-client/pull/2476)   |
| 72   |     |feat: navigation bread crumbs           |  [MIFOSAC-580](https://mifosforge.jira.com/browse/MIFOSAC-580)                 | [PR #2487](https://github.com/openMF/android-client/pull/2487)   |
| 73   |     |feat:New Loan Account – Details Step Page           |  [MIFOSAC-528](https://mifosforge.jira.com/browse/MIFOSAC-528)                 | [PR #2491](https://github.com/openMF/android-client/pull/2491)   |
| 74   |     |feat:New Loan Account – Loan terms Page           |  [MIFOSAC-529](https://mifosforge.jira.com/browse/MIFOSAC-529)                 | [PR #2494](https://github.com/openMF/android-client/pull/2494)   |
| 75   |     |feat: Compose Preview Files            |  [MIFOSAC-591](https://mifosforge.jira.com/browse/MIFOSAC-591)                 | [PR #2496](https://github.com/openMF/android-client/pull/2496)   |
| 76   | Week 15    |feat : New Loan Account – Charges Step Implementation            |  [MIFOSAC-525](https://mifosforge.jira.com/browse/MIFOSAC-525)                 | [PR #2497](https://github.com/openMF/android-client/pull/2497)   |
| 77   |  |fix : Updated Review Transfer bottomSheet            |  [MW-308](https://mifosforge.jira.com/browse/MW-308)                 | [PR #1923](https://github.com/openMF/mobile-wallet/pull/1923)   |
| 78   |        |feat : send money flow change            |  [MW-313](https://mifosforge.jira.com/browse/MW-313)<br>[MW-314](https://mifosforge.jira.com/browse/MW-314) <br>  [MW-315](https://mifosforge.jira.com/browse/MW-315)                  | [PR #1926](https://github.com/openMF/mobile-wallet/pull/1926)           |
