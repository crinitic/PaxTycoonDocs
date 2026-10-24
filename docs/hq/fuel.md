# Fuel
Every flight burns fuel, and the price of fuel changes every day. You can pay whatever it costs, night after night, or buy storage tanks, fill them when fuel is cheap, and burn that fuel later.

Manage fuel from **HQ > Fuel**. The HQ tile shows today's price.

## The price
There is one price for your whole game, the same for every airline. Nothing any airline buys moves it.

The price changes overnight and holds for the whole day. Fuel you buy today costs today's price, and so does any fuel tonight's flying does not take from your tanks. A new game starts at **¤1.000** a litre.

The price moves in trends rather than random jumps: it tends to keep going the way it has been going for a few weeks, then turns. It always stays between **¤0.60** and **¤1.60**, and on most days it is between about ¤0.80 and ¤1.30.

Nobody can tell you where it is going. You see today's price and the price on every day so far, and nothing about tomorrow.

## Shocks
Two or three times a year, the price jumps overnight. Most shocks push it up, by 10 to 25%. Some push it down, by 8 to 15%. After a shock the price slowly drifts back towards where it was: up fast, down slowly.

Shocks never come within a month of each other, and never in a game's first month.

Every shock makes the [news](../intel/news.md), so every airline in the game learns about it the same morning.

## Tanks
A tank stores fuel for your whole airline. It is not at any airport: your whole fleet burns from it, wherever each aircraft flies from.

| Size | Holds | Price |
|---|---|---|
| Small | 1,000,000 L | ¤400,000 |
| Medium | 10,000,000 L | ¤3,500,000 |
| Large | 100,000,000 L | ¤30,000,000 |

Buy as many of each size as you like. Your capacity is all of them added up. You need the money in the bank to buy one. A [security manager](../personnel/jobs/security-manager.md) may get the price down, and the receipt says by how much.

A tank has no running cost. It cannot be sold or removed, so what you pay for it is spent for good.

Without tanks, every night buys all its fuel at that day's price.

Buying a tank needs **Fuel management** from the [development tree](../development.md). Until you have a tank there is nowhere to put fuel, so you cannot buy fuel ahead either. The price, its history and the Fuel screen are open to everyone, since an airline without tanks pays the day's price.

## Buying fuel
You buy fuel at today's price, exactly. Type the litres you want, or pick **Max** to buy as much as you can: exactly the room your tanks have left, or as much as your balance covers if that is less. You cannot buy more than fits, and you need the money in the bank.

Fuel in your tanks cannot be sold. Only your own fleet can burn it.

Everything in your tanks has one **average cost**. Each purchase blends into it: 1,000,000 L bought at ¤0.800 added to 1,000,000 L at ¤1.000 averages ¤0.900. Burning fuel does not change the average.

## Using tank fuel
One setting, for your whole airline, decides when the night burns fuel from your tanks:

- **Always**, the default. Tonight's flying burns fuel from your tanks first, and buys at today's price only what they can't cover.
- **Only when today's price is above ¤___**. On a day dearer than the price you set, the night burns from your tanks first. On any other day it buys all its fuel at today's price and leaves the tanks alone. At exactly your price, the tanks are kept.

The second is how a tank pays best. The fuel in it is already paid for, so on a cheap day it is often worth keeping for a dear one. The Fuel screen tells you which way tonight will go.

## The night
Every night, your airline pays for the fuel the day's flights burned, ferry flights included. It takes from your tanks first, if your setting allows and they hold any, and buys the rest at that day's price.

What the night buys is never refused for lack of money. It is paid even if it takes your balance below zero, like the night's other bills.

## What a tank can save
A tank can only save you money on your own fuel bill, so what it saves depends on how much you fly and how much your tanks hold. With a sensible setting (fill up when fuel is cheap, burn from the tanks only when the price is above ¤1.000), a typical saving is:

| Tanks hold | Saving on your fuel bill |
|---|---|
| 2 weeks of flying | about 1.5% |
| 1 month | about 3.5% |
| 2 months | about 6% |
| 3 months | about 8% |

Used like that, a tank pays for itself in about a year, whatever its size. Sooner if a shock lands while your tanks are full, later if not. Two things slow it down:

- **Using tank fuel Always.** Burning tank fuel on cheap days throws away what you saved buying it. Expect a year and a half to two years.
- **Tanks too big for your fleet.** Fuel sitting in a tank for months saves nothing until it burns. Two A321neos with a Medium tank wait about two years.

As your fleet grows, the same tanks cover fewer days of flying.

## The Fuel screen
- **Today's price**, to three decimals, with the change since yesterday.
- **Price history**, a chart of the last month, three months or year. When your tanks hold fuel, a line shows its average cost, so you can see how today's price compares.
- **Your tanks**: how full they are, their capacity, what they hold, how many days of your schedule that covers, the average cost, and what the fuel is worth at that cost. Days are worked out from the flying on your schedule over the next 7 days.
- **Buy fuel**, **Buy a tank** and **Use tank fuel**.

## Ferry flights
When you schedule a ferry flight, its fuel is quoted at today's price. The night charges what fuel costs on the day it actually flies, and burns from your tanks if your setting lets it.

## The morning report
The morning report gives today's price and the change since yesterday, for example **Fuel today ¤0.943 / L (−0.6%)**.

Among the night's bills, **Fuel** is what all the fuel burned cost, including the fuel from your tanks at its average cost. If some came from your tanks, **Used from tanks** follows under your profit and gives that part back, because you paid for it when you bought it. Your balance only moves by what the night actually bought.

## In the ledger
- **Fuel tank bought**, under **One-time bills**, is a tank.
- **Fuel bought**, under **Loans, aircraft & fuel**, is fuel you bought for your tanks. It is money turning into fuel, like buying an aircraft, so it does not count against your profit.
- **Fuel**, under **The night**, is what the fuel your flights burned cost, tank fuel included at its average cost. So a route's profit is the same whether its fuel came from a tank or not.
- **Used from tanks**, under **Loans, aircraft & fuel**, gives back the tank fuel's part of that, since it was paid for when you bought it.

The Month tab shows **Fuel bought, less used from tanks**: what went into your tanks that month, less what came out.
