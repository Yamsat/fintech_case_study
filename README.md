# Fintech Case Study

## Overview and Origin

* **Name of company**

Company – Ripple Labs Inc.  
Project – RippleNet

* **When was the company incorporated?**

Ripple Labs Inc. was incorporated in 2012.  

* **Who are the founders of the company?**

Jed McCaleb and Chris Larsen started the company. However, Ripple as a payment protocol was first conceived by McCaleb and built by Arthur Britto and David Schwartz, who approached Ryan Fugger, who had conceived the concept of a decentralized monetary system long before McCaleb.

* **How did the idea for the company (or project) come about?**

Ripple started with an idea of decentralizing a monetary system which would free individuals from the stated operated monetary systems. They considered the system should be based on promises by individual users rather than commercial and central banks.

* **How is the company funded? How much funding have they received?**

Ripple’s main source of funding has been sales of their own crypto currency, XPR.  It has sold $1,254.54 million worth of XRP between Q4 2016 and Q2 2020.

Ripple has also raised $293.8M in total through 13 rounds of funding which include angel, seed, series A,B and C and secondary market fundings.




## Business Activities:

* **What specific financial problem is the company or project trying to solve?**

Traditionally banks have been the main provider of cross-border payments. Cross-border payments through the banking network often do not live up to customers’ expectations.  The fees are high and untransparent and it takes days to process and settle payments due to the inefficient system involving of corresponding banks and the outdated messaging protocol. RippleNet aims to solve this problem.

* **Who is the company's intended customer?  Is there any information about the market size of this set of customers?**
**What solution does this company offer that their competitors do not or cannot offer?**

The intended customer for RippleNet is financial institutions (banks and money service providers). 

The global remittance market size is $682.60 billion in 2018 and is projected to reach $930.44 billion by 2026.

RippleNet provides a faster, low-cost alternative to the existing cross-border payment platform which is often criticized as the main culprit for its high, untransparent costs and long processing time of international remittance. 

* **Which technologies are they currently using, and how are they implementing them?**

Thanks to advancing technology, we have a variety of means to transfer money such as electronic bank transfer, credit card, paypal and so on. However, remittance can be processed easily only if a sender and a recipient are in the same network. Remittance across networks are not impossible. But it requires an intermediary who bridges the transaction, which is usually very costly and time-consuming. Among other things the intermediary must be someone we can trust to perform its obligation without failure.

Interledger Protocol (ILP) 

RippleNet is based on an interledger protocol to address these issues pertinent to cross-network payments. ILP uses ledgers that provide an escrow function. A connector is a party which facilitates remittance across different networks. When a sender transfers funds, they are first paid to ledger-provided escrow. When the connector confirms the funds in escrow, they move funds to ledger-provided escrow on the recipient’s side. Once the recipient acknowledges receipt of the funds in escrow, they are paid upon issuing a receipt. With the receipt the sender ensures that the funds have reached the recipient and the funds in the sender’s escrow are released to the connector.

Validation by ledgers of transactions is performed with cryptographic signatures. Asymmetric cryptography makes each transaction secure without trust between a sender, a recipient and a connector. Ledgers escrow funds until a valid signature (private key) is presented for pre-defined public key.

On Demand Liquidity (ODL)

RippleNet provides On Demand Liquidity (ODL) facility in order to smoothly process cross-border payments across different networks.  If we transfer from Japan to USD, market liquidity is not an issue because a large volume of exchange between USD and JPY is occurring twenty-four hours. How about transferring from South Korea to Kenya? The market for KRW/KES is not as liquid as USD/JPY, hence the exchange rate is unfavorable, and it takes more time for the exchange to be settled. For this reason transfers involving exotic currencies are often costly and takes longer to process.

With ODL Ripple provides liquidity by using their own crypto currency, XPR. XPR bridges exchanges between illiquid currencies. In the above example, KRW will be first exchanged for XPR. XPR then will be transferred to the recipient and converted to KES. 

The benefit of using XPR as a bridge currency is cost and speed. Unlike Bitcoin the validation process of blockchains for XPR is not proof of work but consensus mechanism via a group of bank-owned servers. Without the cost and time for proof of work, XPR can be transferred faster and cheaper compared to crypto currencies using mining-based blockchains.

## Landscape:

* **What domain of the financial industry is the company in?**

Cross-border payments

* **What have been the major trends and innovations of this domain over the last 5-10 years?**

Individual customers’ demand, emerging market growth and financial inclusion have shaped the trend of the cross-border payment industry in recent years. They are the groups that have not been well served by banks, the traditionally dominant cross-border payment provider. Most new fintech entrants target this segment of the market by leveraging new technology.

