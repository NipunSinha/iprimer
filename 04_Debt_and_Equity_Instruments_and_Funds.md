# Primer 4 — Debt and Equity Instruments, and the Funds That Hold Them

**Purpose:** A complete map of the investment instruments available in India, with extra depth on debt (the full spectrum from overnight money to 40-year government bonds), then how mutual funds package them, and finally equity. The order is deliberate: first the logic that connects everything, then instruments from shortest to longest, then funds.
**Reader:** Works in mutual fund marketing and holds NISM V-A, so the fund parts are revision; the instrument mechanics and their link to banking are the focus.
**Rules and thresholds** (SEBI/RBI limits, tax rates) change. Treat specific numbers as "as I know them" and confirm against the latest circulars before quoting.

---

## Part A. The logic that connects everything

### A.1 Why instruments exist
- Some people and institutions have surplus money. Others need money. Instruments are the contracts that connect them.
- **Debt:** you lend; you get interest and your principal back on a date. You are a creditor.
- **Equity:** you own part of the business; you share in profits and losses with no promised return. You are an owner.

### A.2 Who issues what
| Issuer | Typical instruments |
|---|---|
| Central government | T-bills, dated G-secs, floating rate bonds, inflation-indexed bonds |
| State governments | State Development Loans (SDLs) |
| Banks | Certificates of deposit, deposits, bonds (including Basel III AT1/Tier 2) |
| Corporates, PSUs, NBFCs | Commercial paper, NCDs, bonds, equity, preference shares |
| RBI | Repo and reverse repo operations (liquidity tools) |
| Funds/trusts | Mutual funds, ETFs, REITs, InvITs, AIFs, PTCs |

### A.3 The market map
```
MONEY MARKET (up to 1 year)      CAPITAL MARKET (over 1 year)
 - Call/notice/term money         DEBT                      EQUITY
 - Repo / TREPS                    - Dated G-secs            - Shares
 - T-bills                         - SDLs                    - Preference shares
 - Certificates of Deposit         - Corporate bonds/NCDs    - IPO/FPO/QIP/Rights
 - Commercial Paper                - Securitised paper       - ETFs/REITs/InvITs
 - Cash management bills           - Bank AT1/Tier 2
```

### A.4 Risk and return: the four risks
1. **Interest rate risk:** bond prices fall when market rates rise.
2. **Credit risk:** the issuer may not pay.
3. **Liquidity risk:** you may not be able to sell quickly at a fair price.
4. **Reinvestment risk:** when a bond matures or pays coupons, rates may be lower for reinvestment.
Plus, for equity: **business risk and market risk**.

General rule: the more risk, the higher the return expected. The bond ladder in India runs roughly: overnight < T-bill < G-sec < AAA corporate < AA < A < unrated.

---

## Part B. Debt basics (the mathematics in plain English)

### B.1 The vocabulary
- **Face value (par):** the amount repaid at maturity (G-secs and most bonds: ₹100 per unit, though trading lots are larger).
- **Coupon:** the fixed interest, stated as % of face value. A 7% coupon on ₹100 means ₹7 a year.
- **Maturity:** the date the principal is repaid.
- **Price:** what the bond trades at in the market. It can be above (premium) or below (discount) face value.
- **Yield to maturity (YTM):** the total annual return if you buy today at the market price, hold to maturity, and receive all payments. This is the number people quote as "the yield".
- **Current yield:** coupon ÷ price.
- **Yield curve:** a chart of yields against maturity. Normally, longer bonds yield more (upward-sloping) because of more risk. A flat or inverted curve (short yields above long yields) often signals that rates are expected to fall or that short rates are being pushed up.

### B.2 Price and yield move in opposite directions
A bond pays a fixed coupon. If market yields rise, the old bond's fixed coupon looks poor, so its price falls until its yield matches the market.
*Worked example:* A 10-year bond pays ₹7 a year on ₹100 face. If market yields move to 8%, its price is
7 × 6.710 (present value of a 10-year annuity at 8%) + 100 × 0.4632 = 46.97 + 46.32 = **₹93.29**.
So a 1 percentage point rise in yield lowered the price by about 6.7%.

