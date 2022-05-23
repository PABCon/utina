---
layout: default
title: Princing Component User Guide
parent: Guides
nav_order: 4
---
# Pricing Component - Concept & Configuration

# Privacy Policy

**0.1 Version (January 2022)**

**Internet**

Visit our home page: www.utina.io

Utina Software

France
34 rue Lacroix 75017
Paris

The information presented is subject to change without notice. UTINA assumes no responsibility for inaccuracies contained herein.

**©** Copyright **Utina** Headquarters. All rights reserved.

This product contains computer software documentation which is the property of Utina. Therefore, the information must not be made available to, copied, or used by anyone outside Utina without its written authorization.

Not to be used or disclosed except under applicable agreements.

The contents of this document are confidential by nature and are to be disclosed only on a need-to-know basis to persons belonging solely to Utina.

Any disclosure of the contents of this document to a third party can be done only after a written dialogue with Utina.

Please note that copying, disseminating, or taking any action based on the above information by anyone not intended as the recipient is unlawful.

This document should be considered in its totality for understanding.

# INDEX

[I.About this Publication 6](#_Toc95228258)

[II.Audiences 6](#_Toc95228259)

[III.Related Information 6](#_Toc95228260)

[IV.Special Conventions 6](#_Toc95228261)

[V.Summary of Changes: 7](#_Toc95228262)

[VI.High-level Concept 7](#_Toc95228263)

[1.Document Overview: 7](#_Toc95228264)

[2.Pricing Overview: 7](#_Toc95228265)

[3.MCD Conceptual Data Model: 8](#_Toc95228266)

[VII.Detailed Concepts 8](#_Toc95228267)

[1.Pricing Element: 8](#_Toc95228268)

[1.1 Search: 9](#_Toc95228269)

[1.2Configuration: 11](#_Toc95228270)

[1.2.1 For Contract Element: 11](#_Toc95228271)

[1.2.1.1 Contract Element Creation: Type Financial 11](#_Toc95228272)

[a-General Data: 12](#_Toc95228273)

[b-Calculation Mode: 13](#_Toc95228274)

[c-Rate: 16](#_Toc95228275)

[d-Duration: 17](#_Toc95228276)

[e-Grace Period: 18](#_Toc95228277)

[f-First Rental: 19](#_Toc95228278)

[g-Residual Value: 20](#_Toc95228279)

[h-Deferred Interest: 21](#_Toc95228280)

[i-Deposit: 22](#_Toc95228281)

[j-Participation: 22](#_Toc95228282)

[k-Prefinancing: 25](#_Toc95228283)

[l-Upfront: 25](#_Toc95228284)

[1.2.1.2 Contract Element Creation Type No Financial: 26](#_Toc95228285)

[a-General Data: 27](#_Toc95228286)

[b-Request Type: 28](#_Toc95228287)

[1.2.2 For Pricing formula: 28](#_Toc95228288)

[1.2.2.1Create a Pricing Formula: 28](#_Toc95228291)

[a-General Data: 29](#_Toc95228292)

[b-Request Type: 30](#_Toc95228293)

[1.3Update a Pricing Element: 31](#_Toc95228294)

[1.3.1 Update: 31](#_Toc95228295)

[1.3.2 Actions: 35](#_Toc95228296)

[2.Pricing Filtering: 35](#_Toc95228297)

[3.Service: 35](#_Toc95228298)

[3.1Service Overview: 35](#_Toc95228299)

[3.2Service Component: 35](#_Toc95228300)

[3.3Service Configuration: 36](#_Toc95228301)

[3.3.1Create a New Service: 36](#_Toc95228302)

[3.3.2Update a Service: 39](#_Toc95228303)

[4.Commission Concept: 44](#_Toc95228304)

[4.2Commission Overview: 44](#_Toc95228305)

[Commission Component: 44](#_Toc95228306)

[Commission Configuration: 44](#_Toc95228307)

[4.2.1Add a New Commission: 44](#_Toc95228308)

[4.2.2Update Commission: 49](#_Toc95228309)

[5.Pricing Pack Concept: 53](#_Toc95228310)

[5.1Pricing Pack Overview: 53](#_Toc95228311)

[4.2 Pricing Pack Component: 53](#_Toc95228312)

[4.3Pricing Pack Configuration: 53](#_Toc95228313)

[5.1.1Search Pricing Pack: 53](#_Toc95228314)

[4.3.2 Add a New Pricing pack: 53](#_Toc95228315)

[5.1.3Update Pricing pack: 57](#_Toc95228316)

[6.Offer: 57](#_Toc95228317)

[6.1Offer Overview: 57](#_Toc95228318)

[Offer Component: 57](#_Toc95228319)

[Search Offer: 58](#_Toc95228320)

[Offer Configuration: 58](#_Toc95228321)

[6.1.1Add a New Offer: 58](#_Toc95228322)

[6.1.2Update an Offer: 59](#_Toc95228323)

[7.Marketing Campaign: 59](#_Toc95228324)

# I. About this Publication

This document is a setup user guide describing the Utina Pricing component.

The print screens may differ from one user to another. And access rights to procedure, menu, sub-menus, sections, and fields are managed by user profiles access rights.

So, for more information about authorization and access rights management information, please read: Utina\_Management Company concepts.

# II. Audiences

This guide is intended for administrator and auditors responsible for setup the application.

# III. Related Information

For information about Utina products, see: Utina Company Website

([www.utina.io](https://utina.io/%20)/)

For information about related product components, see:

- Payment User&#39;s Guide;
- Workflow User&#39;s Guide;
- Proposal User&#39;s Guide;
- Contract User&#39;s Guide.

# IV. Special Conventions

Conventions used in this guide:

| **Convention** | **Meaning** |
| --- | --- |
| **Bold** | The object of an action: menu names, field names, options, button names - Commands typed at a prompt - User input |
| _Italic_ | Names of books, chapters and sections as references - Emphasis |
| Monospace | Directories and subdirectories - File names and extensions - Process names - Code sample, including keywords and variables within the text and as separate paragraphs, and user-defined program elements within the text |
| \&lt;Variable\&gt; | Substitute input value |

# V.Summary of Changes:

This publication contains additions and changes to information previously presented in Pricing Setup.

| **General changes** |
**-**
 |
| --- | --- |
| **New information** |
**-**
 |
| **Changed information** |
**-**
 |
| **Deleted information** |
**-**
 |

# VI. High Level Concept

## 1. Document Overview:

About: The purpose of this document is to describe the Utina Platform approach regarding handling pricing concepts. It also serves as a guide to help manage the different features and proceed to the configuration using detailed setting books and screens.

Utina Pricing is a powerful tool,
easy to set up and maintain

## 2. Pricing Overview:

The pricing is the value establishment of all criteria allowing a predefined model for payment calculation.

In general, when a user leases an asset, the user&#39;s monthly payment will be calculated based on the several factors:

- How much the user has to pay at the start of the lease, which is the upfront;
- The lease&#39;s term or duration in Months or Years;
- The expected asset value at the end of the lease;
- The fees that he will have to pay at the end of the lease, which is the Residual Value;
- The &quot;money factor&quot; or rent charge, which is similar to an interest rate on an asset loan;
- Possible termination fees if the user wants to return the asset before the lease ends;
- Etc.…

Once we define the asset amount, down payment, residual value, duration, and interest rate in the pricing, we will get the payment price.

In Utina Platform, we define the pricing as the lease/rental agreement covering different concepts that will be described in this document:

- Offer
- Pricing Element
- Pricing Filtering
- Pricing Pack
- Commission
- Service
- Marketing Campaign

## 3. MCD Conceptual Data Model:

From simple to highly complex,

Utina handles any Pricing Model!

![](RackMultipart20220523-1-3jkuvu_html_6c17d7f256e3069e.png)

# VII. Detailed Concepts

The essential features of the Pricing module of Utina are discussed in depth in this chapter.

## 1. Pricing Element:

A Pricing element is an object that uses to capture different types of prices, costs, adjustments, taxes, or profit margins.

The Pricing component is based on two essential elements:

- Contract Element
- Pricing Formula

![](RackMultipart20220523-1-3jkuvu_html_168f0d3376be0a56.png)

### 1.1. Search:

1.Log in to the application by typing the system user name and password.

2. Click OK to start the application.

On the Utina home page, the user can access the Pricing component through the Configuration menu  Pricing  Pricing element:

![Shape1](RackMultipart20220523-1-3jkuvu_html_7c8b90496fdf7a8c.gif) ![Shape2](RackMultipart20220523-1-3jkuvu_html_5095aa0e72371d2f.gif) ![](RackMultipart20220523-1-3jkuvu_html_7cf83cf4a0840f07.png)

The Pricing element menu will be displayed:

![](RackMultipart20220523-1-3jkuvu_html_991fda777ce8ddf1.png)

This section describes how to perform a filtering search for USERS using more extensive criteria. The user can sort the list using specific fields.

![Shape8](RackMultipart20220523-1-3jkuvu_html_6ca5306b09be8a92.gif) ![Shape7](RackMultipart20220523-1-3jkuvu_html_e2e4685df5167adc.gif) ![Shape6](RackMultipart20220523-1-3jkuvu_html_a2045e21783341ba.gif) ![Shape5](RackMultipart20220523-1-3jkuvu_html_5b2e49182749246f.gif) ![Shape4](RackMultipart20220523-1-3jkuvu_html_34ce65bbd7ebc2ca.gif) ![Shape3](RackMultipart20220523-1-3jkuvu_html_ca66d6c52cea2101.gif) ![](RackMultipart20220523-1-3jkuvu_html_db6c547ad09605be.png)

The user can select one or more specific filters to do a search or click on the button &#39;Search&#39; directly:

- ID
- Label
- Type (Type of Pricing)
- Pricing Status
- Financed Amount

And then click &#39;Search&#39;. ![](RackMultipart20220523-1-3jkuvu_html_6ab559d00009cd82.gif) :

The screen will display like below:

![Shape9](RackMultipart20220523-1-3jkuvu_html_959432e4dfcd0114.gif) ![](RackMultipart20220523-1-3jkuvu_html_5d463528903e43b0.png)

### 1.2. Configuration:

#### 1.2.1 For Contract Element:

##### 1.2.1.1 Contract Element Creation: Type Financial

To create a new financial Pricing element, the user should click the &#39;Add&#39; button. ![](RackMultipart20220523-1-3jkuvu_html_6ab559d00009cd82.gif)

![Shape10](RackMultipart20220523-1-3jkuvu_html_8ae9d5c6cf0e8cbd.gif) ![](RackMultipart20220523-1-3jkuvu_html_991fda777ce8ddf1.png)

The following screen will be displayed:

![](RackMultipart20220523-1-3jkuvu_html_90abeab006101ae5.png)

###### General Data:

The General Data section is composed by:

- **Label:** The Label of Pricing
- **Start Date:** The start date of the Pricing
- **End date:** the end date of Pricing
- **Type:** The type of pricing (Financial, Service, or other)
- **Category:** The category is related to the kind of Pricing
- **Pricing Description:** to describe the Pricing
- **Fin Amount Min:** The minimum Financing Amount
- **Fin Amount Max:** The maximum Financing Amount
- **Billing Date:** The Billing date
- **Tax code:**

  - Without Tax: No tax will be calculated
  - Standard rate: the tax will be calculated with the standard rate

- **Flag Grace Period**
- **Flag Fin Service**
- **Flag Mandatory**
- **Flag Update**

The user should select the type Financial:

![Shape11](RackMultipart20220523-1-3jkuvu_html_6f21e36be5541e67.gif) ![](RackMultipart20220523-1-3jkuvu_html_f5e2acce06074b0c.png)

###### Calculation Mode:

The Pricing component allow us to choose the calculation type modes.

**Linear Payment:** Linear Payment means a term loan with a fixed amortization schedule providing for the repayment of fixed, equal amounts of principal at regular intervals until maturity.

![Shape12](RackMultipart20220523-1-3jkuvu_html_46ae5c68ad79c66.gif) ![](RackMultipart20220523-1-3jkuvu_html_7217bc6ed8bbed1d.png)

7. Calculation method with STEPS:

- **Multiple Steps:** Multiple Steps is a method of payment that allows using multiple payments.
- **Weighted Steps:** The first step of the calculation is to take each of these payments and multiply them by the number of years until the payment occurs.
- **Seasonal Payment:** A seasonal payment (seasonal loan) is a loan that is repaid in keeping with a company&#39;s seasonal [cash flow](https://www.bdc.ca/en/articles-tools/entrepreneur-toolkit/templates-business-guides/glossary/cash-flow).

![Shape13](RackMultipart20220523-1-3jkuvu_html_e699be587c6e006a.gif) ![](RackMultipart20220523-1-3jkuvu_html_9f0030e3810b195a.png)

Referring to business requirements, the user can create one or multiple steps via the screen STEPS)

![](RackMultipart20220523-1-3jkuvu_html_6eb763c1e5f4b030.png)

The Steps screen is composed by :

- Order of steps
- Duration of steps
- Periodicity
- Rental Coefficient percentage: use if based on rental
- Coefficient Outstanding: use if based on outstanding

The user should fill in the information of the steps and click &#39;Save&#39; ![](RackMultipart20220523-1-3jkuvu_html_6ab559d00009cd82.gif) : (except Coefficient)

![Shape14](RackMultipart20220523-1-3jkuvu_html_9f76b48d131d8645.gif) ![](RackMultipart20220523-1-3jkuvu_html_d477bc2b63de1783.png)

To update, On action, click &#39;Delete&#39; and read a new step.

![Shape15](RackMultipart20220523-1-3jkuvu_html_18e49f332bf0de36.gif) ![](RackMultipart20220523-1-3jkuvu_html_d477bc2b63de1783.png) refaire

10. Return to the Pricing detail and complete the Rate section:

###### Rate:

T ![](RackMultipart20220523-1-3jkuvu_html_dcacce9a14f1e2b7.png) he Rate section is composed by:

- **Type of Rate:**

![Shape16](RackMultipart20220523-1-3jkuvu_html_d57fc5748e8b39b9.gif)

![Shape17](RackMultipart20220523-1-3jkuvu_html_d57fc5748e8b39b9.gif)

![Shape18](RackMultipart20220523-1-3jkuvu_html_d57fc5748e8b39b9.gif) ![Shape19](RackMultipart20220523-1-3jkuvu_html_d57fc5748e8b39b9.gif)

![Shape20](RackMultipart20220523-1-3jkuvu_html_efea5f1eb9834623.gif)

**The Type of Rate:**

- **Nominal rate** is a rate of interest used in adding compound interest to a principal sum when interest is compounded other than annually.
- **Effective rate** is an [actual](https://dictionary.cambridge.org/dictionary/english/actual) [rate](https://dictionary.cambridge.org/dictionary/english/rate) after everything has been [considered](https://dictionary.cambridge.org/dictionary/english/considered), [rather](https://dictionary.cambridge.org/dictionary/english/rather) than a [rate](https://dictionary.cambridge.org/dictionary/english/rate) that is [planned](https://dictionary.cambridge.org/dictionary/english/planned), [offered](https://dictionary.cambridge.org/dictionary/english/offer), etc.
- **Discounted at the end of the period**.
- **Discounted at begin of the period**.
- **A Floating rate** is a [rate](https://dictionary.cambridge.org/us/dictionary/english/rate) that can [change](https://dictionary.cambridge.org/us/dictionary/english/change) over a [period](https://dictionary.cambridge.org/us/dictionary/english/period) of [time](https://dictionary.cambridge.org/us/dictionary/english/time).

- **Calculated formula:**

The type of rate will determinate the calculated formula of the selected rate:

**EG:** The nominal rate type will determine the formula Market Money Rate .

![](RackMultipart20220523-1-3jkuvu_html_129059045d245f5f.png)

- **P ![](RackMultipart20220523-1-3jkuvu_html_77825062d0bce4b2.png) eriodicity**:

- also the user can fill the periodicity of the rate:

![Shape21](RackMultipart20220523-1-3jkuvu_html_efea5f1eb9834623.gif)

![Shape22](RackMultipart20220523-1-3jkuvu_html_d57fc5748e8b39b9.gif)

![Shape23](RackMultipart20220523-1-3jkuvu_html_d57fc5748e8b39b9.gif) ![Shape24](RackMultipart20220523-1-3jkuvu_html_d57fc5748e8b39b9.gif)

- **Value default** : is the rate value default.

![](RackMultipart20220523-1-3jkuvu_html_34cb0c33babf6928.png)

- **The spread:**

![Shape27](RackMultipart20220523-1-3jkuvu_html_37635cc95a4c8daf.gif) ![Shape26](RackMultipart20220523-1-3jkuvu_html_a8a61681382261c0.gif) ![Shape25](RackMultipart20220523-1-3jkuvu_html_a8a61681382261c0.gif) ![](RackMultipart20220523-1-3jkuvu_html_73d0ea21c921dc8c.png)

The use of Pricing in the Proposal modification of the default Pricing settings will trigger a functional control and be monitored by the request type, the request receiver, and the profile.

###### Duration:

The Duration section is composed by:

- Duration Default
- Duration Min
- Duration Max
- Periodicity
- Term
- Unit

![Shape33](RackMultipart20220523-1-3jkuvu_html_35d19d55d3ce7758.gif) ![Shape32](RackMultipart20220523-1-3jkuvu_html_35d19d55d3ce7758.gif) ![Shape31](RackMultipart20220523-1-3jkuvu_html_35d19d55d3ce7758.gif) ![Shape29](RackMultipart20220523-1-3jkuvu_html_257a61ea5216c228.gif) ![Shape28](RackMultipart20220523-1-3jkuvu_html_615e7e538a3f6d0c.gif) ![Shape30](RackMultipart20220523-1-3jkuvu_html_35d19d55d3ce7758.gif) ![](RackMultipart20220523-1-3jkuvu_html_bcda6007887de853.png)

Again, the use of Pricing in the Proposal modification of the default Pricing settings will trigger a functional control and be monitored by the request type, the request receiver, and the profile.

![Shape36](RackMultipart20220523-1-3jkuvu_html_ff40f8d29ecc3838.gif) ![Shape35](RackMultipart20220523-1-3jkuvu_html_ff40f8d29ecc3838.gif) ![Shape34](RackMultipart20220523-1-3jkuvu_html_ff40f8d29ecc3838.gif) ![](RackMultipart20220523-1-3jkuvu_html_bcda6007887de853.png)

###### Grace Period:

Grace period refers to the time frame between the date when the user billing cycle and the date when user payment is due; there is a method of calculation that Utina offers:

The Grace Period section is composed by:

- **Grace Period Method:**

- **Capitalization:** the interest will be capitalized when repayment begins.
- **Interest Invoicing:** The interest will accrue at the beginning of the payment.
- **None:** No grace period

- **Grace period Duration:** It&#39;s the duration of the grace period in months.

![Shape38](RackMultipart20220523-1-3jkuvu_html_3a12338a79930a2a.gif) ![Shape37](RackMultipart20220523-1-3jkuvu_html_ff40f8d29ecc3838.gif) ![](RackMultipart20220523-1-3jkuvu_html_db942646d1f2229.png)

###### First Rental:

The First Rental section is composed by:

- % Amount Min: The percentage of the Minimum Amount
- % Amount Max: The percentage of the Maximum Amount
- Default Value: The Default Value of the Amount

![Shape41](RackMultipart20220523-1-3jkuvu_html_ff40f8d29ecc3838.gif) ![Shape40](RackMultipart20220523-1-3jkuvu_html_ff40f8d29ecc3838.gif) ![Shape39](RackMultipart20220523-1-3jkuvu_html_ff40f8d29ecc3838.gif) ![](RackMultipart20220523-1-3jkuvu_html_5252a0ee8f056c66.png)

Once more, the use of Pricing in the Proposal modification of the default Pricing settings will trigger a functional control and be monitored by the request type, the request receiver, and the profile.

![Shape44](RackMultipart20220523-1-3jkuvu_html_ff40f8d29ecc3838.gif) ![Shape42](RackMultipart20220523-1-3jkuvu_html_ff40f8d29ecc3838.gif) ![Shape43](RackMultipart20220523-1-3jkuvu_html_ff40f8d29ecc3838.gif) ![](RackMultipart20220523-1-3jkuvu_html_376e9641e9b8d6e.png)

###### Residual Value:

[The Residual Value is the estimated value of a fixed asset at the end of its lease term or useful life.](https://www.investopedia.com/terms/r/residual-value.asp)

The Residual Value section is composed by :

- RV Min %: The Minimum Residual Value in percentage

- RV Max % : The Maximum Residual Value in percentage
- RV Default %: The Default Residual Value in percentage
- RV Default Value: The Default Residual Value in amount

![Shape48](RackMultipart20220523-1-3jkuvu_html_ff40f8d29ecc3838.gif) ![Shape47](RackMultipart20220523-1-3jkuvu_html_ff40f8d29ecc3838.gif) ![Shape46](RackMultipart20220523-1-3jkuvu_html_ff40f8d29ecc3838.gif) ![Shape45](RackMultipart20220523-1-3jkuvu_html_ff40f8d29ecc3838.gif) ![](RackMultipart20220523-1-3jkuvu_html_6bfe297dd526991.png)

And again, the use of Pricing in the Proposal modification of the default Pricing settings will trigger a functional control and be monitored by the request type, the request receiver, and the profile.

![Shape51](RackMultipart20220523-1-3jkuvu_html_d4e54b78065e1d72.gif) ![Shape50](RackMultipart20220523-1-3jkuvu_html_d4e54b78065e1d72.gif) ![Shape49](RackMultipart20220523-1-3jkuvu_html_d4e54b78065e1d72.gif) ![](RackMultipart20220523-1-3jkuvu_html_6bfe297dd526991.png)

###### Deferred interest:

A Deferred Interest allows the deferral of some or all of a loan&#39;s interest, enabling borrowers to make smaller payments for a specified time.

The Deferred Interest section is composed by:

- **Deferred Interest Method:**

- **Interest invoicing at the beginning of the contract:** The interest will be capitalized at the beginning of the contract.
- **Capitalization of Interest:** The interest will be generated between the start date and the first billing date.
- **Part of Rental**
- **None:** No deferred interest.

- **Nominal Rate**

![Shape53](RackMultipart20220523-1-3jkuvu_html_308cd74d5bc1bb3.gif) ![Shape52](RackMultipart20220523-1-3jkuvu_html_20886b6b483fb8f7.gif) ![](RackMultipart20220523-1-3jkuvu_html_a35ab439bf495e92.png)

###### Deposit:

The Deposit section is composed by:

- **Deposit Amount:** The collateral Amount.
- **% Amount:** The percentage of the Deposit Amount according to the mortgage.
- **Interest Method:**

- **Reducing Interest of Installment:** the interest generated by the deposit amount will be reduced from the due.
- **None:** No interest Method.

- **Nominal Rate:** the Nominal Rate of the deposit amount; this field will display when choosing interest method.

![Shape54](RackMultipart20220523-1-3jkuvu_html_20886b6b483fb8f7.gif) ![Shape55](RackMultipart20220523-1-3jkuvu_html_20886b6b483fb8f7.gif) ![Shape57](RackMultipart20220523-1-3jkuvu_html_20886b6b483fb8f7.gif) ![Shape56](RackMultipart20220523-1-3jkuvu_html_20886b6b483fb8f7.gif) ![](RackMultipart20220523-1-3jkuvu_html_76933bac3c0539f4.png)

###### Participation:

Participation means an interest in a loan that is acquired indirectly by way of participation from a selling institution.

The Participation section is composed by:

- **Calculation Method:**

  - Supplier Credit:
  - Reduce Financing Amount:
  - Prom (Reduce Fin Amount):
  - None:

- **Participation Amount**
- **Participation Rate**
- **Number of Days**
- **Third-party Role**
- **Third-party**

![Shape61](RackMultipart20220523-1-3jkuvu_html_e93ef4b9f160e4e8.gif) ![Shape60](RackMultipart20220523-1-3jkuvu_html_20886b6b483fb8f7.gif) ![Shape59](RackMultipart20220523-1-3jkuvu_html_20886b6b483fb8f7.gif) ![Shape58](RackMultipart20220523-1-3jkuvu_html_20886b6b483fb8f7.gif) ![](RackMultipart20220523-1-3jkuvu_html_64d5639cbcb45c54.png)

And select the third-party Role and the third party (created in the Third Party section):

Click on the &#39;Search&#39; button on the Third Party:

![Shape62](RackMultipart20220523-1-3jkuvu_html_ce918699a4a1cfd5.gif) ![](RackMultipart20220523-1-3jkuvu_html_64d5639cbcb45c54.png)

All third party with the selected role will display:

![Shape65](RackMultipart20220523-1-3jkuvu_html_e8912913e50e3552.gif) ![Shape64](RackMultipart20220523-1-3jkuvu_html_421ad61f5ffd75e5.gif) ![Shape63](RackMultipart20220523-1-3jkuvu_html_25e7e45bb23738ec.gif) ![](RackMultipart20220523-1-3jkuvu_html_618d040342fce05c.png)

Then click &#39;OK&#39;.

The user can see all information about the third party on Open Synthesis or in the Financial element screen:

![Shape66](RackMultipart20220523-1-3jkuvu_html_4263791d26360723.gif) ![](RackMultipart20220523-1-3jkuvu_html_64d5639cbcb45c54.png)

Click on &#39;Third Party&#39;, and the screen will display all information of the third party:

![Shape68](RackMultipart20220523-1-3jkuvu_html_4263791d26360723.gif) ![Shape69](RackMultipart20220523-1-3jkuvu_html_4263791d26360723.gif) ![Shape67](RackMultipart20220523-1-3jkuvu_html_493d36dd6276ae81.gif) ![](RackMultipart20220523-1-3jkuvu_html_5dbe920e5998e148.png)

Seamless integration with any

Third-Party or Retail solutions

###### Prefinancing:

The Prefinancing section is composed by:

- **Calculation Method**
- **Nominal Rate**
- **Basis**
- **Periodicity**
- **Rate Type**
- **Rate formula**

![Shape75](RackMultipart20220523-1-3jkuvu_html_a4977b7d84e39d04.gif) ![Shape74](RackMultipart20220523-1-3jkuvu_html_a4977b7d84e39d04.gif) ![Shape73](RackMultipart20220523-1-3jkuvu_html_a4977b7d84e39d04.gif) ![Shape72](RackMultipart20220523-1-3jkuvu_html_a4977b7d84e39d04.gif) ![Shape71](RackMultipart20220523-1-3jkuvu_html_a4977b7d84e39d04.gif) ![Shape70](RackMultipart20220523-1-3jkuvu_html_a4977b7d84e39d04.gif) ![](RackMultipart20220523-1-3jkuvu_html_8cac3f893704304f.png)

###### Upfront:

The Upfront section is composed by:

- **Amount Min**
- **Amount Max**
- **Default Value**

![Shape78](RackMultipart20220523-1-3jkuvu_html_3ff146e9bdffc79e.gif) ![Shape77](RackMultipart20220523-1-3jkuvu_html_a4977b7d84e39d04.gif) ![Shape76](RackMultipart20220523-1-3jkuvu_html_a4977b7d84e39d04.gif) ![](RackMultipart20220523-1-3jkuvu_html_dead78d09bd25744.png)

The use of Pricing in the Proposal modification of the default Pricing settings will again trigger a functional control and be monitored by the request type, the request receiver, and the profile.

Click on the &#39;Save&#39; button. A Pricing Id will be generated. ![](RackMultipart20220523-1-3jkuvu_html_6ab559d00009cd82.gif) :

![Shape79](RackMultipart20220523-1-3jkuvu_html_ba0fa5eb96c9877e.gif) ![](RackMultipart20220523-1-3jkuvu_html_8da30c79f94aa79e.png)

##### 1.2.1.2. Contract Element Creation Type No Financial:

Log in to the application by typing the user system user name and password.

Click &#39;OK&#39; to start the application.

On the Utina homepage, the user can access to Pricing component through the Configuration menu  Pricing  Pricing element:

The Contract element types No Financial is composed by:

- **Service:** Service Lease or Rent is a type of lease where the lessor undertakes the responsibility to serve all the assets that the lessee leases out.
- **Commission:** Commission means a fee payable to a broker or other third party in connection with a lease or the expansion or renewal of a lease.
- **Financed Service:** The Financed Service is an agreement where the lessor receives lease payments to cover its ownership&#39; costs. The lessee is responsible for maintenance, insurance, and taxes. Some finance leases are conditional sales or hire purchase agreements.
- **Contract Fees:** [Contract Fee](https://www.lawinsider.com/dictionary/lease-fee) means any monetary fee or other charge or consideration, or any combination thereof, charged by or paid during a particular shift, or for any period.

4.Click the &#39;Add&#39; button. ![](RackMultipart20220523-1-3jkuvu_html_6ab559d00009cd82.gif)

![Shape80](RackMultipart20220523-1-3jkuvu_html_8ae9d5c6cf0e8cbd.gif) ![](RackMultipart20220523-1-3jkuvu_html_991fda777ce8ddf1.png)

The screen will display the following information:

![](RackMultipart20220523-1-3jkuvu_html_93a9973277895467.png)

###### General Data:

In General Data, the type is composed of no financial element:

- Service
- Commission
- Contract Fees
- Financed Service

When choosing **Service:** the category will display all services created on the Service menu (the user will find an explanation on the Service section [below](#_Add_a_new)).

When choosing **Commission:** the category will display all commissions created on the Commission menu (the user will find an explanation [below](#_Add_a_new_1)).

When choosing **Financed Service:** the category will display all financed services (the user will find an explanation on the Service section [below](#_Add_a_new)).

When choosing **Contract Fees:** the category will display all contract fees (the user will find an explanation on the Service section [below](#_Add_a_new)).

![Shape82](RackMultipart20220523-1-3jkuvu_html_282cb799c5a65ac8.gif) ![Shape81](RackMultipart20220523-1-3jkuvu_html_282cb799c5a65ac8.gif) ![](RackMultipart20220523-1-3jkuvu_html_fe5c7ae9035cd203.png)

###### Request Type:

![Shape84](RackMultipart20220523-1-3jkuvu_html_282cb799c5a65ac8.gif) ![Shape83](RackMultipart20220523-1-3jkuvu_html_282cb799c5a65ac8.gif) ![](RackMultipart20220523-1-3jkuvu_html_fa7f3343a201aa88.png)

The use of Pricing in the Proposal modification of the default Pricing settings will trigger a functional control and be monitored by the request type, the request receiver, and the profile.

Click &#39;Save&#39; and a Pricing ID will be generated.

#### 1.2.2. For Pricing formula:

##### 1.2.2.1 Create a Pricing Formula:

1. Log in to the application by typing the system user name and password.

2. Click &#39;OK&#39; to start the application.

3. On the Utina homepage, the user can access to Pricing component through the Configuration menu  Pricing  Pricing element:

![Shape85](RackMultipart20220523-1-3jkuvu_html_7c8b90496fdf7a8c.gif) ![Shape86](RackMultipart20220523-1-3jkuvu_html_5095aa0e72371d2f.gif) ![](RackMultipart20220523-1-3jkuvu_html_7cf83cf4a0840f07.png)

The Pricing element menu will display:

![Shape87](RackMultipart20220523-1-3jkuvu_html_8ae9d5c6cf0e8cbd.gif) ![](RackMultipart20220523-1-3jkuvu_html_991fda777ce8ddf1.png)

4. Click the &#39;Add&#39; button. ![](RackMultipart20220523-1-3jkuvu_html_6ab559d00009cd82.gif):

![](RackMultipart20220523-1-3jkuvu_html_650a0f083dfbef3e.png)

5. Choose a Formula in Type. Fill in all the Financial Pricing sections that will be displayed:

###### General Data:

In General Data, the type is composed a formula:

- Modification Fee Formula:
- Total Pay off Fees Formula:
- Partial Pay off Fees Formula:
- Degradation Fee Formula:
- Rejection Fee Formula:
- Reminder Fee Formula:
- Late Charge Formula: For late charge calculation.

![Shape88](RackMultipart20220523-1-3jkuvu_html_f929ddb0222210f5.gif) ![](RackMultipart20220523-1-3jkuvu_html_d8c03c2625e11ad7.png)

Fill in all information and go to the section Request Type:

###### Request Type:

![Shape90](RackMultipart20220523-1-3jkuvu_html_f929ddb0222210f5.gif) ![Shape89](RackMultipart20220523-1-3jkuvu_html_f929ddb0222210f5.gif) ![](RackMultipart20220523-1-3jkuvu_html_4b60dce6ecab0369.png)

Click &#39;Save&#39; and a Pricing ID will be generated:

![Shape91](RackMultipart20220523-1-3jkuvu_html_24a084d2a2322b6c.gif) ![](RackMultipart20220523-1-3jkuvu_html_7a4dc288a4c8d04c.png)

### 1.3. Update a Pricing element:

#### 1.3.1 Update:

1. On the Utina homepage, go to Configuration  Pricing  Pricing element and click on it. ![](RackMultipart20220523-1-3jkuvu_html_6ab559d00009cd82.gif)

2. Click on the &#39;Search&#39; button, and the list of Pricing element will display: ![](RackMultipart20220523-1-3jkuvu_html_6ab559d00009cd82.gif)

![Shape92](RackMultipart20220523-1-3jkuvu_html_e7d747f2a0580e10.gif) ![](RackMultipart20220523-1-3jkuvu_html_11ee7945c8fcfa5c.png)

3. Click on one existing pricing:

![Shape93](RackMultipart20220523-1-3jkuvu_html_54095f73b4a0cf63.gif) ![](RackMultipart20220523-1-3jkuvu_html_cda6950f8409db07.png)

4. The pricing information will display:

![](RackMultipart20220523-1-3jkuvu_html_5f8c86063f9a775.png)

5. The user can modify information and click &#39;Update&#39;:

![Shape94](RackMultipart20220523-1-3jkuvu_html_a217f2cb84eca28e.gif) ![](RackMultipart20220523-1-3jkuvu_html_90be3240d5b832fa.png)

The user can add Criteria on the Pricing element, through Pricing Pricing Criteria  Add: ![](RackMultipart20220523-1-3jkuvu_html_6ab559d00009cd82.gif)

![Shape96](RackMultipart20220523-1-3jkuvu_html_332940596c26b375.gif) ![Shape95](RackMultipart20220523-1-3jkuvu_html_c2b9e01f25b5ece9.gif) ![](RackMultipart20220523-1-3jkuvu_html_ea2b4e3b97dabf49.png)

9. After clicking on the &#39;Save&#39; button, an ID will be generated, and the Pricing criteria will be added as below: ![](RackMultipart20220523-1-3jkuvu_html_6ab559d00009cd82.gif):

![Shape98](RackMultipart20220523-1-3jkuvu_html_332940596c26b375.gif) ![Shape97](RackMultipart20220523-1-3jkuvu_html_3567af1f6ef05084.gif) ![](RackMultipart20220523-1-3jkuvu_html_c1ec0997e94c1b18.png)

10. The user can also delete the Pricing criteria by clicking on the &#39;Delete&#39; button. ![](RackMultipart20220523-1-3jkuvu_html_6ab559d00009cd82.gif):

![Shape100](RackMultipart20220523-1-3jkuvu_html_9edd2a00e268344f.gif) ![Shape99](RackMultipart20220523-1-3jkuvu_html_46b40b4318fd9a5a.gif) ![](RackMultipart20220523-1-3jkuvu_html_4c989d87d93113c3.png)

11.To add Pricing commission, click on the created Pricing Pricing Commission  Add ![](RackMultipart20220523-1-3jkuvu_html_6ab559d00009cd82.gif):

![Shape102](RackMultipart20220523-1-3jkuvu_html_556708ea4dd2af5a.gif) ![Shape101](RackMultipart20220523-1-3jkuvu_html_664156c9a65f3c0d.gif) ![](RackMultipart20220523-1-3jkuvu_html_6a6973b4404a73e8.png)

A screen of Pricing commission detail will display:

![Shape103](RackMultipart20220523-1-3jkuvu_html_867b8dd8bc8fcddc.gif) ![](RackMultipart20220523-1-3jkuvu_html_861ed45d13f9c3bd.png)

After the user complete the following information, an ID will be generated :

![Shape104](RackMultipart20220523-1-3jkuvu_html_a0596404c7d0e573.gif) ![](RackMultipart20220523-1-3jkuvu_html_88af40a9d0b35b8f.png)

When choosing the Calculation method _Multiple Steps, Weighted Steps or Seasonal_ on Financial Type_,_ a new screen will display:

The user can update or delete steps:

![Shape106](RackMultipart20220523-1-3jkuvu_html_1a3023812980a7d1.gif) ![Shape105](RackMultipart20220523-1-3jkuvu_html_6bf2eba48d4014eb.gif) ![](RackMultipart20220523-1-3jkuvu_html_25cfa7a4bb2a7c16.png)

#### 1.3.2 Actions:

8. To activate the Pricing, go to Action and click &#39;Activate&#39; (the user can also disable or terminate the Pricing element): ![](RackMultipart20220523-1-3jkuvu_html_6ab559d00009cd82.gif)

![Shape107](RackMultipart20220523-1-3jkuvu_html_81f1eb324066119.gif) ![](RackMultipart20220523-1-3jkuvu_html_11c6e2d34db9ffcc.png)

9. To duplicate the Pricing element, go to action and click &#39;duplicate&#39;: ![](RackMultipart20220523-1-3jkuvu_html_6ab559d00009cd82.gif)

![Shape108](RackMultipart20220523-1-3jkuvu_html_81f1eb324066119.gif) ![](RackMultipart20220523-1-3jkuvu_html_11c6e2d34db9ffcc.png)

## 2. Pricing Filtering

## Service:

A service is a help given to a client in exchange for money. Therefore, it is also intangible and can only be qualified and described, not weighted and carried like a product. All companies offering services are part of the tertiary sector.

For example, a service Lease is a type of lease where the lessor undertakes the responsibility to serve all the assets that the lessee leases out.

### Search:

1.Log in to the application by typing the system user name and password.

2. Click &#39;OK&#39; to start the application.

On the Utina homepage, the user can access to the Pricing component through the Configuration menu  Pricing  Service:

![Shape110](RackMultipart20220523-1-3jkuvu_html_7c8b90496fdf7a8c.gif) ![Shape109](RackMultipart20220523-1-3jkuvu_html_5095aa0e72371d2f.gif) ![](RackMultipart20220523-1-3jkuvu_html_7cf83cf4a0840f07.png)

The Service menu will be displayed:

![](RackMultipart20220523-1-3jkuvu_html_5c66901bf0867ed1.png)

This section describes how to perform a filtering search for USERS using more extensive criteria. The user can sort the list using specific fields.

![Shape113](RackMultipart20220523-1-3jkuvu_html_6ca5306b09be8a92.gif) ![Shape114](RackMultipart20220523-1-3jkuvu_html_e2e4685df5167adc.gif) ![Shape115](RackMultipart20220523-1-3jkuvu_html_a2045e21783341ba.gif) ![Shape116](RackMultipart20220523-1-3jkuvu_html_f655338cad688c91.gif) ![Shape111](RackMultipart20220523-1-3jkuvu_html_49612c513bf543cc.gif) ![Shape112](RackMultipart20220523-1-3jkuvu_html_ca66d6c52cea2101.gif) ![](RackMultipart20220523-1-3jkuvu_html_987736394c4fce28.png)

The user can select one or more specific filters to make a search or click on the &#39;Search&#39; button directly:

- Code
- Label
- Service Type
- Category
- Status

And then click &#39;Search&#39;. ![](RackMultipart20220523-1-3jkuvu_html_6ab559d00009cd82.gif) :

The screen will display like below:

![Shape117](RackMultipart20220523-1-3jkuvu_html_959432e4dfcd0114.gif) ![](RackMultipart20220523-1-3jkuvu_html_e286f2a1921c0344.png)

### Configuration:

The Service component starts with the service creation by adding the following main data:

- Service General Data
- Service
- Invoicing
- Supplier

#### Create a New Service:

1.On the Utina homepage, go to Configuration  Pricing  Service and click on it. ![](RackMultipart20220523-1-3jkuvu_html_6ab559d00009cd82.gif)

![Shape118](RackMultipart20220523-1-3jkuvu_html_558e4fbd85cfd764.gif) ![Shape119](RackMultipart20220523-1-3jkuvu_html_63934342d8a62a07.gif) ![](RackMultipart20220523-1-3jkuvu_html_8fe74cb81c4267f9.png)

2. To add a new service, click the &#39;Add&#39; button ![](RackMultipart20220523-1-3jkuvu_html_6ab559d00009cd82.gif)

![Shape120](RackMultipart20220523-1-3jkuvu_html_7da4340090a20611.gif) ![](RackMultipart20220523-1-3jkuvu_html_8aa7e8b5545167c0.png)

3. A New Service screen will be displayed:

![](RackMultipart20220523-1-3jkuvu_html_78c8315845a0a224.png)

The New Service screen is composed by:

- General Data
- Service: Information related to service
- Invoicing: Information related to invoicing
- Supplier: Information related to supplier

##### General Data:

The General Data section is composed by :

- Code
- Label
- Currency
- Start date
- End date

![Shape125](RackMultipart20220523-1-3jkuvu_html_e71dde6d1d9562dd.gif) ![Shape124](RackMultipart20220523-1-3jkuvu_html_9c6a8709e24c6395.gif) ![Shape123](RackMultipart20220523-1-3jkuvu_html_9c6a8709e24c6395.gif) ![Shape122](RackMultipart20220523-1-3jkuvu_html_cb30bbb014b5d333.gif) ![Shape121](RackMultipart20220523-1-3jkuvu_html_cb30bbb014b5d333.gif) ![](RackMultipart20220523-1-3jkuvu_html_852fff0bd7c478e1.png)

After completing the general data information, fill the information in the Service section:

##### Service:

![Shape133](RackMultipart20220523-1-3jkuvu_html_62cd0ad5d01ff645.gif) ![Shape132](RackMultipart20220523-1-3jkuvu_html_62cd0ad5d01ff645.gif) ![Shape131](RackMultipart20220523-1-3jkuvu_html_62cd0ad5d01ff645.gif) ![Shape130](RackMultipart20220523-1-3jkuvu_html_62cd0ad5d01ff645.gif) ![Shape129](RackMultipart20220523-1-3jkuvu_html_62cd0ad5d01ff645.gif) ![Shape128](RackMultipart20220523-1-3jkuvu_html_62cd0ad5d01ff645.gif) ![Shape127](RackMultipart20220523-1-3jkuvu_html_62cd0ad5d01ff645.gif) ![Shape126](RackMultipart20220523-1-3jkuvu_html_62cd0ad5d01ff645.gif) ![](RackMultipart20220523-1-3jkuvu_html_852fff0bd7c478e1.png)

The Service section is composed by :

- **Service Type:**
- **Category**
- **Service Basis**
- **Amount Basis**
- **Service Duration:** The field Service Duration is related to other fields like below :

![](RackMultipart20220523-1-3jkuvu_html_acbb540ff0d4bd88.png)

- **Service Calculation Method:** The field Service Calculation Method is related to other fields like below:

![](RackMultipart20220523-1-3jkuvu_html_484873e5481d2091.png)

- **Service Period**
- **Service Duration Definition**
- **Fixed Amount**
- **Percentage**

##### Invoicing:

![Shape138](RackMultipart20220523-1-3jkuvu_html_62cd0ad5d01ff645.gif) ![Shape137](RackMultipart20220523-1-3jkuvu_html_62cd0ad5d01ff645.gif) ![Shape136](RackMultipart20220523-1-3jkuvu_html_62cd0ad5d01ff645.gif) ![Shape135](RackMultipart20220523-1-3jkuvu_html_62cd0ad5d01ff645.gif) ![Shape134](RackMultipart20220523-1-3jkuvu_html_7329dc136e3e3c4a.gif) ![](RackMultipart20220523-1-3jkuvu_html_2998181e5d3a5a27.png)

The Invoicing section is composed by:

![](RackMultipart20220523-1-3jkuvu_html_160db714110b4682.png)

- Type:

![](RackMultipart20220523-1-3jkuvu_html_8e671acbed32dad0.png)

- Line:

- C ![](RackMultipart20220523-1-3jkuvu_html_9add454c1d9467b4.png) ategory:

- T ![](RackMultipart20220523-1-3jkuvu_html_aebab412adfe79c6.png) ax Code:

##### Supplier:

The Invoicing section is composed by :

- Third party Role
- Third party
- S ![](RackMultipart20220523-1-3jkuvu_html_1db08c536242c711.png) ervice Repayment Mode :
  - On invoice
  - On receiving payment
  - None
- Flag Auto Expense
- Service Repayement Percentage
- Service Repayment Fixed Amount

![Shape139](RackMultipart20220523-1-3jkuvu_html_b233626c25f5a861.gif) ![](RackMultipart20220523-1-3jkuvu_html_62ef2e6308ee5508.png)

![](RackMultipart20220523-1-3jkuvu_html_7449a4f2db7e27be.png)

Click save :

A new service will be created.

### Update Service:

##### 3.2.2.1 Update:

1.On the Utina homepage, go to Configuration  Pricing  Service and click on it. ![](RackMultipart20220523-1-3jkuvu_html_6ab559d00009cd82.gif):

2. Click on the &#39;Search&#39; button, and the list of services will be displayed. ![](RackMultipart20220523-1-3jkuvu_html_6ab559d00009cd82.gif):

![Shape140](RackMultipart20220523-1-3jkuvu_html_eff81cd22162208d.gif) ![](RackMultipart20220523-1-3jkuvu_html_c84cec2a9c9e1061.png)

Click on &#39;Service&#39; to modify. ![](RackMultipart20220523-1-3jkuvu_html_6ab559d00009cd82.gif):

![Shape141](RackMultipart20220523-1-3jkuvu_html_eff81cd22162208d.gif)

![](RackMultipart20220523-1-3jkuvu_html_c0a1da606393e798.png)

The selected service will display and the user can modify information and click &#39;Update&#39;. ![](RackMultipart20220523-1-3jkuvu_html_6ab559d00009cd82.gif):

![Shape142](RackMultipart20220523-1-3jkuvu_html_517877b1aa66fa8f.gif) ![](RackMultipart20220523-1-3jkuvu_html_2edf90969bd98602.png)

6. The user can add criteria on the Service ![](RackMultipart20220523-1-3jkuvu_html_6ab559d00009cd82.gif) :

![Shape143](RackMultipart20220523-1-3jkuvu_html_d8fa3f844b074926.gif) ![](RackMultipart20220523-1-3jkuvu_html_2a4b6a5c08034a9f.png)

Select a Criteria Code and a Criteria Value and click &#39;Save&#39;. ![](RackMultipart20220523-1-3jkuvu_html_6ab559d00009cd82.gif) :

![Shape146](RackMultipart20220523-1-3jkuvu_html_9fc1f8df110d3c88.gif) ![Shape145](RackMultipart20220523-1-3jkuvu_html_9fc1f8df110d3c88.gif) ![Shape144](RackMultipart20220523-1-3jkuvu_html_38801509c08bd1ea.gif) ![](RackMultipart20220523-1-3jkuvu_html_b8c86eee5edb681d.png)

After Saving, a Service Criteria ID will be generated:

![Shape147](RackMultipart20220523-1-3jkuvu_html_7c0375cc6d2f7a2d.gif) ![](RackMultipart20220523-1-3jkuvu_html_c6838a84ac104167.png)

To delete a Service Criteria, click on the &#39;Delete&#39; button on Service Criteria ![](RackMultipart20220523-1-3jkuvu_html_6ab559d00009cd82.gif) :

![Shape148](RackMultipart20220523-1-3jkuvu_html_1631f358464cf08e.gif) ![](RackMultipart20220523-1-3jkuvu_html_fba13cbd75ecc2ac.png)

##### 3.2.2.2 Action:

The user can activate, disable or terminate a service. ![](RackMultipart20220523-1-3jkuvu_html_6ab559d00009cd82.gif) :

![Shape149](RackMultipart20220523-1-3jkuvu_html_171af51f36aed1f8.gif) ![](RackMultipart20220523-1-3jkuvu_html_b801608fafacc1cd.png)

## Commission:

A commission is a percentage or fixed payment associated with a Pricing.

### Search:

### Configuration:

#### Add a New Commission:

1.On the Utina homepage, go to Configuration  Pricing  Commission and click on it. ![](RackMultipart20220523-1-3jkuvu_html_6ab559d00009cd82.gif)

![Shape151](RackMultipart20220523-1-3jkuvu_html_1748ef494456ccaf.gif) ![Shape150](RackMultipart20220523-1-3jkuvu_html_74d2f2c5dce90b4b.gif) ![](RackMultipart20220523-1-3jkuvu_html_31e42ddaf805a24f.png)

2.To add a new commission, click the &#39;Add&#39; button. ![](RackMultipart20220523-1-3jkuvu_html_6ab559d00009cd82.gif):

![](RackMultipart20220523-1-3jkuvu_html_2db8bc73dd869a97.png)

3.A new commission screen will be displayed:

![](RackMultipart20220523-1-3jkuvu_html_90977930846752a4.png)

4. After completing the following information, click on the &#39;Save&#39; button ![](RackMultipart20220523-1-3jkuvu_html_6ab559d00009cd82.gif) :

![Shape152](RackMultipart20220523-1-3jkuvu_html_78c6e2a5924cba40.gif) ![](RackMultipart20220523-1-3jkuvu_html_bde0b2e7fd075ae.png)

5. A new commission will be added; click &#39;Search&#39; on the list and click on the new commission ![](RackMultipart20220523-1-3jkuvu_html_6ab559d00009cd82.gif) :

![Shape154](RackMultipart20220523-1-3jkuvu_html_deaad006394a8e54.gif) ![Shape153](RackMultipart20220523-1-3jkuvu_html_f36c39ee0c30efd0.gif) ![](RackMultipart20220523-1-3jkuvu_html_e9c42887a7bfff17.png)

6. The user can add criteria on the Commission ![](RackMultipart20220523-1-3jkuvu_html_6ab559d00009cd82.gif) :

![Shape155](RackMultipart20220523-1-3jkuvu_html_53f9925e29e4770.gif) ![](RackMultipart20220523-1-3jkuvu_html_d9dec9e558e381da.png)

Select a Criteria Code and a Criteria Value and click &#39;Save&#39;:

![Shape158](RackMultipart20220523-1-3jkuvu_html_ec083ff150f1bfea.gif) ![Shape157](RackMultipart20220523-1-3jkuvu_html_ec083ff150f1bfea.gif) ![Shape156](RackMultipart20220523-1-3jkuvu_html_43afa1729d2993eb.gif) ![](RackMultipart20220523-1-3jkuvu_html_cca9aaea0357b0f8.png)

A Commission Criteria Id will be generated:

![Shape159](RackMultipart20220523-1-3jkuvu_html_d39d2526f53c0d85.gif) ![](RackMultipart20220523-1-3jkuvu_html_19e17dd592be84cd.png)

The user can delete a Commission Criteria by clicking on &#39;Delete&#39;:

![Shape160](RackMultipart20220523-1-3jkuvu_html_33df19a8c11c7331.gif) ![](RackMultipart20220523-1-3jkuvu_html_19e17dd592be84cd.png)

### Update Commission:

On the Utina homepage, go to Configuration  Pricing  Commission and click on it. ![](RackMultipart20220523-1-3jkuvu_html_6ab559d00009cd82.gif) :

![Shape162](RackMultipart20220523-1-3jkuvu_html_e199d10f4b8acb15.gif) ![Shape161](RackMultipart20220523-1-3jkuvu_html_68ef3c344804ad82.gif) ![](RackMultipart20220523-1-3jkuvu_html_25357a12b121c503.png)

Click on the &#39;Search&#39; button, and the list of services will be displayed ![](RackMultipart20220523-1-3jkuvu_html_6ab559d00009cd82.gif) :

![Shape163](RackMultipart20220523-1-3jkuvu_html_496c43f07025ec4a.gif) ![](RackMultipart20220523-1-3jkuvu_html_40c7f9350f9b6cfe.png)

Click on one existent commission ![](RackMultipart20220523-1-3jkuvu_html_6ab559d00009cd82.gif):

![Shape164](RackMultipart20220523-1-3jkuvu_html_496c43f07025ec4a.gif) ![](RackMultipart20220523-1-3jkuvu_html_40c7f9350f9b6cfe.png)

The screen will display:

![](RackMultipart20220523-1-3jkuvu_html_ad17f5dd3ffd545a.png)

Modify desired information and click &#39;Update&#39; ![](RackMultipart20220523-1-3jkuvu_html_6ab559d00009cd82.gif):

![Shape165](RackMultipart20220523-1-3jkuvu_html_ceb16dc33b878ce6.gif) ![](RackMultipart20220523-1-3jkuvu_html_ad17f5dd3ffd545a.png)

The user can also modify criteria on the Commission:

![Shape167](RackMultipart20220523-1-3jkuvu_html_8b8317a39d469d71.gif) ![Shape166](RackMultipart20220523-1-3jkuvu_html_3e1f9c4dd3b17bdf.gif) ![](RackMultipart20220523-1-3jkuvu_html_bec860fa11bff020.png)

The user can add a new criteria:

![Shape168](RackMultipart20220523-1-3jkuvu_html_9680f442bbceabf8.gif) ![](RackMultipart20220523-1-3jkuvu_html_bec860fa11bff020.png)

The user can delete a criteria:

![Shape169](RackMultipart20220523-1-3jkuvu_html_614291918368aa6b.gif) ![](RackMultipart20220523-1-3jkuvu_html_bec860fa11bff020.png)

## Pricing pack:

A Pricing Pack encompasses all the pricing elements created above, namely Financial, Service and Commission.

The whole pack will be associated with a predefined offer, and the offer will inherit the entire pack data. So, the offer&#39;s entered data will be overwritten by those of the pack.

### Search:

### Configuration:

The Pricing Pack component starts with the commission creation, by adding the following main data:

Offer Detail

Parameter Filtering

Parameter Value

Criteria

Pricing

#### 4.3.2 Add a new Pricing Pack:

1.On the Utina homepage, go to Configuration  Pricing  Pricing pack and click on it ![](RackMultipart20220523-1-3jkuvu_html_6ab559d00009cd82.gif) :

![Shape171](RackMultipart20220523-1-3jkuvu_html_d1c1ffba55dd2326.gif) ![Shape170](RackMultipart20220523-1-3jkuvu_html_10ac262a68f5a767.gif) ![](RackMultipart20220523-1-3jkuvu_html_25357a12b121c503.png)

2.To add a new Pricing Pack, click the &#39;Add&#39; button ![](RackMultipart20220523-1-3jkuvu_html_6ab559d00009cd82.gif):

![Shape172](RackMultipart20220523-1-3jkuvu_html_97c6ad3e67bf0491.gif) ![](RackMultipart20220523-1-3jkuvu_html_73ba6e70c70020cc.png)

3.A new Pricing Pack screen will be displayed:

![](RackMultipart20220523-1-3jkuvu_html_537d48d115b0c479.png)

4.After completing the following information, click on the &#39;Save&#39; button ![](RackMultipart20220523-1-3jkuvu_html_6ab559d00009cd82.gif) :

![Shape173](RackMultipart20220523-1-3jkuvu_html_251f18350bdf03c7.gif) ![](RackMultipart20220523-1-3jkuvu_html_352adaff5e172a70.png)

An ID will be generated for the new pack; click on &#39;Search&#39; and click on the new created pack ![](RackMultipart20220523-1-3jkuvu_html_6ab559d00009cd82.gif):

![Shape176](RackMultipart20220523-1-3jkuvu_html_e32ad71036c3af15.gif) ![Shape175](RackMultipart20220523-1-3jkuvu_html_e32ad71036c3af15.gif) ![Shape174](RackMultipart20220523-1-3jkuvu_html_a4ed05f092d29731.gif) ![](RackMultipart20220523-1-3jkuvu_html_bc1108a4fb20afec.png)

The screen will display, and the user can add criteria on the Pricing Pack by clicking on the &#39;Add&#39; button ![](RackMultipart20220523-1-3jkuvu_html_6ab559d00009cd82.gif):

![Shape177](RackMultipart20220523-1-3jkuvu_html_7b287501b7d4d7ea.gif) ![](RackMultipart20220523-1-3jkuvu_html_686beebe192680a7.png)

Select a Criteria Code and a Criteria Value and click &#39;Save&#39;; and an ID for that criteria will be generated ![](RackMultipart20220523-1-3jkuvu_html_6ab559d00009cd82.gif):

![](RackMultipart20220523-1-3jkuvu_html_fc20d130b56e0e84.png)

### Update Pricing Pack:

## Offer:

An Offer is nothing more than a specific product that a user offers to its customers for a particular Pricing over a specified period. And it can be attached to a marketing campaign.

The Offer Menu provides the ability to:

- Configure one or more offers;

- Manage Offers;

- View each offer specific details related to this application.

**Note:** All offers can be active at a time.

### Search:

### Configuration:

The Offer component starts with the offer creation by adding the following main data:

- Offer General Data
- Calculation Method
- Rate Information
- Duration
- First Rental Information
- Residual Value Information
- Deferred Interest and Prefinancing Method Information
- Upfront Data

#### Add a New Offer:

_ **This section describes how to initialize and perform simple tasks using the Offer Menu:** _

It is therefore dedicated to the offer configuration throughout the screening.

**To start the Offer:**

1. Access the following URL using a web browser:

[https://dev.utina.io/](https://dev.utina.io/)

Where:

- Hostname: the host or the IP address of the server containing the Utina applications;

- Port: the TCP port number, listening to HTTP requests.

**Note:** The user needs to contact the system administrator for the values that apply to the user organization.

2. Log in to the application by typing the system user name and password.

3. Click OK to start the application.

4. In the Utina homepage, go to Configuration  Pricing  Offer and click on it.

![Shape179](RackMultipart20220523-1-3jkuvu_html_6bb9ee2e78e7c5b2.gif) ![Shape178](RackMultipart20220523-1-3jkuvu_html_1a50982412d8f4ef.gif) ![](RackMultipart20220523-1-3jkuvu_html_6d4ef00aa44b7d59.png)

The Offer menu will be displayed.

### Update an Offer:

## Marketing campaign:

Utina Pricing can be all-inclusive or modular
according to your business needs

<div style="text-align:center;background-color='#00A896;">
<h1>Got a question? <a href='mailto:hello@utina.com'>Get in touch</a></h1>
<p>Utina team of experienced professionals provides all the help and information you need to keep our product working for you.</p>
<br>
<a href='utina.io'> www.utina.io </a>
</div>
