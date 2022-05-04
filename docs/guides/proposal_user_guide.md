---
layout: default
title: Proposal Component User Guide
parent: Guides
nav_order: 3
---



# Proposal Component - User Guide
{:.no_toc }
# Privacy Policy

The contents of this document are confidential by nature and are to be disclosed only on a need-to-know basis to persons belonging solely to Utina Product.

Any disclosure of the contents of this document to a third party can be done only after a written dialogue with Utina.

Please note that copying, disseminating, or taking any action based on the above information by anyone not intended as the recipient is unlawful.

This document should be considered in its totality for understanding.

# INDEX

{:.no_toc .text-delta}

1.TOC{:toc}

# I. Preface

## 1. About this Publication

This document is a user guide describing Utina&#39;s Proposal component.

The print screens may differ from one user to another. And access rights to procedure, menu, sub-menus, sections and fields are managed by user profiles access rights.

So, for more information about authorization and access rights management, please read: Utina\_Management Company concepts and setup.

## 2. Related Information

For information about Utina products you can visit our official [Website](www.utina.io/)

For information about related component products, make sure to read:

- Pricing Concept Document;
- Document &amp; Checklist Concept and Setup Document;
- Workflow User&#39;s Guide.

## 3. Version History

| **Version** | **Date** | **Author(s)** | **Description** |
| --- | --- | --- | --- |
| 1.0 | 2022-02-04 | Utina | Creation |

# II. Proposal Search

A simplified proposal management process that saves time and resources.

Before starting please note that, in Utina Platform, all Proposals are created from the Proposal menu. And that once one Proposal is activated, it will be transferred to the Contracts Menu.

## 1. Search Process

Through the Client Invoices area, authorized users can search for `Proposals`and process different actions - by simply entering the Proposals menu and starting the search for a specific proposal.

![](/assets/search.png)

A set of search filters is available according to the following criteria:

- Reference
- Linked Contract Reference
- Associated Product (Renting, Leasing, etc.)
- Offer
- Client Name
- Network
- Proposal Phase
- Proposal Status

This way, the user only has to insert some of these filters and then click on the `Search` button, to access the required proposal.

![](/assets/search2.png)

For example, to display a Proposal in the`Analysis` phase, the user has to select the Phase filter `Analysis` and then click on the`Search`button.

![](/assets/search3.png)

The button`Clear` will clear all the applied filters to refine the search.

## 5.Proposal List

Once the user clicks on the `Search` button, the resulting Proposals list will be displayed, with the following data for each Proposal reference:

- Proposal Reference
- Linked Contract Reference
- Product
- Offer
- Client Name
- Network
- Financed Amount
- Status Date
- Proposal Phase
- Proposal Status
- Synthesis: on click, a summary panel will be displaying important data linked to the Proposal (last risk decision, decision level, and related information.)

In the `Contract`field, the user will also see a summary panel with the following information:

- Product
- Collaterals and guarantees on the contract
- Broker
- Asset type
- Financed amount
- Currency
- Term (arrears, in advance)
- First rental date
- End rental date
- Duration
- Rate type
- Rate %
- Total calculated late charges of the contract

Then, the `Actions`button will display the list of available actions he can execute on the Proposal - referring to the verified application rules on the User profile, the Proposal status, and its phase or any other business process.

![](/assets/contract.png)

# III. Proposal Consultation

Once the user enters one of the proposals on the list by clicking in its reference, it will be organized into several sections:

- **Quick Simul**: Financing request inputs (Product, Client, Offer, Pricing, Services, Financed Asset, and related) and outputs (Payment Schedule)
- **Third Parties**: contains the Client Reference, Borrower, Supplier, and the Guarantor. Also, Distribution Network and Channel
- **Invoicing &amp; Payments**: contains the Client Payment Details, Invoice Address, and Proposal Applied Pricing Formulas
- **Assets**: contains the list of Assets references linked to the Proposal
-**Financing Elements**: contains the list of Contractual Financial Elements (Financial Services and Fees)
- **Process Follow-up**: presents the list of executed procedures processed on the Proposal

Additional Information
- **Check-List**: contains the list of the check items linked to the Proposal, to be verified and validated by users
- **Analysis**: contains the scoring files list linked to the Proposal
- **Decision**: lists all risk decisions made on the Proposal
- **Guaranty**
- **Accounting Events**: lists accounting events details linked to the workflow procedures executed on the Proposal
- **Documents**: displays the list of configured documents on the Proposal component satisfying application rules

![](/assets/contractdetails.png)

The buttons available inside the Proposal details area, including all these sections, are:

- The button`Save`to update and save any modification done within the different Proposal sections
- The button`Actions`


## 1. Quick Simulation

The Quick Simul section contains all fundamental inputs to generate a simulation result for a financing request.