### B.3 Duration: the sensitivity measure
- **Macaulay duration:** the weighted average time, in years, to receive the bond's cash flows.
- **Modified duration:** approximately the % change in price for a 1 percentage point change in yield. A bond with modified duration 7 loses about 7% if yield rises 1 point, and gains about 7% if yield falls 1 point. For the example above, the 10-year 7% bond has modified duration of about 7.0, which matches the 6.7% fall (the gap is because the price–yield relationship is slightly curved, called convexity).
- Longer maturity and lower coupon mean higher duration, so more interest rate risk.
- **Rule of thumb for a fund held for a year:** return ≈ portfolio yield − (duration × rise in yield). A fund yielding 7% with duration 3 would earn about 5.5% if yields rise 0.5 points immediately, and about 8.5% if they fall 0.5 points.

### B.4 Accrual vs mark-to-market
- **Accrual:** interest earns day by day, and a hold-to-maturity investor receives the agreed yield regardless of daily price moves.
- **Mark-to-market (MTM):** the value today at the market's current prices. Mutual funds are required to value holdings at market prices, so NAV moves when yields move.
- Banks classify their own bond holdings as Held to Maturity (accrual accounting), Available for Sale or Held for Trading (marked to market).

### B.5 Credit spread
A corporate bond's yield = G-sec yield of the same maturity + **credit spread**. The spread compensates for default risk and lower liquidity. Illustration (not current data): G-sec 10-year at 7.2%; AAA corporate at 7.7% (spread 0.5%); AA at 8.7% (spread 1.5%); A at 10% (spread 2.8%).

### B.6 Credit ratings
- Ratings come from agencies such as CRISIL, ICRA, CARE, India Ratings, Acuité and Brickwork.
- **Long-term scale:** AAA (highest safety), AA, A, BBB (lowest investment grade), BB and below (speculative), D (default). Modifiers "+" and "−" refine each step. Outlooks: positive, stable, negative.
- **Short-term scale (up to 1 year):** A1+ (highest), A1, A2, A3, A4, D.
- Ratings change. A downgrade reduces a bond's price, and is the main source of credit events in funds.

---

## Part C. The debt spectrum, from shortest to longest

### C.1 Overnight and call money
- **Call money:** banks lend to each other for one day. **Notice money:** 2 to 14 days. **Term money:** 15 days to 1 year.
- **Rate:** moves around the RBI repo rate, between the SDF floor (5.00%) and MSF ceiling (5.50%). The **WACR** (weighted average call rate) is the RBI's operating target.
- **Who:** banks and primary dealers (non-banks can lend in some forms).
- **Bank link:** how banks balance daily cash needs after CRR/SLR. When there is surplus liquidity (as now), call rates sit near the SDF.

### C.2 Repo, reverse repo and TREPS
- **Repo:** a short-term loan against securities. The borrower sells a security with an agreement to buy it back at a higher price; the difference is interest. It is collateralised lending, so very safe.
- **Who borrows and lends?** From the RBI's point of view, a *repo* is when the RBI lends to banks (repo rate 5.25%). A *reverse repo* is when the RBI borrows from banks (the current tool is the SDF at 5.00%, and variable rate reverse repo auctions for longer periods).
- **TREPS (Tri-Party Repo):** a collateralised overnight market run through CCIL. Mutual funds, especially liquid and overnight funds, lend here. Rates are usually a little below call money rates.
- **Corporate relevance:** companies with spare cash can invest via funds that lend in TREPS.