Individual customers traditionally use banks for international transfers because of the large network of branches despite the high, untransparent fees and long processing time.  In emerging economies remittance from banks is more difficult due to difficult access to branches and currency control by the government. Thus, they often bring cash to a shop which is an agent for a money service provider.  These money service providers are large organizations with a global network so that they can make a payment to a beneficiary via an agent in another country.

With mobile technology a network of branches is not an advantage for banks and large money service providers any longer. New fintech remittance companies capitalize on mobile technology. They are able to provide cheaper service because of lower fixed cost they enjoy for not having a large network of branches.

In the backend they often use either their own or third-party’s offshore bank accounts. They make and collect payments using these offshore accounts, which enables them to process transactions faster than transfers via the international corresponding banking network.  

* **What are the other major companies in this domain?**

Wise, OFX, Airwallex

## Results

* **What has been the business impact of this company so far?**

The technologies most fintech companies apply are limited to the frontend.  They use technology to create a user interface that provides customers with better access and experience.  As for the backend (i.e. moving funds across borders), they rely on offshore bank accounts and the corresponding banking network using SWIFT, which banks and money services providers have used for many years. 

On the other hand, RippleNet applies new technologies to the backend in order to offer better customer experience. It provides a new infrastructure for cross-border payments that has potential to replace the legacy corresponding banking network and become a new standard.

* **What are some of the core metrics that companies in this domain use to measure success? How is your company performing, based on these metrics?**

The core metrics to measure success in this domain are cost, speed, network, security, user interface and compliance (AML/CTC).

Financial institutions using RippleNet are successful in reducing cost and processing time significantly hence offer better customer experience.  Using RippleNet has opened up new networks or makes access to their existing networks faster and cheaper. For example, [MercuryFX](https://www.mercury-fx.com/) has reduced the cost to transfer to Mexico from $50 to $2 and is able to settle the transaction 100 times faster.

RippleNet achieves high level of security. The architecture of ILP eliminates counterparty and settlement risks. In RippleNet all information regarding a remittance is exchanged between sending and receiving institutions before remittance is executed, which reduces operational risk significantly. On the other hand, for remittance using SWIFT, remittance and transmission of information are performed simultaneously and separately, which is subject to operational errors.

Currently RippleNet is not offered directly to consumers but only to financial institutions providing cross-border payment services.  User interface is not relevant as a measure for success. 

In terms of AML/CTF management RippleNet relies on its users (i.e. financial institutions). Its seamless integration with banks’ AML/CTF system reduces the risk of incompliance caused by a system defect of RippleNet.  However, this also means that if the system of a user bank fails to identify the risk, RippNet is also unable to detect it.


* **How is your company performing relative to competitors in the same domain?**

Due to the nature of its service the major competitor is considered to be SWIFT. As SWIFT has been used by banks for decades, it is a big challenge for RippleNet to threaten the dominant position of SWIFT.  SWIFT also is trying to respond to its customers’ requirements and growing competition by innovation such as SWIFT global payments innovation (gpi).

## Recommendations

* **If you were to advise the company, what products or services would you suggest they offer?**

I would suggest they launch their own platform for consumers where they can directly use RippleNet. 


* **Why do you think that offering this product or service would benefit the company?**

Since banks have used SWIFT for decades, it would take long for them to adopt RippleNet due to the huge switching cost.  As a switching cost for individual customers is relatively low, they could increase individual customers faster.  

* **What technologies would this additional product or service utilize?**

Mobile and web technologies would be utilized.

* **Why are these technologies appropriate for your solution?**

To introduce a new service to consumers, an easy-to-understand, user-friendly application is a key.


## Addendum

References  
https://www.ig.com/au/news-and-trade-ideas/forex-news/who-is-the-ripple-founder--41717-180122
https://en.wikipedia.org/wiki/Ripple_Labs
https://en.wikipedia.org/wiki/Ripple_(payment_protocol)
https://www.crunchbase.com/organization/ripple-labs/company_financials
https://www.alliedmarketresearch.com/remittance-market
https://ripple.com/insights/interledger-beyond-blockchain/
https://orbilu.uni.lu/bitstream/10993/39731/1/Deep_dive_into_Interledger.pdf
https://interledger.org/interledger.pdf
https://www.ey.com/en_gl/banking-capital-markets/how-new-entrants-are-redefining-cross-border-payments
https://ripple.com/customer-case-study/
https://ripple.com/compliance/

