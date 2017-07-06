# Brickblock General Whitepaper

by Jakob Drzazga, Martin Mischke, Holger Schlünzen, Philip Paetz

### Abstract
Brickblock is building a new blockchain-based solution for investing in exchange-traded funds (ETFs), real estate funds (REFs), passive coin-traded funds (CTFs) and active coin managed funds (CMFs). Through the effective use of smart contracts, order and issuing fees can be reduced to a fraction of traditional costs. This will make investing in Brickblock more financially inclusive across all income classes. Artificial geographical trading restrictions, including the need for a bank account, can thus be eliminated. Counterparty risk can be reduced to mere minutes. Furthermore, we are introducing a new system of passively managed cryptocurrency baskets, which reduces the risks and high fees of actively managed coin funds by using liquidity providers, incentivized by arbitrage effects. Our system is based on an underlying rule-based asset allocation rather than high-risk contracts for difference (CFDs). It uses the asset-first principle, which incentivizes asset vendors to deliver assets before getting paid, thus further reducing investor risk.

### Table of Contents
- [1. Introduction - How does Brickblock work?](#1-introduction---how-does-brickblock-work)
- [2. Market Analysis](#2-market-analysis)
  * [2.1. Current Problems in the Market](#21-current-problems-in-the-market)
  * [2.2. How does Brickblock addresses current problems?](#22-how-does-brickblock-addresses-current-problems)
  * [2.3. Market Review](#23-market-review)
  * [2.4. Difference to Existing Projects](#24-difference-to-existing-projects)
- [3. Who is Brickblock for?](#3-who-is-brickblock-for)
  * [3.1. Private Investors](#31-private-investors)
  * [3.2. Institutional Investors](#32-institutional-investors)
  * [3.3. Fund Managers](#33-fund-managers)
  * [3.4. Broker-Dealers](#34broker-dealers)
  * [3.5. Commercial Paper Issuers](#35-commercial-paper-issuers)
- [4. The Platform](#4-the-platform)
  * [4.1. Tradeable assets on Brickblock](#41-tradeable-assets-on-brickblock)
  * [4.2. Technical Setup](#42-technical-setup)
- [5. Tokens](#5-tokens)
  * [5.1. Brickblock Tokens](#51-brickblock-tokens)
  * [5.2. Access Tokens](#52-access-tokens)
  * [5.3. Proof-of-Assets (PoA) Tokens](#53-proof-of-assets-poa-tokens)
- [6. Conclusion and Vision](#6-conclusion-and-vision)
- [Glossary](#glossary)

## 1. Introduction - How does Brickblock work?

At present, the crypto-economy is possibly one of the most volatile
economies. Investors can make 10x gains in one month only to lose it all
the next month. Thus far, there have only been a limited number of ways
to diversify crypto-portfolios to mitigate these risks. Real
diversification, across multiple asset classes, is essential for a
well-balanced portfolio.

Brickblock introduces the first platform where users can seamlessly
invest in real estate funds (REFs), exchange-traded funds (ETFs),
passive coin-traded funds (CTF) and active coin managed funds (CMFs)
through a streamlined process and with significantly lower costs than
traditional investing.

Each fund on the Brickblock platform has its own denomination and its
own “proof-of-asset” (PoA) token which, via established token exchange
platforms, can be traded simpler, faster and cheaper than on
conventional stock markets. Our asset-backed PoA tokens empower
investors to hedge the risk of cryptocurrencies in real assets without
needing to convert their cryptocurrency into a fiat currency. All
dividends and coupons are automatically transferred to token-holders
through self-executing smart contracts on the Ethereum network. The
content of the smart contract and the PoA token itself is unalterable,
cryptographically secured and visible to everyone on the blockchain.

To ensure the safety of the underlying assets represented by the PoA
token, a digital trust fund holds the exact same amount of fund shares
as tokens issued. This securities account cannot be claimed by
Brickblock, the broker or anyone else, and is protected by strict laws
regarding trust funds, even in the case of bankruptcy. Only token
holders may reclaim their fund shares, at any time.

Brickblock’s infrastructure will be implemented as a decentralized
application (Dapp) and run on the Ethereum network. Broker-dealers and
fund managers will be able to list their investment opportunities on the
platform, after being thoroughly verified by Brickblock through e.g.
proof of residence, credit reports and criminal record. Based on their
personal risk/reward ratio, investors can then select an investment from
the offered funds to add to their diversified portfolio. All fees,
minimum investment pools, exchange rates, holding periods, net asset
values, dividends or coupon payments will be listed clearly and thus,
can easily be compared. All investment opportunities will be carefully
validated and audited by independent parties (such as [EY](https://www.ey.com/)) to
eliminate fraud.

## 2. Market Analysis

### 2.1. Current Problems in the Market

#### 2.1.1. High Volatility

Cryptocurrencies are extremely volatile and, due to their limited
acceptance in the traditional economy, investors have almost no options
to disperse their risk.

Money has three important properties: It serves as a store of value, a
medium of exchange and a unit of account. Currently, cryptocurrencies
are primarily used as a store of value. The use of cryptocurrencies as a
medium of exchange and as a unit of account is still in a very early
stage. This means that there are limited options to escape the
volatility of its value. At present, the only real way out is to
reconvert into a fiat currency.

#### 2.1.2. Counterparty Risk

When the counterparty does not possess the necessary funds or assets to
settle a trade, this is known as “counterparty risk”, also “default
risk”.

In traditional asset trading, clearing and settlement processes take
three days. On the first day, a broker makes a deal with the
counterparty on the basis of trust. Based on this trust, the broker then
makes countless other trades that all depend on the first trade actually
being settled. On the second day, the clearing house logs the price,
amount and payment method of the assets into its network. Only on the
third day, two days after the actual trade, does the settlement and the
exchange of delivery versus payment (DVP) actually occur.

#### 2.1.3. High Costs and Complexity in Conventional Stock Trading

Trading fees, broker-assisted fees, account maintenance fees, account
transfer fees, selling fees and commission fees at various stages are
standard costs to consider when buying real-world assets through a
retail broker. In addition to the complexity of determining which costs
apply to which assets, minimum fees apply that make investing small
amounts unprofitable and exclude lower income groups from participating
in the market. Percentage-wise, a user that can only invest $100 in an
ETF pays a significantly higher fee than a professional trader investing
$100,000 - we think this is unfair and want to level the playing field
here.

#### 2.1.4. Trading Restrictions

It is highly complicated or even outright impossible for private
investors to buy ETFs or REFs in some countries due to insufficient
connectivity to worldwide exchanges. Investors need expensive bank or
broker accounts and are severely limited in their freedom to trade by
local governments. Furthermore, vastly different tax structures penalize
worldwide investors.

#### 2.1.5. No Safe Possibility of Crypto Basket Investments

To date, no secure and easy way to invest in a crypto-basket with **full
market exposure** in exchange for a single token exists. One must trust
a fund manager to allocate the assets and not take advantage of their
position; there is no legally binding contract between investors and
fund managers. Indeed, there are no agreed-upon verification processes
for fund managers or *any* form of regulation. Investors are solely
dependent on trusting that fund managers spend their funds how they said
they would.

### 2.2. How does Brickblock addresses current Problems?

#### 2.2.1. High Volatility

By enabling the direct purchase of real-world assets, such as ETFs and
REFs, with Ethereum, we are offering a simple way to hedge against
volatile crypto-portfolios with low beta asset classes.

<img src="https://github.com/brickblock-io/whitepaper-general/raw/master/img/beta-formula.png" height="40" />

#### 2.2.2. Counterparty Risk

By using the blockchain for clearing and settlement processes,
Brickblock reduces counterparty risk exposure from multiple days to less
than 1 minute, or more precisely: to the length of a few [Ethereum block
confirmations](https://etherscan.io/chart/blocktime).

#### 2.2.3. High Costs and Complexity in Conventional Stock Trading

Through a high degree of automation, blockchain technology and the use
of smart contracts, we are able to bypass a number of third parties,
such as clearing houses and retail brokers. This allows us to reduce the
fees associated with buying and selling real-world assets down to a
fraction of traditional retail brokers. Depending on the country of
purchase, the specific asset and the investment amount, Brickblock is
able to offer up to a **50-fold discount** on the initial purchase
price. If the asset is then subsequently sold on token exchanges, this
discount can easily increase to 150-fold. An in-depth comparison of
Brickblock fees vs. traditional broker fees is available [on our
blog](https://medium.com/@Brickblock/brickblock-will-lead-the-way-in-making-investing-more-financially-inclusive-around-the-world-97952f80925d).

#### 2.2.4. Trading Restrictions

No bank account is needed to trade global ETFs and REFs since no
geographic borders apply. This enables Brickblock to offer the cheapest
ETFs and REFs worldwide and the most economical way of order execution.

#### 2.2.5. No Safe Possibility of Crypto Basket Investments

For actively managed CMFs, Brickblock will enter legally binding
contracts with fund managers, verify them thoroughly and implement a
cryptographic audit structure. We, not the fund managers, will
commission independent auditors to prevent any potential conflicts of
interest between fund managers and auditors.

For passively managed CTFs, rule-based fund indices in conjunction with
the arbitrage phenomenon of foreign exchange (FX) markets are leveraged
to obviate active fund managers and decentralize trades toward liquidity
providers. Therefore, human error is minimized.

### 2.3. Market Review

In the past years, many token-funded startups have announced the
development of financial tools to help traders and investors diversify
within the crypto-currency market. In this section, we are going to
examine several of these projects and highlight possible improvements.
However, the purpose of this is not to devalue the competition, we
merely seek to illustrate our motivation for developing our own
solution, i.e. to address these problems. We have the highest respect
for everyone that is sincerely trying to move the crypto-community
forward and deeply believe that there is enough room for many innovative
players in this field.

#### 2.3.1. Taas

[Taas](https://taas.fund) is a stand-alone, closed-end crypto-fund. Its [whitepaper](https://taas.fund/media/whitepaper.pdf) states that they have built a cryptographic audit system with
[Ambisafe](https://www.ambisafe.co). Users are able to track the trades of Taas on their
website. We could not find any details about this system besides the
trade records, which are made public on a [subpage](https://ca.taas.fund/wallets/dashboard). From an investor’s perspective, however, there is **no legal contract** between
the user and Taas, which carries potential risks.

#### 2.3.2. Melonport

[Melonport](https://www.melonport.com) is an open source protocol (initially based on
Ethereum and currently in development) that aims to simplify the process
of developing portfolios of different cryptocurrencies for investors.
Fund managers, on the other hand, can easily select what
cryptocurrencies they want to buy. In comparison to Taas, the Melon
Protocol, if executed safely in smart contracts, will eliminate the
trust aspect. However, as far as we could interpret from the [green paper](https://github.com/melonproject/greenpaper/blob/master/melonprotocol.pdf), it is mostly based on contracts for difference (**CFDs**) for
non-ERC20 tokens and coins. Since investments can only be made in Melons
or ETH, users are heavily dependent on the stability of these two
tokens. If, for example, a fund manager purchases a certain volume of
[Dash](https://www.dash.org/blockchain-explorers/), no actual Dash tokens are being held by the user. From an investor’s perspective, this means that there is a potential risk of not
receiving the equivalent value of Dash if the Melons or ETH collateral
cannot cover the gains or losses.

#### 2.3.3. Shapeshift’s Prism

[Prism](https://info.shapeshift.io/blog/2017/05/21/introducing-prism-worlds-first-trustless-portfolio-market-platform) is also based on Ethereum. The user and a counterparty
both deposit an equal amount of ETH into a Prism smart contract, which
serves as collateral and is therefore also a contract for difference
(**CFD**). The user bets, for example, on a bullish bitcoin (or any other cryptocurrency offered by Shapeshift’s Prism) and the counterparty bets on a bearish bitcoin. This all works well if ETH is
the users’ domestic currency. However, if, as is the case for most
investors, fiat currencies (like USD or EUR) are the users’ domestic
currency, then one could actually lose money. One could lose money even
if they predicted the correct market movement of bitcoin, because the
user’s collateral will always be ETH regardless of the price. On the
other hand, the user’s profit is capped at 100% gains, because Prism’s
collateral matches the user’s. Thus, if one were to bet 1 ETH on Dash
and Dash tripled in price, the maximum gain would not be 2 ETH but only
1 ETH.

#### 2.3.4. Digix

To the best of our knowledge, we are the first platform to build the
necessary infrastructure to tokenize ETFs and REFs. The most comparable
start-up to date, however, is [Digix](https://www.digix.io). Digix, which is currently
in development, tokenizes a real-world asset: physical gold. After
depositing ETH into a smart contract, a new DGX token is created and the
asset vendor delivers the gold to a custodian. An auditor then regularly
verifies whether the gold is still in possession of the custodian. In
the [last whitepaper](https://dgx.io/whitepaper.pdf) we could find, it seems that Digix’s asset vendors receive investors’ funds before investors receive their gold.
For example, if a great amount of gold is bought in a bearish
crypto-market, the vendor either has to lend the money and wait until
the audit is completed to receive investors’ funds or the vendor
receives the **payment in advance**, which constitutes a potential risk
for the buyer.

#### 2.3.5. Proof Suite

[Proof Suite](https://www.proofsuite.com) is focusing on developing blockchain tools for
tracking real-world assets. In their whitepaper, they present the
benefits for companies and governments to replace existing systems with
Proof Suite. They are trying to reduce bureaucratic procedures and make
transactions more efficient. Nevertheless, they **rely on change
occurring within companies and the legal acceptance** of their
technology. Thus, if two parties were to trade real estate with Proof
Suite and one of the parties decided to sell the same real estate to
another party on the traditional market, legal problems occure.

### 2.4. Difference to Existing Projects

#### 2.4.1. Legal Enforceability of Claims

Brickblock enters a **legally binding contract** with every fund manager
and every broker-dealer. In contrast to direct and trust-based
investments in fund managers, this adds an additional layer of security
for investors. On the Brickblock platform, every fund manager has a
direct liability to the investor, which is enforceable through legal
action.

#### 2.4.2. Full Market Exposure

We believe that CFDs and other derivatives rely too much on trust and
moderate price trends. In the world of cryptocurrencies, where [flash
crashes](https://blogs.wsj.com/moneybeat/2017/06/23/ethereums-flash-crash-shows-hazards-of-trading-cryptocurrencies/) and price movements of &gt;200% on a single day are a
regular phenomenon, we consider CFDs no suitable instrument for mid- and
long-term investments. Thus, **Brickblock only allows physical shares,
commodities and currencies** instead of betting on derivatives.

#### 2.4.3. Escrow-backed Security for Investors and Brokers (asset-first principle)

Brickblock’s smart contracts will only **release investors’ funds to the
broker-dealer after the broker-dealer transfers the assets** to the
digital trust fund. This represents a new way of conducting clearing and
settlement. Through automated smart contracts, the broker-dealer
receives the investors’ funds immediately after transmitting the assets.
Initially, until new broker-dealers trust Brickblock’s asset-first smart
contracts, Brickblock will deposit the investor’s funds in escrow as
collateral. Therefore, if a smart contract does not activate, the
broker-dealer can claim the escrow.

#### 2.4.4. Connecting Old and New Economy

Brickblock builds a bridge from the traditional investment world into
the digital realm. We are leveraging existing infrastructure to enable
faster adoption of this new system. All Brickblock transactions are
legally accepted and enforceable in a court of law.

We believe a transition from old to new is best achieved by **building
bridges**, not burning them.

## 3. Who is Brickblock for?

### 3.1. Private Investors

Most importantly, Brickblock will help private investors diversify their
portfolios beyond cryptocurrencies and tokens, reducing the overall
risk. In addition to other benefits, this helps:

-   Significantly lower the costs of investing in REFs, ETFs, CMFs and
    CTFs through cutting out the middlemen and pooling investment
    volume,

-   Create steady returns in the form of dividends and coupons,

-   Hedge the systemic risk of a heated market,

-   Clarify fees, tracking errors and liquidity,

-   Minimize bureaucratic overhead,

-   Empower **everyone** to invest directly in global funds in every
    market, regardless of where funds or investors live.

### 3.2. Institutional Investors

Brickblock will help institutional investors invest their funds in a
diversified digital currency portfolio without having to worry about
holding multiple wallets and handling a multitude of exchange platforms.

### 3.3. Fund Managers

#### 3.3.1. Real Estate Fund Managers

Real estate fund Managers are responsible for a variety of tasks. Some
of the most important of which are: supervising real estate acquisition;
evaluating consultants, appraisers and property managers; designing
financial models and formulating asset allocation strategies.

In the traditional system, fund managers must pay enormous provisions to
banks to sell their funds to customers, which is only possible if the
fund is large enough. For smaller funds, which cannot afford to pay for
distribution, their only chance is to maintain all investor
relationships themselves. This represents a significant competitive
disadvantage, since this costs significantly more time, which then
cannot be spent increasing the rentability of the fund. Brickblock
enables immediate global distribution, reducing fund costs, increasing
profitability, lowering fund managers’ workload and overall, leveling
the playing field.

#### 3.3.2. Coin Managed Fund Manager

Coin managed fund managers, either professional or social, gain a
platform for advertising their past performance and attracting new
investors. Coin managed fund managers can freely set their management
fee structure and have Brickblock as a legal and trustworthy entity whom
they can contract. Brickblock is interested in productive professional
relationships and will help fund managers establish the initial
management structure. Furthermore, Brickblock will work with third
parties to pro-actively reduce potential legal and cyber security risks
associated with the responsibility of being a fund manager.

### 3.4.Broker-Dealers

Broker-Dealers, sometimes also referred to as “market makers”, are
liquidity providers at traditional stock exchanges. Most large
institutional ETF block trades do not take place at exchanges, but
over-the-counter (OTC) and are not visible to the public. This is
especially the case for illiquid exotic ETF underlyings. In contrast to
the immediate execution on exchanges, broker-dealers prefer to be asked
for the price of specific products and quantities. They prepare all
background hedging and internal risk exposure analyses before quoting
and executing an order. The quoted price is often better than the bid
ask offer on exchanges.

The digital trust “request for quote” (RFQ) issued by the smart contract
can be parsed and tokenized in a variety of industry standard formats,
such as [FIX](http://www.fixtradingcommunity.org/pg/structure/tech-specs) ensuring compatibility with existing processes and legacy integrations. Brickblock acts as a single counterpart against the broker-dealer. This simplifies compliance and set-up processes for
broker-dealers. Brickblock will assist broker-dealers with a dedicated
e-wallet application programming interface (API) solution.

The focus is to radically reduce operational costs and enable delivery
versus payment (DvP) support, including crypto-payments. Compliance
costs (e.g. maintenance of segregated accounts), onboarding, settlement
and know your customer (KYC) processes are also included, where
applicable. The key is that broker-dealers are free to focus on the core
business. Broker-dealers profit by increasing their trading volume of
securities, and Brickblock improves the liquidity of the crypto-economy.

### 3.5. Commercial Paper Issuers

Brickblock will help issuers enter the crypto-economy by integrating
existing asset management legacy infrastructure and messaging standards
for both issuance and distribution. There is a strong incentive in
conventional paper issuance to move toward lower cost distribution
models and reach international marketplaces.

## 4. The Platform
### 4.1. Tradeable assets on Brickblock

After choosing a fund, the user deposits the payment into a smart
contract. The smart contract controls all fees, minimum investment
pools, exchange rates, holding periods, net asset values, dividends or
coupon payments. Therefore, depending on the asset class, there are
three different scenarios.

#### 4.1.1. Real Estate Funds (REFs)

Investing in real estate comes with major diversification potential,
depending on both the users’ foreign exchange (FX) exposure and tax
domicile. Our platform will enable fund managers to list real estate
projects with high potential and help users to easily discover
interesting opportunities. Each project will be carefully audited by
independent parties to minimize fraud.

Real estate funds (REFs) are actively managed by a fund manager.
Depending on its underlying focus, the fund manager acquires a certain
volume of real estate in certain cities, countries or continents across
the globe.

Real estate has two growth functions. First, there is the value of the
real estate itself, which may potentially grow over time. Second, real
estate produces a steady income in the form of rent, which is
distributed to its shareholders via smart contracts or re-invested in
new real estate, depending on user preference. By choosing a fund, users
can influence the frequency of distributions and other factors such as
costs and fees, area of investment, net asset value (NAV) and minimum
investments.

Brickblock will start with European REFs and subsequently extend into
more locations. After the processes for REFs are established, we will
further broaden the investment scope to also include real estate
investment trusts (REITs) and real estate crowdfunding.

#### 4.1.2. Exchange-traded Funds (ETFs)

Exchange-traded funds are an interesting store of value for many
investors. Unlike actively managed funds, the fees and costs are
significantly lower since ETFs passively track rule-based indices like
the S&P 500, the Nikkei or the Dax 30. Exchange-traded funds can also
track commodities like gold and silver and have the advantage of being
offered at near-wholesale prices without minimum purchase amounts.
Exchange-traded funds [outperform the returns of most actively managed
funds](https://www.justetf.com/uk/news/passive-investing/the-proof-that-active-managers-cannot-beat-the-market.html) that invest in company shares and enable investors to
diversify their portfolio, even with very little capital. By choosing
their preferred ETFs, investors can actively decide in which markets to
invest and spread their risk across different geographic locations and
industries.

Brickblock will start with the ETFs that track global indices and will
then inquire after the community as to which ETFs to implement next.
Brickblock will establish connections with and request quotes from
different broker-dealers based on past pricing performance. This
guarantees the best execution of orders.

#### 4.1.3. Coin Managed Funds (CMF)

Actively managed CMFs provide projects like Taas [@ref5] the opportunity
to offer their funds to the public. Fund managers can manage investors’
funds by selecting specific cryptocurrencies, day-trading, taking
profits out of diversifying portfolios and the active distribution of
funds. Conversely, users can decide which strategies and fund managers
to trust. Each project will be carefully audited by independent parties
to significantly minimize the risk of fraud.

#### 4.1.4. Coin-traded Funds (CTF)

Brickblock offers passively managed CTFs and tracking rule-based indices
designed by fund managers and community members. One of these could be a
Top 10 cryptocurrencies market cap CTF. The index would include the Top
10 cryptocurrencies weighted by market capitalization. Since no passive
CTF currently exists, we are introducing a system based on passive ETFs,
as explained in section \[CTFtext\]

Further, a separate non-profit organization (NPO) is set up; leading
members of the crypto-finance community are invited to join us in
improving the system and standardizing processes.

### 4.2. Technical Setup

The following framework describes the underlying technical processes.
Our platform will be developed as a Dapp on top of the Ethereum
blockchain. The Dapp will guide users through all of the investment
steps. All Ethereum transactions relevant to Brickblock will
additionally be backed up on our own blockchain, with only one public
node for security reasons.

#### 4.2.1. Real Estate Funds (REFs) and Exchange-traded Funds (ETFs) 
Figure 1 displays the detailed process of investing in real-world assets such as REFs and ETFs.

<img src="https://github.com/brickblock-io/whitepaper-general/raw/master/img/order-process-flow-etfs-rtfs.png" width="800" />

*Figure 1*

After choosing an asset class, either REF or ETF, users can select a
fund based on their investment preferences. Users will be informed about
fees, frequency of distributions, areas of investment, current net asset
value (NAV), minimum investment volume, performance or track record.

Once users select a fund, they will be asked to deposit the desired
investment amount into a smart contract. A minimal creation size helps
reduce transaction costs and decouples the PoA tokens from the nominal
value of the fund. After reaching the minimal creation size, the
broker-dealer places a fund order. The purchased securities are then
deposited into a digital trust fund by the broker-dealer.
Simultaneously, the custodian of the digital trust fund issues a
cryptographically signed electronic document confirming the receipt of
assets. This document is verified by the smart contract to ensure that
the broker-dealer’s order matches the user’s order. If the orders match,
the smart contract treats this as proof that the broker-dealer’s
obligations are properly fulfilled. The smart contract subsequently
releases the user’s deposited funds to the broker/dealer, and a PoA
token to the user. This token serves as a proof of assets.

The digital trust fund is only allowed to hold the securities for the
actual beneficiary of the PoA token. If PoA token holders want to sell
their assets, they can sell the PoA tokens on token exchanges like
EtherDelta, iDex, 0x or withdraw the securities from the digital trust
fund at any time after going through a KYC process provided by the bank.
If dividends or coupons are issued by the fund, the custodian of the
digital trust fund will send these proceeds to the self-executing smart
contract, which will automatically allocate them to the respective token
holders.

#### 4.2.2. Active Coin Managed Funds (CMFs)
Coin managed fund managers will be able to offer funding campaigns on
our platform and manage funds by investing in different
cryptocurrencies. A cryptographic audit infrastructure will thoroughly
verify every new individual through, inter alia, proof of residence,
credit report and criminal record. Furthermore, all trades will be
recorded and stored safely. Users can choose between:

1.  Fund managers who use **secured accounts**

    Users’ funds are transferred to secured accounts at trustful
    exchanges, where withdrawal functions are blocked. Users then
    receive PoA tokens in exchange for their funds. Through the use of
    secured accounts, the risk of fraud and private key loss are
    minimized.

2.  Fund managers who use **unsecured accounts**

    For digital assets that are not traded over common exchanges, the
    fund manager receives the users’ funds from the smart contract into
    an unsecured account, controlled by the fund manager. Users again
    receive a PoA token in exchange. In this case, the legal contract
    between Brickblock and the fund manager protects users from fraud.
    In case of any irregularities, Brickblock is able to enforce users’
    claims through legal action.

The crypto-backed PoA token represents the invested funds actively
managed by a fund manager. The fund manager diversifies the received
funds into various other cryptocurrencies and tokens.

Fund managers can choose from different fee structures: percentage of
gains, percentage of funds managed or a fixed fee. Users can then choose
a fund manager based on compliance with their desired fee structure and
risk/reward ratio.

After a predetermined trading time window, funds are transferred back to
the smart contract, which then forwards them to the users’ Ethereum
wallets, minus the fund manager’s fees.

#### 4.2.3. Passive Coin-traded Funds (CTFs) {#CTFtext}

The CTF concept maps the efficient ETF mechanism onto the blockchain. A
CTF is a smart contract that tracks an underlying index of crypto-assets
as closely as possible. The holdings of the digital trust fund, in the
form of crypto-wallets, are stored in cold storage by a custodian. This
is necessary because an Ethereum smart contract currently cannot
reliably handle automated transactions with other blockchains. A CTF
provides both a creation and a redemption basket, necessary for creating
and redeeming tokens. The composition of these baskets helps rebalance
the funds’ holdings according to the underlying index.

The user first decides whether to buy the token via an exchange trade or
using the creation mechanism.

##### The Trading Process

The investment process for passive CTFs is similar to investing in REFs
and ETFs. Figure 2 illustrates the process flow in detail.
Users can choose between different indexing methods designed by fund
managers. The index is the basis for the CTF composition and determines
risk and performance. Brickblock will support users by providing CTF
factsheets with holdings, past performance and tracking quality of the
CTF.

<img src="https://github.com/brickblock-io/whitepaper-general/raw/master/img/order-process-flow-existing-ctf-tokens.png" width="800" />

*Figure 2*

##### The Creation Process

To prevent trading and therefore, trading fees inside the CTF, we
utilize liquidity providers (LPs). The LPs hold PoA tokens in their
account and sell them on exchanges. Furthermore, LPs can create and
redeem tokens from the fund. Figure 3 illustrates the
process flow in detail. Tokens are created by sending the components
specified in the creation file to the custodian and the correspondent
wallet addresses. If the correct basket is delivered to the wallets, an
automated message is sent to the CTF smart contract and the PoA token is
released. Liquidity providers help minimize the running costs of trading
and rebalancing inside the fund and take advantage of arbitrage effects
on the market.

If the CTF fund accepts cash redemptions (paying out ETH for PoA
tokens), existing PoA token holders are charged for the resulting
trading costs and thus, penalized. Therefore, LPs receive the assets of
the redemption basket in return for the PoA token and must manage the
trading themselves.

Rather than buying PoA tokens via an exchange, users are allowed to use
the creation mechanism as long as they hold all necessary assets.
However, for unprofessional users, it is more convenient to buy already
created tokens on token exchanges.

<img src="https://github.com/brickblock-io/whitepaper-general/raw/master/img/order-process-flow-create-new-ctf-tokens.png" width="800" />

*Figure 3*

All CTF-relevant entities are listed below:

##### Users/Investors

select in which CTF to invest and can trade PoA tokens on token
exchanges. Moreover, users are allowed to create tokens by sending a
“creation unit” to the CTF smart contract and receiving PoA tokens of
the same value in return.

##### Liquidity Providers (LPs)

are at the center of the creation and redemption process of PoA tokens.
They have the right to redeem PoA tokens against the fund’s holdings. To
reduce trading within the CTF and save on transaction fees, the
redemption units are consolidated into blocks of 5,000 tokens. Like
users, LPs can create tokens by delivering the creation basket to the
fund (the custodian wallets). In exchange, they receive the same value
in PoA tokens.

The LPs act as market makers on exchanges. To properly fulfill this role
and react in a timely manner, the LPs hold PoA tokens in their own
accounts. LPs act as a buffer between the investor and the fund. The
number of LPs for one CTF is unlimited.

##### Coin-traded Fund Smart Contracts

seek to replicate the index as closely as possible. They publish the
creation and redemption baskets on a daily basis. The baskets describe
the assets necessary to create new tokens, or those which the LPs
receive when a PoA token is redeemed. The creation and redemption
baskets are designed to adjust the assets to the underlying index.

##### Creation/Redemption Files

describe the creation basket. It is the composition of the coins or
tokens for creating new PoA Tokens. The creation/redemption file is
released by the CTF smart contract.

##### Underlying Indices

are the heart of the CTF. The CTF tries to track the index as closely as
possible without tracking errors or differences. The methodology and
rules of the index are designed by fund managers or index providers.
These rules can be market-cap oriented, factor or momentum strategies.
Every blockchain asset can be included within the index.

##### Custodian

The custodian holds the different crypto-wallets in cold storage. The
transactions are automatically sent to the CTF smart contracts, which
confirm receipt of the correct creation basket.

## 5. Tokens
There are three types of tokens, all of which implementing the [ERC20
token standard](https://github.com/ethereum/EIPs/issues/20). Detailed information about volume, distribution mechanism and the price of tokens will be released separately ahead of
the contribution period.

### 5.1. Brickblock Tokens
Brickblock tokens will only be released during the contribution period
in exchange for ETH and Bitcoin. If the Brickblock tokens are stored in
a special smart contract, the Brickblock token holder will receive a
certain amount of access tokens per week until the Brickblock tokens are
withdrawn from the smart contract.

### 5.2. Access Tokens
Broker-dealers and fund managers need access tokens to list their fund
on the Brickblock platform and to pay market-determined Brickblock fees
when REFs, ETFs, CMFs or CTFs are sold. The access token is then burned.
Brickblock will determine the amount of access tokens based on supply
and demand.

Brickblock is incentivized to establish the amount of access tokens
needed in such a way so as to positively influence the usage of the
platform, while still making a profit. All access token holders can act
as competitors to Brickblock and sell their access tokens to
broker-dealers and fund managers on the open market. Brickblock cannot
increase fees without risking a decline in the number of trades
conducted on the platform and cannot decrease fees without reducing its
own profit.

### 5.3. Proof-of-Assets (PoA) Tokens
For ETFs and REFs, PoA tokens represent real-world assets in the form of
securities. For CMFs and CTFs, they represent a claim to coin funds on a
secured trading account or in the custodians’ wallets. Users receive a
PoA token in return for every fund in which they invest, which
represents a legally enforceable claim to the underlying assets.

--------------
## 6. Conclusion and Vision
Brickblock is an inclusive investment platform that empowers people from
all income classes to diversify their crypto-portfolio with real-world
assets like ETFs and REFs. We will provide legal frameworks to directly
link these assets to our PoA tokens. Furthermore, Brickblock will lead
the development of passively managed CTFs, as well as offer actively
managed CMFs.

At Brickblock, we strongly believe that digital currencies are the
future. The monetary system and the financial services industry are
extremely old-fashioned and [ripe for disruption](https://www.forbes.com/sites/ciocentral/2017/02/24/is-the-financial-services-industry-ripe-for-disruption/). It still takes 5 days for an international money transfer to crawl through the SWIFT
network, originally [created in 1973](https://www.swift.com/about-us/history), and it still takes 2 days
to complete clearing and settlement processes of asset-transfers.
Present technology is far more advanced than the heavily outdated
regulatory frameworks of sluggish banks.

Various members of the Brickblock team have spent several years working
professionally in conventional asset management and understand the
processes and issues of trading and settlement. The asset management and
global custody ecosystem is highly complex, extremely cost intensive in
a multitude of ways (execution, reconciliation, allocation settlement
etc.) and exceptionally exclusive.

Our mission is to change that.

We believe that by including more people in the global economy and
enabling them to invest their money however they like, everyone will
win: investors will pay significantly lower fees, have more options to
hedge volatility and risks that accompany the digital economy and bypass
unfair local jurisdictions. Furthermore, trusted brokers/dealers and
fund managers will obtain an entirely new group of financiers, and
underfinanced companies and industries will gain access to new capital.

Incumbent banks neither have the ability nor the incentive to free
themselves from the burden of the status quo. They lack vision. Any
attempt to innovate would meet with disapproval from the board.

So it is up to us, the crypto-community, to use the aspiring blockchain
technology to eliminate the faults of the old economy and to develop
tools which make it simple, affordable and safe to access the
instruments currently reserved for the financial class.

It is up to us, to create a system that gives everyone access to
real-world assets and to participate in profiting from global economic
progress. No matter where and no matter if you have a bank account or
not.

**It is up to us, to make trading, clearing and settlement with any kind
of assets as easy and secure as transferring a bitcoin.**

If you are interested in shaping the future of investing with us: We are
always looking for talented people to help us in making the crypto-world
better, safer and more inclusive. Get in touch.

<br><br>

### Glossary

**Access Token:** An Access Token is used by broker-dealers and fund
managers to pay the platform service fees.

**Brickblock Token:** A Brickblock Token is received in the contribution
period and is the only way to generate access tokens.

**Broker-dealer:** A Broker-dealer is an entity that trades securities
for its own account or on behalf of its customers. Broker-dealers are
often market-makers and authorized participants in the ETF market; they
act as liquidity providers on exchanges.

**CFD:** A “contract for difference” allows traders to speculate on the
movement of an asset price without owning the underlying. A buyer and
seller devise a contract to exchange the difference in the current value
of the underlyings.

**CMF:** A “coin managed fund” is the crypto-equivalent of an actively
managed investment fund, where the portfolio manager chooses the fund’s
investments.

**CTF:** A “coin-traded fund” is the crypto-equivalent of an ETF; it is
a passively managed basket of different cryptocurrencies.

**CTF Constituents:** The constituents of a CTF are the holdings of the
fund.

**Creation Basket:** A creation basket is the exact list of assets that
need to be sent to the CTF to create a PoA Token.

**Creation File:** The Creation File contains the details of the
creation basket.

**Custodian:** A custodian holds the assets for a fund. The assets (cash
and securities) of a fund must be maintained in the cash/securities
account opened in the name of that fund.

**Dapp:** A “decentralized app” is an application that runs
predominantly on the blockchain.

**DVP:** “Delivery versus payment” is a securities settlement procedure
in which the transfer of the securities and payments occur
simultaneously and no party holds both at the same time.

**ERC20 Token:** The ERC20 token is a widely tradable token that
implements the ERC20 standard. [@ref21]

**ETF:** An “exchange-traded fund” is an investment fund traded on
exchange, which passively tracks a rule-based index.

**LP:** A “liquidity provider” provides liquidity for proof-of-asset
tokens on exchanges. The LP can create and redeem CTF tokens against the
portfolio holdings.

**NAV:** The “net asset value” is the current value of the fund holdings
divided by the number of shares. The NAV therefore, is the price of one
of the fund’s shares. The NAV is calculated on a daily basis at a fixed
time.

**OTC:** “Over-the-counter”, within a trading context, means that the
trade is not executed on an exchange, but privately in a dealer network
or over the phone.

**PoA Token:** A “Proof-of-Asset” Token represents a real-world asset in
the form of securities or, in the case of CTFs, the right to Coin funds
on a certain secured trading account

**REF:** A “real estate fund” invests directly in commercial and
residential property. Most REFs focus on a specific type of assets (e.g.
luxury housing) or region (e.g. Europe).

**REIT:** A “real estate investment trust” is a company that, in most
cases, owns and operates income-producing real estate assets. Some REITs
provide loans to the owners and operators of real estate.

**RFQ:** “Request for quote” describes the process of sending
standardized quote requests to select brokerage firms. The quote is
constantly updated and the processing can be fully automated.

**Smart Contract:** Smart contracts are computer protocols that have
fixed if-then relations, therefore facilitating contract design and
enforcement.


DISCLAIMER: This Brickblock whitepaper is for information purposes only
and is subject to change. Brickblock does not guarantee the accuracy of
or the conclusions reached in this white paper, and this whitepaper is
provided “as is”. Brickblock does not make and expressly disclaims all
representations and warranties, express, implied, statutory or
otherwise, whatsoever, including, but not limited to: (i) warranties of
merchantability, fitness for a particular purpose, suitability, usage,
title or non-infringement; (ii) that the contents of this white paper
are free from error; and (iii) that such contents will not infringe
third-party rights. Brickblock and its affiliates shall have no
liability for damages of any kind arising out of the use, reference to,
or reliance on this white paper or any of the content contained herein,
even if advised of the possibility of such damages. In no event will
Brickblock or its affiliates be liable to any person or entity for any
damages, losses, liabilities, costs or expenses of any kind, whether
direct or indirect, consequential, compensatory, incidental, actual,
exemplary, punitive or special for the use of, reference to, or reliance
on this whitepaper or any of the content contained herein, including,
without limitation, any loss of business, revenues, profits, data, use,
goodwill or other intangible losses.

Copyright (c) 2017 brickblock.io Without permission, anyone may use, reproduce or distribute any material in this whitepa- per for non-commercial and educational use (i.e., other than for a fee or for commercial purposes) provided that the original source and the applicable copyright notice are cited.