### C.3 Treasury Bills (T-bills)
- **What:** short-term zero-coupon securities issued by the government of India at a discount and repaid at face value. No interest payments; the return is the gap between price and face value.
- **Maturities:** 91-day, 182-day, 364-day. Auctioned by RBI on behalf of the government (weekly for 91-day; alternate weeks for 182- and 364-day). There are also **Cash Management Bills (CMBs)** of shorter maturity used for temporary government cash gaps.
- **Risk:** effectively no credit risk (sovereign); small interest rate risk; very liquid.
- **Pricing example:** a 91-day T-bill with a yield of 6.00%.
Price = 100 ÷ (1 + 0.06 × 91/365) = 100 ÷ 1.014959 = **₹98.53**.
You invest ₹98.53 and receive ₹100 after 91 days. The gain is ₹1.47.
- **Who holds:** banks, mutual funds, corporates, insurers; retail can buy through the RBI Retail Direct platform or via non-competitive bids.
- **Banks' link:** T-bills count towards the SLR and LCR, and T-bill yields can be used as a benchmark for some floating-rate products.

### C.4 Certificates of Deposit (CDs)
- **What:** a tradable deposit certificate issued by banks (and certain financial institutions) at a discount, for 7 days to 1 year.
- **Who buys:** mutual funds (significantly), corporates, insurers.
- **Rate:** slightly higher than T-bills because of bank credit risk (though small for top banks).
- **Bank link:** a bank raises wholesale funding when deposits lag loan growth. CD issuance typically rises when credit growth outpaces deposit growth.
- **Example:** an ICICI-type bank issues a 6-month CD at 6.6% annualised; a liquid or money market fund buys it. The bank's funding cost is the yield.

### C.5 Commercial Paper (CP)
- **What:** an unsecured, short-term promissory note issued by corporates, NBFCs and financial institutions, 7 days to 1 year, at a discount.
- **Rating:** must have a minimum short-term rating (A3 or above), and most buyers demand A1+.
- **Use:** a strong company can borrow more cheaply from CP than a bank working capital loan.
- **Risk:** refinancing risk. The issuer repays old CP by issuing new CP; if the market shuts (as in 2018 after IL&FS), it may not be able to. That is a key reason for liquidity stress.
- **Bank role:** bank arranges, sometimes underwrites or gives a back-up line. This is fee business and interacts with working capital loans.
- **Example:** a large, AAA-type client has cash credit at 8.5%. It issues CP at 6.8%. The bank loses some interest income but can earn a placement fee and keep the client's other business.

### C.6 Commercial bills and invoice discounting
Bills of exchange drawn on buyers, discounted by banks (see Primer 1, section 4.1). The bank holds them or rediscounts them with other banks or institutions.

### C.7 Government securities (G-secs): dated securities
- **What:** long-term bonds issued by the Central Government to fund its deficit. Maturities range from 2 to about 40 years. Face value ₹100.
- **Coupon:** fixed, paid **semi-annually** (every six months). Example: a 7.10% 2034 G-sec pays ₹3.55 twice a year per ₹100 face value.
- **Auction:** RBI conducts regular auctions (generally on Fridays). Bidding is competitive (institutions) or non-competitive (small investors).
- **Benchmark:** the most recently issued or most liquid 10-year bond, whose yield is quoted as "the 10-year". As of 29 September 2026 it is around 7.2%.
- **Holders:** banks (mostly for SLR), insurers, provident funds, mutual funds, RBI, FPIs (under the Fully Accessible Route for specified bonds).
- **Risk:** no credit risk in rupees; high interest rate risk for long maturities.
- **Variants:**
 - **Floating rate bonds (FRBs):** coupon resets periodically against a benchmark.
 - **Inflation-indexed bonds:** principal/coupon tied to inflation.
 - **STRIPS:** separately traded coupon and principal pieces (zero-coupon-like).
 - **Sovereign Gold Bonds (SGBs):** government bonds denominated in grams of gold with small annual interest; new issuance was stopped, but existing ones trade.
 - **State Development Loans (SDLs):** bonds issued by state governments; slightly higher yield than G-secs because of state credit risk and lower liquidity, but no state has defaulted.