![](/assets/POCgraph1.png)

To generate a Proposal Simulation, the user needs to fill in:

- The Product (Loan, Leasing, Master Facility, Real estate, or other)
- The Client: the third party that will be invoiced
- The Investment Amount: for the Leasing product, the investment amount is registered automatically once the Financed Amount is linked to the Proposal
- The Request Date
- The Offer: the Financing conditions carrying feature, including Financing contract elements.

### 1.1 General Information

![](/assets/generalinformation.png)

The General Information section contains the general information of the contract:

- Proposal Reference
- Product: Available Products are:
  * Consumer Loan
  * Loan backed to asset
  * Leasing
  * Renting
  * Master Facility
- Currency
- The Invest Amount: depending on the selected product, the Invest Amount could be a free input field for the user to put the required amount in or the amount will be retrieved once the Asset is added to the Proposal.
- Proposal reference
- Financed Asset
- Proposal Conditions

![](/assets/filters.png)

### 1.2 Financed Asset

The Asset elements section contains all the assets linked to the contract. The details of the assets are already partially filled from the Front Office. All remaining information can be entered in the Back Office during the `Waiting Implementation`and`In Service`phases.

To visualize the Asset detail, click on the hyperlink in the column`Asset Reference`.

### 1.3 Offer &amp; Pricing

![](/assets/offer.png)

### 1.4 Proposal Conditions

The Financial elements section is filled automatically after offer and pricing application. It will contain the core of the contract, and the scheduled financial element (Rental and deferred interest) to be invoiced to the client.

To visualize the element&#39;s schedule, select the line and click on `Action | Calcule the payment schedule`;.

##### Simple Mode

The user is able to use the simple mode section to have an overview on the financial conditions for a linear payment

- Initial start date: contains the estimated start date of the contract
- The billing date
- The rate xxxxx
- Duration
- Deposit
- Upfront
- The Residual value can be entered in percentage or in amount
- xxxxxxx

##### Advanced Mode

The Advanced Mode section is dedicated for complex financial conditions, payment steps, seasonal steps, and others.

All details of the elements are already filled after offer and pricing application.

Mainly, the financial Conditions are:

- Calculation Method: specifies if the contract has fixed payments or has payment steps
- Periodic Rate: contains the periodic rate of the contract
- Financing Amount: contains the elements amount
- Rate Type: contains the rate nature, if fixed or floating
- Rate Formula: contains the rate formula (fixed or floating)
- Residual Value: contains the residual value amount and rate
- Periodicity
- Payment Term: in arrears or in advance
- Rental Amount
- Currency: contract currency
- Period count basis: 365/360
- xxxxxxx

In addition to the financial elements, the contract may contain other elements to be invoiced to the client, such as:

- Admin fees
- Insurance fees
- LC commission
- Others applicable.

### 1.5. Services to Finance

### 1.6. Additional Services and Fees

### 1.7. Commissions

## 2. Third Parties

## 3. Invoicing and Payments

## 4. Assets

## 5. Financing Elements

## 6. Process Follow-up

## 7. Additional Infos

## 8. Check-List

## 9. Analysis

## 10. Decision

## 11. Guaranty

## 12. Accounting Events

## 13. Documents

# IV. Proposal Creation

Automatic processes make it faster to create and review competitive proposals.

For a new proposal creation, it&#39;s necessary to follow these quick steps throughout all the proposal elements, completing all requested information automatically or manually generated.


## 1. Financial Condition level

### 1.1 At Proposal level

The financial element of the Proposal is linked to the Asset list

### 1.2 At Asset level

Each Asset is linked to a financial element in the Proposal

## 2. Products

### 2.1 Leasing and Renting

### 2.2 Loan

###  2.3 Real Estate

The user can also access the Pre-rental element section.
Where Pre-Financing is defined as below:

- Rate Nature: Same as contract
- Rate Value: Contract rate + 2%
- Start Date: should be equal to the value date of the payment done to the supplier (Manually entered)
- Invoicing Frequency: Monthly till the contract activation
- Calculation Basis: total amount paid to supplier – down payment if existing

If a partial payment was made to the supplier, then the sum paid would be the basis of the calculation minus (–) down payment, if existing.

### 2.4 Master Facility

## 3. Syndication

## 4. Offer &amp; Pricings

Offer Application

Pricing Formulas??

## 5. Calculation Methods

Different calculation methods can be applied on the financial element:

### 5.1 Linear Payment

Fixed Payment: all the payments are fixed during the duration of the element

### 5.1 Payment Steps

