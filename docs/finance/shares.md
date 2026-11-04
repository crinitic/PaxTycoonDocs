# Shares
Every airline in your game, yours included, is divided into shares, and every share has a price that changes each weekday. Selling part of your own airline raises money without a loan. Buying into a rival earns you its dividends, and once you hold more than half of it, it is yours to take over.

The same goes the other way. Hold less than half of your own airline for too long, and a rival can take you over. That ends the game.

Open the market from **Finance > Shares**. The tile shows how much of your own airline you hold.

## Who holds an airline
Every airline has **1,000,000 shares**, and starts out holding **80%** of itself. The other 20% belongs to the public: the investors who put up your opening capital.

An airline's shares are held by the airline itself, by other airlines, and by the public. The public is whatever no airline holds, and it is the only one anybody trades with. Every share you buy comes from the public, and every share you sell goes to it. Nobody sells to you directly, so there are no offers to make and nobody to wait for. A rival that gets rid of its shares in you sells them to the public, and then anyone can buy them.

What the public holds of an airline is what is **available to buy**.

No new shares are ever issued. Selling part of your own airline is how you raise money, and once you have sold it, that money is spent. The only thing that changes an airline's number of shares is [absorbing](#absorbing) another airline.

## The Shares node
Buying and selling shares, and taking over an airline you control, need **Shares** from the [development tree](../development.md). Until you have it, the market is open to look at but not to trade on.

While you do not have it, **no computer airline trades shares either**. Rivals start trading once you have the node, and never stop after that. So nobody can take you over before you have it: you cannot sell any of yourself, and nobody can buy the public's 20%.

In a game with everything unlocked, the market is open to everyone from the first day.

## Market hours
The market is open **Monday to Friday**. On **Saturday and Sunday it is shut**: nobody buys or sells, nobody absorbs or liquidates, and every price stays where Friday's trading left it. The screens still show every price and every holding, and what a takeover would do, and the Shares screen says the market is shut until Monday.