- **Bank link:** banks must hold around 18% of deposits as SLR in such securities. Their bond books gain when yields fall and lose when yields rise, so rising yields (as in September 2026) reduce banks' treasury profits.

### C.8 Corporate bonds, NCDs and debentures
- **What:** long-term borrowing by companies (over 1 year), typically with fixed coupons, **secured** (backed by assets) or **unsecured**, privately placed or public, listed on exchanges.
- **Who issues:** PSUs (e.g., NTPC, REC, PFC), NBFCs, infrastructure companies, private corporates, banks.
- **Features to know:**
 - **Bullet vs amortising repayment**
 - **Callable/puttable options** (issuer may repay early / investor may demand early repayment)
 - **Step-up/step-down coupon**
 - **Convertible debentures** (can turn into equity)
 - **Zero-coupon bonds**
 - **Floating rate** (linked to T-bill, repo or MIBOR)
- **Pricing:** G-sec yield of comparable maturity + spread.
- **Market:** most are privately placed to institutions and traded over-the-counter, which means liquidity is lower than G-secs.
- **Tax-free bonds:** historically issued by public infrastructure entities whose interest is exempt from tax; now trade in the secondary market.
- **Bank link:** banks and their subsidiaries arrange issues (fee), buy them (as an investment), and sometimes lend to the same company (so the RM sees a total exposure).

### C.9 Bank capital instruments: AT1 and Tier 2
- **Tier 2 bonds:** subordinated debt (repaid after depositors, before equity), pay higher coupons.
- **Additional Tier 1 (AT1) bonds:** perpetual (no maturity), with call options and the ability to be **written down** if the bank is in trouble. In March 2020, Yes Bank's AT1 bonds (about ₹8,400 crore) were written off in its rescue. Mutual funds holding them took losses, which prompted tighter SEBI rules on how they are held and valued.
- **Lesson:** a higher coupon is payment for a loss-absorbing structure, not free return.

### C.10 Securitised debt (PTCs, ABS)
- **What:** loans (vehicle loans, home loans, microfinance, business loans) are bundled into a pool sold to a trust, which issues **Pass Through Certificates (PTCs)** backed by the pool's cash flows. Investors get paid from borrowers' repayments.
- **Why:** lenders (especially NBFCs) get funding and free up capital; investors get yield with pool-level credit enhancement.
- **Bank link:** the bank buys PTCs, or does **direct assignment** of loan pools.

### C.11 Small savings and bank deposits (retail benchmarks)
- **Fixed deposits (FDs):** bank deposits for a fixed period. Insured up to ₹5 lakh per depositor per bank by DICGC. Rates are known at start; premature withdrawal has a penalty.
- **PPF, NSC, Sukanya Samriddhi, Senior Citizens' Savings Scheme, etc.:** government-backed schemes with rates reset quarterly.
- **Why include them:** these are the "competitors" of debt funds for household savings, and the reference for retail yields.

### C.12 Interest rate and currency derivatives
- **Interest rate swaps (IRS) / OIS:** exchange fixed interest for floating interest on a notional amount. An overnight index swap exchanges a fixed rate against the compounded overnight rate. Used by banks, funds and corporates to hedge or speculate on rates.
- **Forward rate agreements (FRA):** lock a future interest rate.
- **Currency forwards/swaps/options:** hedge exchange rate risk (Primer 1, 4.4).
- Mutual funds have limited use of these, mainly for hedging.

