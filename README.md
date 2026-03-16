# portal-help-pages-my-account COP

*description of the COP*

**COP timeframe** 2026-03-02 - 2026-06-08

## Overview

This repository was created via the **Design Assistant**.  
It contains the template files and in-scope pages needed to get started.

GitHub Pages: [https://cra-proto.github.io/portal-help-pages-my-account](https://cra-proto.github.io/portal-help-pages-my-account)

---
## Update procedures

Add information on how to manage your repo here.

---
## Design phase roadmap:

- [x] Initial content inventory and repo setup
- [ ] Prototype: co-design navigation and content
- [ ] SME review and accuracy check
- [ ] Validation usability testing (including accessibility review)
- [ ] Refine prototype (if required)
- [ ] Spot check usability (if required)

**Updated:**  2026-03-16

## Information Architecture
```mermaid
flowchart TD;
    node1(Canada.ca)
    node2(Canada Revenue Agency #40;CRA#41;)
    node3(CRA Newsroom)
    node4(Get answers about your tax and benefit information online at the CRA – it’s easy and quick)
    node5(Sign in to your CRA account)
    node6(Help with using your CRA account)
    node7(CRA account help – CRA account availability)
    node8(About My Account)
    node9(About My Account - Services in My Account)
    node10(System maintenance details)
    node11(Personal Information Collection Statement)
    node12(Provincial partner)
    node13(Taxes)
    node14(Digital services)
    node15(Digital services for individuals)
    node16(My Account for individuals – CRA sign-in)
    node17(5. Submit document)
    node18(My Account important notices)
    node19(Application cancelled #40;BOA.ex1#41;)
    node20(Application in process #40;BOA.ex3#41;)
    node21(Authorize my representative)
    node22(Pre-authorized Instalment Payment Plan)
    node23(Cancel application #40;BOA.e7#41;)
    node24(Change marital status - Review)
    node25(Change my marital status)
    node26(Help with My Account)
    node27(Help with Change my marital status)
    node28(Help with the TFSA Contribution Page)
    node29(Uncashed cheques help page)
    node30(Identification of spouse or common-law partner - Review)
    node31(Identification of spouse or common-law partner)
    node32(Individual income tax information)
    node33(Direct deposit help page)
    node34(Name of spouse or common-law partner - Review)
    node35(Name of spouse or common-law partner)
    node36(Email notifications for individuals)
    node37(Submit Documents)
    node38(Update marital status #40;BOA.e2a#41;)
    node39(Untitled)
    node40(Residency for spouse or common-law partner)
    node41(Help opening a non-resident tax account)
    node42(Progress tracker)
    node1 --x node2
    node2 --> node3
    node3 --x node4
    node2 --> node5
    node5 --> node6
    node6 --> node7
    node6 --> node8
    node8 --> node9
    node5 --x node10
    node5 --x node11
    node5 --> node12
    node1 --> node13
    node13 --x node14
    node14 --> node15
    node15 --> node16
    node16 --x node17
    node16 --x node18
    node16 --x node19
    node16 --x node20
    node16 --x node21
    node16 --x node22
    node16 --x node23
    node16 --x node24
    node16 --x node25
    node16 --x node26
    node16 --x node27
    node16 --x node28
    node16 --x node29
    node16 --x node30
    node16 --x node31
    node16 --x node32
    node16 --x node33
    node16 --x node34
    node16 --x node35
    node16 --x node36
    node16 --x node37
    node16 --x node38
    node16 --x node39
    node16 --x node40
    node14 --x node41
    node14 --x node42
    click node1 "https://www.canada.ca/en.html" _blank
    click node2 "https://www.canada.ca/en/revenue-agency.html" _blank
    click node3 "https://www.canada.ca/en/revenue-agency/news/newsroom.html" _blank
    click node4 "https://www.canada.ca/en/revenue-agency/news/newsroom/tax-tips/tax-tips-2015/answers-about-your-tax-benefit-information-online-cra-easy-quick.html" _blank
    click node5 "https://www.canada.ca/en/revenue-agency/services/e-services/cra-login-services.html" _blank
    click node6 "https://www.canada.ca/en/revenue-agency/services/e-services/cra-login-services/help-cra-sign-in-services.html" _blank
    click node7 "https://www.canada.ca/en/revenue-agency/services/e-services/cra-login-services/help-cra-sign-in-services/sign-in-services-availability.html" _blank
    click node8 "https://www.canada.ca/en/revenue-agency/services/e-services/digital-services-individuals/account-individuals/about-account.html" _blank
    click node9 "https://www.canada.ca/en/revenue-agency/services/e-services/digital-services-individuals/account-individuals/about-account/services-my-account.html" _blank
    click node10 "https://www.canada.ca/en/revenue-agency/services/e-services/cra-login-services/outage-details.html" _blank
    click node11 "https://www.canada.ca/en/revenue-agency/services/e-services/cra-login-services/personal-information-collection-statement.html" _blank
    click node12 "https://www.canada.ca/en/revenue-agency/services/e-services/digital-services-individuals/account-individuals/provincial-partner.html" _blank
    click node13 "https://www.canada.ca/en/services/taxes.html" _blank
    click node14 "https://www.canada.ca/en/revenue-agency/services/e-services.html" _blank
    click node15 "https://www.canada.ca/en/revenue-agency/services/e-services/digital-services-individuals.html" _blank
    click node16 "https://www.canada.ca/en/revenue-agency/services/e-services/digital-services-individuals/account-individuals.html" _blank
    click node17 "https://www.canada.ca/en/revenue-agency/services/e-services/digital-services-individuals/account-individuals/5-submit-document.html" _blank
    click node18 "https://www.canada.ca/en/revenue-agency/services/e-services/digital-services-individuals/account-individuals/account-important-notices.html" _blank
    click node19 "https://www.canada.ca/en/revenue-agency/services/e-services/digital-services-individuals/account-individuals/application-cancelled-ex1.html" _blank
    click node20 "https://www.canada.ca/en/revenue-agency/services/e-services/digital-services-individuals/account-individuals/application-process-ex3.html" _blank
    click node21 "https://www.canada.ca/en/revenue-agency/services/e-services/digital-services-individuals/account-individuals/authorize-representative.html" _blank
    click node22 "https://www.canada.ca/en/revenue-agency/services/e-services/digital-services-individuals/account-individuals/authorized-instalment-payment-plan.html" _blank
    click node23 "https://www.canada.ca/en/revenue-agency/services/e-services/digital-services-individuals/account-individuals/cancel-application-e7.html" _blank
    click node24 "https://www.canada.ca/en/revenue-agency/services/e-services/digital-services-individuals/account-individuals/change-marital-status-review.html" _blank
    click node25 "https://www.canada.ca/en/revenue-agency/services/e-services/digital-services-individuals/account-individuals/change-marital-status.html" _blank
    click node26 "https://www.canada.ca/en/revenue-agency/services/e-services/digital-services-individuals/account-individuals/help-account.html" _blank
    click node27 "https://www.canada.ca/en/revenue-agency/services/e-services/digital-services-individuals/account-individuals/help-change-marital-status.html" _blank
    click node28 "https://www.canada.ca/en/revenue-agency/services/e-services/digital-services-individuals/account-individuals/help-tfsa-contribution-page.html" _blank
    click node29 "https://www.canada.ca/en/revenue-agency/services/e-services/digital-services-individuals/account-individuals/help-uncashed-cheque.html" _blank
    click node30 "https://www.canada.ca/en/revenue-agency/services/e-services/digital-services-individuals/account-individuals/identification-spouse-common-law-partner-review.html" _blank
    click node31 "https://www.canada.ca/en/revenue-agency/services/e-services/digital-services-individuals/account-individuals/identification-spouse-common-law-partner.html" _blank
    click node32 "https://www.canada.ca/en/revenue-agency/services/e-services/digital-services-individuals/account-individuals/individual-income-tax-information.html" _blank
    click node33 "https://www.canada.ca/en/revenue-agency/services/e-services/digital-services-individuals/account-individuals/manage-direct-deposit.html" _blank
    click node34 "https://www.canada.ca/en/revenue-agency/services/e-services/digital-services-individuals/account-individuals/name-spouse-common-law-partner-review.html" _blank
    click node35 "https://www.canada.ca/en/revenue-agency/services/e-services/digital-services-individuals/account-individuals/name-spouse-common-law-partner.html" _blank
    click node36 "https://www.canada.ca/en/revenue-agency/services/e-services/digital-services-individuals/account-individuals/online-mail-individuals.html" _blank
    click node37 "https://www.canada.ca/en/revenue-agency/services/e-services/digital-services-individuals/account-individuals/submit-documents.html" _blank
    click node38 "https://www.canada.ca/en/revenue-agency/services/e-services/digital-services-individuals/account-individuals/update-marital-status-e2a.html" _blank
    click node39 "https://www.canada.ca/en/revenue-agency/services/e-services/digital-services-individuals/account-individuals/view-mail.html" _blank
    click node40 "https://www.canada.ca/en/revenue-agency/services/e-services/digital-services-individuals/account-individuals/residency-spouse-common-law-partner.html" _blank
    click node41 "https://www.canada.ca/en/revenue-agency/services/e-services/help-non-resident.html" _blank
    click node42 "https://www.canada.ca/en/revenue-agency/services/e-services/progress-tracker.html" _blank
    classDef inscope stroke:#7636ab,stroke-width:3px
    class node4,node7,node8,node9,node10,node11,node12,node15,node17,node18,node19,node20,node21,node22,node23,node24,node25,node26,node27,node28,node29,node30,node31,node32,node33,node34,node35,node36,node37,node38,node39,node40,node41,node42 inscope
```