Prices are set again on Monday morning. [Dividends](#dividends) are paid every night, weekends included.

## The price
Each airline's price is set overnight before each weekday, and holds for the whole day, except that trading moves it (see [Buying and selling](#buying-and-selling)). A new airline gets its first price on its first night: until then it has none, and nobody can trade it.

The price follows what the airline is worth:

- **What it owns**: its balance, its fleet at what it would fetch if sold, the fuel in its tanks, and its shares in other airlines, less what it owes on loans.
- **What it earns**: its profit over the last 28 days. A loss counts against it.
- **Its [reputation](../reputation.md)**, a little. A high score adds up to 10%, a low one takes off up to 5%.
- **Its incidents**: a Moderate incident takes a little off, and a Major one more, for 28 days.

However deep in debt an airline is, its price never reaches zero.

On top of that, the market has a mood about each airline. For weeks at a time it can like an airline more or less than it is worth, before it changes its mind, and now and then it changes its mind overnight. Nobody explains why. The mood always comes back towards what the airline is worth, so an airline priced well under it is a bargain, if you can wait.

## Buying and selling
Tap an airline on the market to open it, then **Buy** or **Sell**. On your own airline the buttons are **Sell** and **Buy back**.

Enter how much in one of three ways:

- **%**, a share of the airline;
- **Shares**, a number of shares;
- **¤**, an amount of money. Buying, you get as many shares as the money covers. Selling, you sell as few as raise at least that much.

Whichever you pick, you trade whole shares, and the sheet shows all three. **Max** fills in the most you can: buying, everything available to buy, or as much as your balance covers if that is less; selling, everything you hold.

The sheet shows what the trade comes to before you confirm: the shares at today's price, the trading fees, what you pay or get, your holding after and your balance after. If the price moves before you confirm, because someone else traded, the sheet says so and shows the new figures.

**Trading fees.** Every trade runs at today's price, and the broker takes a fee on top of a buy or off a sale. The sheet shows its rate for that trade. It starts under 2% for a small trade and grows the more of an airline you trade at once: about 8% on a tenth, about 21% on 30%.

**Your trade moves the price,** up when you buy and down when you sell, by how much nobody knows until it's done. The more you trade, the further it moves. The price moves halfway back every week, all of it on weekdays.

The fee is always more than your trade can move the price, so buying and selling straight back always loses money, whatever the size, and so does buying in several goes and selling in one.

**Buying needs the money in the bank**, as hiring and buying aircraft do. Selling never does: an airline below zero can always sell what it holds.

## Selling part of your own airline
Selling part of your own airline is a way to raise money. It is cheaper than any loan, at about 3% a year in [dividends](#dividends), and you never pay it back.

What it really costs is control. Every share you sell is one a rival can buy. Below 50%, a rival can take you over: see [Being taken over](#being-taken-over).

Selling your own shares makes the [news](../intel/news.md): "Seeded Air sells 4% of itself."

## Dividends
Every airline pays **3% of its share price a year** to everyone who holds it, a little every night, weekends included: other airlines and the public alike. An airline never pays itself.

So your own airline pays the public from the start, on its 20%: about 0.6% of what it is worth a year. And every share you sell adds to what you pay.

Dividends are paid whatever the airline made that day, even by an airline below zero, and can take the balance below zero, like the night's other bills.

What you hold in other airlines pays you the same way. The Shares screen shows what comes in and goes out a month.

## Control
**More than half** of an airline is control: 500,001 shares out of 1,000,000.

Once you control a rival, its screen shows what you can do instead of your holding. You can do nothing at all: the rival keeps flying as before, and pays you its dividends. **Absorb** and **Liquidate** stay there for as long as you hold more than half, and work on any weekday.

Each shows what it would do before you confirm, and neither can be undone.

### Absorbing
The rival joins your airline: its money, its aircraft (with their registrations), its crew and every other employee, its routes and its schedule, its rented routes, its fuel and tanks, its gates and terminals, and its loans, each on its own rate and due date. Where you both have a lounge at the same airport, the better one stays. Nobody is laid off.

The rival's other shareholders become yours, keeping what they had:

- **A rival that held some of it** gets new shares in your airline worth what its shares were worth.
- **The part nobody else held**, the rival's own and the public's, becomes new shares in your airline, available to buy.
- **Your own shares in it** are cancelled.
- **Its shares in other airlines** become yours.

Both airlines are valued at their prices before the day's trading moved them, so buying or selling shares just before absorbing changes nothing.

So absorbing gives your airline more shares, and you hold less of yourself afterwards. Absorbing an airline as big as yours, or bigger, can take you under half. The preview tells you how much of yourself you would hold.

### Liquidating
The rival closes. Its aircraft go to the used market and its staff to the hiring pool, where anyone can pick them up. Its rented routes, gates and lounges are given up.

Everything it had is turned into money: its balance, its aircraft at what they would fetch, the fuel in its tanks, and its shares in other airlines sold less the trading fees, less what it owes. If that comes to more than nothing, every airline that held it gets its share, and you get yours. If it comes to less, its lenders write off the difference, and nobody gets anything.

### Which one
- **Absorbing** keeps the aircraft, the crew and the routes, but brings the debt, and you hold less of yourself.
- **Liquidating** gives you cash, and you hold just as much of yourself. It also takes a competitor off your routes, and puts its aircraft and pilots on the market.

Either way, the rival is gone from the game, but its stories stay in the news and its line stays on the reputation chart. A game short of rivals gets a new one later, as it always does. See [Competitors](../competitors.md#when-they-arrive).

## Being taken over
When a rival buys more than half of your airline, you have been acquired, and **the game is over**.

Nothing happens to your airline. It keeps flying, and so does the rival. But **the stock market closes for good** in that game: nobody buys, sells or pays dividends any more, prices stop, and every holding stays as it stood.

The next time you open the game, it tells you: "You have been acquired by Gullwing." **Continue playing** carries on; **Back to my games** leaves. After that, **Game over · acquired by Gullwing** and the day it happened are shown on your reputation, your airline's name, the Shares screen and the Shares node.

You still earn [achievements](../achievements.md) and DP after that. Those earned after the game over are marked **After game over**.

Only rivals take over. A rival does not pounce the moment you dip below half: a week there will not hurt you. But stay there for months, and rivals start buying, and they keep what they have bought, so the next time you need even less to lose control. Every 10%, 25% and 40% a rival gets of you makes the news. See [Competitors](../competitors.md#shares).

## What you can find out
- **Every airline's price**, its change since yesterday, its history over the last month, three months or year, what it is worth, and how much of it is available to buy. Open to everyone.
- **Who holds your airline**, and how much, always. Every airline knows its own shareholders.
- **Who holds a rival**, with an **Impressive** [informer](../personnel/jobs/informer.md). It is on the rival's Shares screen, and with the rest of its finances under **Intel > Leaks**.
- **Whether control is within reach**, with a [financial advisor](../personnel/jobs/financial-advisor.md) who is at least **Competent**. A rival's card then says, for example, "Available to buy: 38%. With your 15%, that's 53%: enough for control." It only says so when there is enough. It never says who holds the rest.

## The Shares screen
- **Your holdings**: what your shares in other airlines are worth, and the dividends coming in and going out a month.
- **Every airline**, yours first: its price, the last 28 days as a line, the day's change, what it is worth, how much is available to buy, and how much you hold.

Tap an airline for its screen:

- **Today's price** and the change since yesterday.
- **Price history**: the last month, three months or year. Tap a day for its price.
- **Market value**, **Available to buy**, and the **dividend** a share pays a year. On your own airline, what you pay your shareholders a month.
- **Your holding**, with **Buy** and **Sell**, or, on a rival you control, **Absorb** and **Liquidate**. At the weekend there is nothing to press until Monday.
- **Shareholders**: who holds it, and the public, where you can see it.

## The morning report
Among the night's bills, after the loans, **Dividends received** is what your shares in other airlines paid you, and **Dividends paid** is what your airline paid its shareholders.

## In the ledger
- **Dividends paid** and **Dividends received**, under **The night**, count towards your profit, like loan interest.
- **Shares bought**, **Shares sold**, **Absorbed** and **Liquidation**, under **Loans, aircraft, fuel & shares**, are money turning into shares and back, like buying an aircraft, so they do not count against your profit. **Absorbed** is the balance an absorbed airline brought with it, and **Liquidation** your part of what a liquidated one fetched.

The Month tab shows **Shares bought, less sold**.

## In the news
Shares make the [news](../intel/news.md#what-makes-the-news): an airline selling part of itself, a fundraising round, a holder getting 10%, 25% or 40% of another airline, control, an absorption, a liquidation, and your own acquisition.