### C.13 Summary table: the debt ladder
| Instrument | Maturity | Issuer | Coupon/return | Main risk | Typical holders |
|---|---|---|---|---|---|
| Call/notice/term money | 1 day to 1 year | Banks | Market rate | Counterparty | Banks |
| TREPS / repo | 1 day onwards | Collateralised | Near repo | Very low | Banks, funds |
| T-bill | 91/182/364 days | Government | Discount (zero coupon) | Minimal | Banks, funds, corporates |
| CD | 7 days–1 year | Banks | Discount | Bank credit | Funds, corporates |
| CP | 7 days–1 year | Corporates | Discount | Credit, refinancing | Funds, banks |
| Dated G-sec | 2–40 years | Central govt | Fixed semi-annual | Interest rate | Banks, insurers, funds |
| SDL | 3–30 years | States | Fixed | Interest rate, liquidity | Banks, insurers |
| NCD/bond | 1–15+ years | Corporates | Fixed/floating | Credit, liquidity | Funds, banks, insurers |
| AT1/Tier 2 | Perpetual/10+ yrs | Banks | Higher fixed | Write-down, call | Funds, HNIs |
| PTC | Varies | Trusts | Fixed/floating | Pool performance | Banks, funds |
| FD | Fixed | Banks | Fixed | Bank credit (insured to ₹5 lakh) | Households |

---

## Part D. Debt mutual funds

### D.1 What a debt fund does
It pools investors' money and buys the instruments above. Investors hold units; NAV = (value of holdings − expenses) ÷ units. Returns come from **interest (accrual)** plus **gains or losses from price changes (MTM)**. A fund's profile is decided mainly by two things: its **duration** and its **credit quality**.

### D.2 SEBI's categories of debt funds (16)
From shortest to longest:
| Category | What SEBI requires (roughly) | Who it suits |
|---|---|---|
| **Overnight** | Invests in securities maturing the next day | Parking money for days |
| **Liquid** | Securities with maturity up to 91 days | Corporates' and investors' idle cash; emergency funds |
| **Ultra short duration** | Portfolio Macaulay duration 3 to 6 months | 3 to 6 months horizon |
| **Low duration** | 6 to 12 months | 6 to 12 months |
| **Money market** | Money market instruments with maturity up to 1 year | Up to 1 year |
| **Short duration** | 1 to 3 years | 1 to 3 years |
| **Medium duration** | 3 to 4 years | 3 to 4 years |
| **Medium to long duration** | 4 to 7 years | Longer |
| **Long duration** | Over 7 years | Expect yields to fall |
| **Dynamic bond** | Manager moves duration freely | Reliance on manager's rate view |
| **Corporate bond** | At least 80% in AA+ and above rated bonds | Higher accrual with relatively good quality |
| **Credit risk** | At least 65% in AA and below | Higher yield with credit risk |
| **Banking and PSU** | At least 80% in banks, PSUs, public financial institutions | Quality plus yield |
| **Gilt** | At least 80% in G-secs | Zero credit risk, high rate sensitivity |
| **Gilt with 10-year constant duration** | At least 80% in G-secs, duration 10 years | Pure rate bet |
| **Floater** | At least 65% in floating-rate instruments | Rising-rate period |

Other structures: **Fixed Maturity Plans (FMPs)** (closed-ended, hold to maturity), **Target Maturity Funds / Index funds on bonds** (e.g., funds tracking an index that matures on a fixed date) and **Arbitrage funds** (equity-taxed, low-risk strategies).

### D.3 Liquid fund specifics (most relevant to corporate treasuries)
- Maturity of securities up to 91 days, marked to market daily.
- At least a stated minimum in liquid assets (cash, G-secs, T-bills, repo), which adds safety.
- Quick redemption: investors can redeem and receive money the next working day; there is an instant redemption option up to a cap.
- Graded exit loads in the first seven days.
- Returns generally track short-term rates: if the RBI raises the repo rate, yields on the portfolio rise as securities roll over.
- **Why corporates use them:** a company with ₹20 crore idle for 40 days can earn a few percent more than the zero interest on its current account. This is a cross-sell point, and also a competitor to the bank's own deposits, so banks price their short deposits and CDs with this in mind.

### D.4 Potential Risk Class (PRC) matrix
SEBI requires each debt fund to state a risk class from a grid: **credit risk** (Low/Medium/High) on one axis and **interest rate risk** (Low/Medium/High by duration) on the other, from A-I (lowest) to C-III (highest). The Riskometer also shows a label from Low to Very High.

