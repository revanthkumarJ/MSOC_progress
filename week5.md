## 🗓️ Week 5: June 29 – July 5

### 🧩 Overview
This week marked the beginning of the second month of MSOC. I focused on addressing critical bugs, module removal, and significant refactors. I raised and merged multiple PRs targeting client image issues, savings account errors, and further modularization improvements using Compose libraries. In addition, I actively reviewed multiple PRs across **android-client**, **mifos-mobile**, and **mobile-wallet** repositories to support fellow contributors and maintain high code quality.

---

### ✅ Tasks Completed

- 🚀 **PRs Raised & Merged**
  - 🖼️ **Fix: Client Image (Edit, Delete Dialog)**  
    - [MIFOSAC-480](https://mifosforge.jira.com/browse/MIFOSAC-480)  
    - [MIFOSAC-483](https://mifosforge.jira.com/browse/MIFOSAC-483)  
    - [PR #2421](https://github.com/openMF/android-client/pull/2421)
  - 🗂️ **Feat: Removed mifosng-android module**  
    - [MIFOSAC-484](https://mifosforge.jira.com/browse/MIFOSAC-484)  
    - [PR #2422](https://github.com/openMF/android-client/pull/2422)
  - 🏦 **Fix: SavingsAccount Withdrawal & Deposit Screens (Serializable Error)**  
    - [MIFOSAC-485](https://mifosforge.jira.com/browse/MIFOSAC-485)  
    - [PR #2423](https://github.com/openMF/android-client/pull/2423)
  - ✍️ **Feat: Refactor SignatureScreen to CommonMain using Compose-Signature Library**  
    - [MIFOSAC-482](https://mifosforge.jira.com/browse/MIFOSAC-482)  
    - [PR #2425](https://github.com/openMF/android-client/pull/2425)

---

### 🔍 Code Reviews & Collaboration

Reviewed PRs by fellow contributors:  
- [#2427](https://github.com/openMF/android-client/pull/2427): Fix: cmp-desktop does not build  
- [#2424](https://github.com/openMF/android-client/pull/2424): Fix(feature:client): fix silent creation failure and state/snackbar issues for client identifier  
- [#2850](https://github.com/openMF/mifos-mobile/pull/2850): Feat: Onboarding language screen UI and ViewModel  
- [#2851](https://github.com/openMF/mifos-mobile/pull/2851): Sign in UI and ViewModel  
- [#2852](https://github.com/openMF/mifos-mobile/pull/2852): Feat: Status component  
- [#1874](https://github.com/openMF/mobile-wallet/pull/1874): Refactor MakeTransferScreen to improve account selection using BottomSheetScaffold  
- [#1875](https://github.com/openMF/mobile-wallet/pull/1875): Fix TransferDetail deserialization error by updating transferDate type to String  
- [#1876](https://github.com/openMF/mobile-wallet/pull/1876): Fix crash when app is opened without internet after passcode entry  
- [#1877](https://github.com/openMF/mobile-wallet/pull/1877): Setup Postman collection for Mifos Pay self-service API checks
