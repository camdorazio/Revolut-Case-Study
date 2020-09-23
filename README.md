# A Case Study on Building a Global Financial SuperApp

![Revolut](Revolut-logo-1.png)<sup>1<sup>

# Overview and Origin

**Revolut** was founded by Nikolay Storonsky and Vlad Yatsenko on July 1, 2015.<sup>2</sup> **Revolut**'s main business idea was to have the ability to send money internationally. **Revolut** offers free, fast, and secure money transfers to a bank account in over 130 countries, and this is done using the real exchange rate you see quoted a traded without any additional fees or mark-ups.<sup>3</sup> **Revolut** has compiled roughly £627 million million since their launch in 2015 with investors including *DST Global*, which was an early backer of *Facebook* and *Spotify*. The company has 29 main investors including, most notably, the tennis star Andy Murray.<sup>4<sup> 

**Revolut** is passively looking to raise an additional USD$500 million to launch a commission free stock trading platform. Storonsky, who is currently acting as CEO, stated in an interview with CNBC, in July 2019, that Japan's tech investment giant, *SoftBank*, could be a "potential partner".<sup>5</sup>

## Business Activities

**Revolut** was founded on the basis of providing secure money transfers to banks globally using a real exchange rate. In 2018, many institutional investors, as well as individual investors, initiated lawsuits against big banks for *"restrained trade, decreased competition, and artificially increased prices"* in the foreign exchange markets ("FOREX").<sup>6<sup> 

The FOREX market is, and has always been, a highly decentralized financial market with, at times, high transaction costs. Since there is no centralized market for FOREX, banks can charge consumers any fee they want almost at will! However, becuase there are many global banks, including central banks, who participate in the FOREX markets, who compete for business from both institutional and individual investors, mark-ups can be quite competitve if you shop around. 

**Revolut**'s original customer target base was the individual consumer and payment processing of FOREX transactions. It is the individual consumer who suffers the most from transaction costs becuase of the small transaction size and banks' inefficiencies in processing small FOREX transactions. Individual consumers, or retail investors, in the FOREX markets make up the smallest portion of all FOREX volume and mainly use the FOREX market to make payments, speculate and/or day trade.<sup>7<sup>

The digital banking amrket, and more specifically the payment processing solution, continues to grow at a steady pace as depicted in the following chart:

![U.S. Payments Digital Payment Market Size](us-digital-payment-market.png)<sup>8<sup>

**Revolut** began with an initial cloud-based solution. The company had a rapid growth spurt since it's launch and developed over 50 applications into it's platform. However, their initial solution started to become overwhelmed as it wanted to automate as many processes as possbile, but deployment became increasing challenging. They bagan to test a range of solutions to find a platform and enviornment that could have continous delivery and be able to release as many applications as possible. The company ultimately decided to use the *Google Cloud Platform* ("GCP"). **Revolut** built its new core infrastructure with *Compute Engine* virtual machines and used *Cloud Identiy and Access Management* to secure their enviorment. They also used *Cloud APIs* along with some other 3rd party tools to fully automate their code deployment and platform management. "Incremental snapshotting is my favorite Compute Engine feature," says Vlad Yatsenko. "With the incremental feature, only the initial snapshot is big. The subsequent snapshots are much more efficient in terms of time and storage. Instead of backups lasting up to twenty hours, we now get a snapshot in around five minutes."<sup>9<sup>

The main solution that **Revolut** is attempting to provide it's customer's is a one stop shop for all things in Personal Financial Services. The current market has fragmented FinTech domains and **Revolut**'s goal is to merge all these FinTech domains into one platform.

### Landscape

**Revolut** currently offers *individual* consumers global payment processing, Crypto coin trading and Vaults, Junior accounts (for children ages 12-17), and has extras such as Budgeting & Analytics, Rewards and Donations. The company also offers the following *business* accounts: 
1. Multi-Currency
2. Corporate Credit Cards
3. Money Transfer and Subscription Payment Manager
4. Automated Payroll Processing
5. Corprate Expense Management and Processing

**Revolut** originally was founded in the Payments/Billing domain of FinTech. As company has experienced tremendous growth it then made it's push into other FinTech domains such as: Personal Finance/Deposits/Online Banking and Blockchain and Cryptocurrencies. The company's quest is to become the first truly global banking superapp and it's currently working on platforms for the following FinTech domains: Investment Management, Wealth Management, and InsurTech.<sup>10<sup>

**Revolut**'s current main competitors include, but not limited to:
1. TransferWire
2. Monzo
3. Starling
4. N26

However, **Revolut** is moving into new FinTech domains that include competitor's such as:
1. RobinHood
2. TradeStation
3. TD Ameritrade
4. Betterment
5. And many, many more!!

**Revolut** has been able to obtain more customers since it's launch that it's main competitor's becuase of the multiple financial service product offering by layering multiple FinTech domains into one application. See below chart.

![Revolut Growth](Revolut Customer Growth.png)<sup>11<sup>


<sup>1 Revolut Logo - https://blog.revolut.com/were-getting-a-fresh-new-look-at-revolut/

<sup>2 https://en.wikipedia.org/wiki/Revolut

<sup>3 Morahan, G. (2019, December 10) *Considering getting **Revolut** Here's what you need to know* Extra.ie https://extra.ie/2019/10/12/business/irish/revolut-heres-need-to-know

<sup>4 Barton, C. (2020, September 2) *Revolut statistics* Finder https://www.finder.com/uk/revolut-statistics

<sup>5 Brown,Ryan (2019, July 5) *Inside **Revolut**'s bid to be the Amazon of banking, and the lessons it's learned from breakneck growth* CNBC https://www.cnbc.com/2019/07/05/revolut-ceo-nikolay-storonsky-on-the-fintech-unicorns-journey.html

<sup>6 Török, L. (2018, November 9) *Lawsuit Levied against Banks over Rigged Foreign Exchange Rates* Veem https://medium.com/small-business-big-world/lawsuit-levied-against-banks-over-rigged-foreign-exchange-rates-5f8e3d459428#:~:text=Institutional%20investors%20filed%20a%20lawsuit,foreign%20exchange%20(forex)%20prices.&text=This%20kind%20of%20opting%20out,they%20sue%20on%20their%20own.

<sup>7 Segal, Troy (2019, October 24) *Forex Market: Who Trades Currency and Why* Investopedia https://www.investopedia.com/articles/forex/11/who-trades-forex-and-why.asp 

<sup>8 Grand View Research (2019, November) *Digital Payment Market Size, Share & Trends Analysis Report By Solution, By Mode of Payment, By Deployment, By Enterprise Size, By End Use, By Region, And Segment Forecasts, 2019 - 2025* Grand View Research https://www.grandviewresearch.com/industry-analysis/digital-payment-solutions-market

<sup>9 Google Cloud *Revolut: Simplifying cross-currency payments with Google Cloud Platform* Google Cloud https://cloud.google.com/customers/revolut

<sup>10 **Revolut** website https://www.revolut.com/en-US

<sup>11<sup> SDK.finance *How to Build a Revolut-like Digital Bank?* SDK.Finance https://sdk.finance/how-to-build-a-revolut-like-digital-bank/#revolut-overview