### D.5 What happens to a fund when yields move
*Example with 3 funds, a 1-year view, 0.5-point rise in yields:*
| Fund | Yield | Duration | Approx. return |
|---|---|---|---|
| Liquid | 5.8% | 0.1 | about 5.8% (almost no MTM effect) |
| Short duration | 7.0% | 2.5 | about 7.0 − 1.25 = 5.75% |
| Long duration / gilt | 7.2% | 8.0 | about 7.2 − 4.0 = 3.2% |
And if yields had instead **fallen** 0.5 points, the long gilt fund would gain about 4 points over its yield. The point: the same market move has a far bigger effect on funds with higher duration.

### D.6 Credit events: what the past taught
- **IL&FS (2018), DHFL (2019), Franklin Templeton's six closed schemes (April 2020)** and **Yes Bank AT1 write-off (March 2020)**: lower-rated paper was marked down sharply, creating losses and redemption pressure.
- Responses from SEBI: stricter rules on liquidity and portfolio concentration, valuation norms, the **risk-o-meter**, the **PRC matrix**, **segregated portfolios ("side pockets")** for a defaulted bond, and mark-to-market for all debt funds.
- **Example of the size of credit risk:** if a fund has 5% of assets in a bond that is downgraded and the bond's price falls 20%, the fund's NAV falls 1%. If it defaults to zero, NAV falls 5%. This is why fund houses limit exposure to single issuers.

### D.7 Taxation (indicative; confirm)
Debt funds that invest mostly in debt and money market instruments are generally taxed at the investor's **income-tax slab rate** on gains regardless of holding period, with no indexation benefit. Listed equity-oriented funds: long-term gains (over 12 months) taxed at 12.5% above ₹1.25 lakh a year; short-term gains at 20%. (These are the rates after the July 2024 changes.) Bank FD interest is also taxed at slab rates and subject to TDS.

### D.8 Fund versus direct investing
Funds give diversification, professional credit research and daily liquidity with small amounts; direct holding gives certainty of maturity value if held to maturity.

---

## Part E. Hybrid and alternative instruments (brief)

| Type | What it is |
|---|---|
| **Hybrid funds** | Mix of equity and debt. Categories include conservative hybrid, balanced hybrid, aggressive hybrid, **balanced advantage / dynamic asset allocation**, multi-asset allocation, arbitrage, and equity savings |
| **Gold** | Gold ETFs, gold funds, digital gold, existing SGBs, jewellery |
| **REITs (Real Estate Investment Trusts)** | Units backed by rent-earning commercial property, distribute most income |
| **InvITs** | Same idea for infrastructure assets like toll roads and power transmission |
| **Alternative Investment Funds (AIFs)** | Privately pooled funds (Category I, II, III) for larger investors; includes private credit funds that lend to corporates |
| **PMS** | Portfolio Management Services: customised portfolios, minimum ₹50 lakh |

---

## Part F. Equity

### F.1 What an equity share is
A share is a unit of ownership in a company. Shareholders get **dividends** (a share of profit, not guaranteed) and **capital gains** if the price rises. Shareholders are last in line if the company is wound up.

### F.2 Types of equity instruments
- **Ordinary (equity) shares**
- **Preference shares:** fixed dividend and priority over equity in payment; can be cumulative, redeemable or convertible.
- **Warrants:** right to buy shares at a fixed price.
- **Depository receipts (ADRs/GDRs):** foreign-listed receipts of Indian shares.
- **Convertible debentures:** debt that converts to shares.

### F.3 How companies raise equity
- **IPO (Initial Public Offer):** first sale to the public. Price is set via a book-building range.
- **FPO (Follow-on Public Offer):** further issue by a listed company.
- **OFS (Offer for Sale):** existing shareholders (like promoters or PE funds) sell.
- **Rights issue:** offer to existing shareholders in proportion to holdings.
- **QIP (Qualified Institutional Placement):** quick raise from institutions.
- **Preferential allotment:** shares issued to select investors.
- **Bonus, split, buyback:** corporate actions that change the number of shares or return cash.
- **Bank link:** the wholesale bank finances promoters (loans against shares), advises on IPOs/QIPs (with group securities arms), and lends to PE-backed companies.