- **By Steps and Amount**: this calculation method allows the user to fix some steps of the schedule and to ask the system to calculate the remaining ones. In the `Flow`sub-section, specify`By Steps and Amount` in the dropdown list, and the system will display a new sub-section`Step`enter the steps as required, enter the known amounts and check the steps to be calculated by the system; then, click on `Action | Step amount calculation`to calculate the remaining steps.

The payment schedule is generated accordingly by clicking on `Action | Calcule the payment schedule`.

### 5.2 Seasonal Payment

This method applies to cases in which the customer pays specific amounts in a dedicated month of every year as a regular basis.

Let&#39;s see this first case that Utina manages as a seasonal amount repayment: at the level of the financial quote, the user has to define the structure for 1 calendar year; and that structure will be repeated every year from the contract start date until maturity.

Example: 

> For tourism sector, a customer may ask to pay 10000 EUR every September during his lease period for a lease amount of 1M.


On this other case, this is how Utina manages seasonal amount payments: the customer pays specific weightage in a dedicated month of every calendar year as a regular basis.

Example: 
> For tourism sector, a customer may ask to pay 100% from January to November. Then he will pay 80% in December, during his lease period for a lease amount of 1M.``

### 5.3 Weighted Steps Payment

**Weighted Steps**: this method allows the user to have a payment schedule based on weights, by specifying all the steps weight except one. Then the system will determine the weight of that remaining step. At the level of the`Flow`sub-section, in the`Variation rule` dropdown list, select `Weighted Steps`. In the`Step`sub-section, specify the steps with their coefficient, and select a step for which the system has to calculate the weight.

Note that, in case of a rental based on weighted steps, on seasonal payment, both fixed and floating rate are to be used (the system can update the schedule on rate revision date in case of a non-fixed payment plan)

## 6. Third-Party

## 7. Add Asset

It is possible for the user to add more than one asset to the same Proposal.

Create a new Asset by choosing one of the options:

- Add from Catalog
- Add Initial Asset
- Add Asset from Stock

The asset is automatically created after the Proposal creation and saved. All the entered information in the Proposal Office is already filled in. The user only has to complete or amend the remaining information directly in the asset screen.

## 8. Save Process

Once the user saves the filled Client Invoice Data, the system will create the invoice and display the following message:

![](/assets/statussuccess.png)

The system will then generate and display the new invoice reference and the third-party name at the top of the screen.

The Invoice Status will be updated and shown as`Validated`, and the accounting date will be displayed.

# V. Proposal Processes

![](/assets/POCgraph2.png)

| **Step** | **Description** |
| --- | --- |
| 1 | Proposal Creation |
| 2 | The Customer is not interested, the sales representative cancel the proposal |
| 3 | The customer is interest and documents are available, the Sales representative prooceeds with collecting the documents |
| 4 |  The customer is interest and documents are not available, the Sales runs waiting documents to send an email to the customer requesting the missing documents |
| 5 | The sales manager validates the proposal |
| 6 | The Sales Team adds a guaranty |
| 7 | The Analyst manages the proposal |
| 8 | The Analyst creates a scoring file |
| 9 | The Analst proceeds with Analysis and validation of the scoring file |
| 10 | The Analyst decides to cancel the scoring file and creates a new one |
| 11 | The Analyst enters the decision |
| 12 | Risk Manager  Enters decision |
| 13 | The Back Officer prepares the contract |
| 14 | The Back Officer ordres the asset |
| 15 | The Back Officer validates the purchase order |
| 16 | The Back Officer decides to cancel the purchase order and create a new one |
| 17 | The Back Officer launches the Asset Delivery workflow and activates the contract |




## 1. Sales Process

* If the spread is out of the already defined ranges, the deal creator will request an authorization. And a task will be sent to the Head of the Department, who can either accept or reject it:
  - If rejected → a task is sent to the originator to cancel or rework the deal.
  - If accepted → it will go back to the standard workflow.

* If RV is below the minimum, the deal creator will request an authorization. And a task will be sent to the Head of the Department, who can either accept or reject it:
  - If rejected → a task is sent to originator to cancel or rework the deal.
  - If accepted → it will go back to the standard workflow.

* The Proposal Duration will be manually entered by the user and should be within a range of a minimum and a maximum amount. 
If the minimum and maximum are exceeded, a control is triggered: the deal creator will request an authorization. And a task will be sent to the Head of the Department, who can either accept or reject it:

  - If rejected → a task is sent to originator to cancel or rework the deal.
  - If accepted → it will go back to the standard workflow.

## 2. Analysis Process

## 3. Risk Process

## 4. Back Office Process

<div style="text-align:center;background-color='#00A896;">
<h1>Got a question? <a href='mailto:hello@utina.com'>Get in touch</a></h1>
<p>Utina team of experienced professionals provides all the help and information you need to keep our product working for you.</p>
<br>
<a href='utina.io'> www.utina.io </a>
</div>