### F.4 The market
- **Primary market:** shares sold for the first time. **Secondary market:** trading on NSE/BSE. Settlement is T+1. Regulator: SEBI.
- **Market capitalisation** = share price × number of shares. SEBI ranks the top 100 companies by market cap as **large cap**, 101 to 250 as **mid cap**, and the rest as **small cap**.
- **Indices:** Nifty 50, Sensex, Nifty Next 50, Midcap 150, Smallcap 250, sectoral indices.
- **Participants:** retail investors, mutual funds and other domestic institutions (DIIs), foreign portfolio investors (FPIs), promoters.

### F.5 Valuation measures
P/E, P/B, EV/EBITDA, dividend yield (see Primer 2, section 11). Earnings yield (1 ÷ P/E) is compared with the bond yield to judge whether equities are expensive relative to bonds.

### F.6 Equity mutual fund categories (SEBI)
Large cap, large and mid cap, mid cap, small cap, multi cap, flexi cap, dividend yield, value/contra, focused, sectoral/thematic, ELSS (tax-saving, three-year lock-in). Index funds and ETFs track indices with low costs.

### F.7 Equity derivatives
Futures and options on indices and stocks. Options buyers pay a premium; sellers take on risk. SEBI has tightened rules for retail participants in index options.

### F.8 Linking equity to interest rates and flows
- When bond yields rise, the discount rate investors use rises, so the present value of future earnings falls and **valuations compress**. Growth and long-duration sectors (IT, consumer discretionary) suffer more.
- Banks' shares react to credit growth, NIM, NPAs and treasury losses from bond mark-downs.
- FPIs selling puts pressure on the market; domestic SIPs absorb some of it (Primer 3).

---

## Part G. Bringing it back to the bank and the RM

| Instrument | How a wholesale bank deals with it |
|---|---|
| Deposits/CASA | Main source of cheap funds; corporate current accounts |
| CDs | The bank's wholesale borrowing |
| CPs, NCDs, bonds | Arranged, underwritten, invested in, or alternative to bank loans |
| G-secs and T-bills | Held to meet SLR and LCR; treasury income |
| Repo/TREPS | Day-to-day cash management |
| Liquid/debt funds | Where clients may park surplus cash (competition for deposits and cross-sell via group AMC) |
| Forwards, swaps | Sold to clients as hedges |
| Equity/IPO/QIP | Advisory and promoter funding |
| Securitised paper | Bank buys PTCs or buys loan pools |
| AT1/Tier 2 | The bank's own capital-raising tools |

**Rising-yield impact on a bank:** bond portfolio loses value; borrowers' interest cost rises; CASA may be strong because rates rise; loan growth can slow. **Falling-yield impact:** treasury gains; borrowers' costs fall; margins can compress on repo-linked loans.

---

## Part H. Self-test
1. A 182-day T-bill is bought at ₹96.80. What is the return over the period and the annualised yield?
 *(Gain = 100 − 96.80 = 3.20; period return = 3.20 ÷ 96.80 = 3.31%; annualised ≈ 3.31% × 365/182 = 6.63%)*
2. Why does a bond's price fall when yields rise? Explain with a numerical example.
3. What is the difference between a liquid fund and a money market fund?
4. A company has ₹30 crore idle for 60 days. List three places it could put it, and rank them by risk and likely return.
5. Why might a bank prefer to arrange a client's CP issue rather than refuse a working capital increase?
6. Explain why the AT1 write-off in 2020 matters to an investor reading a fund's portfolio.
7. When the RBI increases the repo rate, which funds are hurt most in the short term? Which benefit over time?
