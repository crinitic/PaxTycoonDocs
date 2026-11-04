# Competitors
You do not have your home airport to yourself for long. A few weeks into a game, computer airlines start setting up there: they fly from the same airport, sell seats on the same routes, hire from the same candidates and buy from the same market as you. A computer airline's CEO is drawn as a robot, so you can tell one apart at a glance.

If your game was set up with **Computer airlines** turned off, none ever arrive.

## Ordinary airlines
A computer airline plays by your rules. It gets the same passengers for the same fares, pays the same costs, borrows from the same lenders, and spends only the money in its bank, as you do. It gets no hidden bonus on demand, fares or costs. What makes one rival harder than another is how well it decides and how much money it starts with.

- **Based at your home airport.** Every route a rival flies has your home airport at one end.
- **Whoever is first gets it.** A seasonal offer, a candidate or a used aircraft belongs to whichever airline takes it first. Rented routes are not exclusive: anyone can rent the same route, and everyone on it shares its passengers.
- **You always see something new first.** Rivals make their moves overnight, before the night brings new candidates, new aircraft on the used market and new seasonal offers. So anything new is yours to look at for a whole day before a rival can take it.
- **What a rival knows about you** is what anyone can find out: which routes you fly, when you leave, how many seats you offer and what you charge. Never how full your flights are, and never your money.

On a route you share, passengers go to the best value first: the fare weighed against the seats, the entertainment, the meals and the lounge, and a departure at the hour they want to leave. A few book whoever has the seats.

Rivals are listed in the [reputation](reputation.md) dialog with everyone else, and their stories are in the [News](intel/news.md).

## When they arrive
A rival **files** first, and **launches** two weeks later. Filing makes the news:

> Budgetwing has filed to fly from New York. Its first flights leave on Feb 28.

On its launch day it gets what you started with: two A321neo, and the crew, mechanic and gate agent to fly them. From then on it runs itself.

**The first rival waits for you to settle in.** It files on the first night your last 28 days were profitable, but never before day 21. If you have not managed a profitable 28 days by day 42, it files anyway.

**More follow as you grow**, one at a time, at least 28 days apart and usually a week or so more, until the game holds as many other airlines as your revenue over the last 28 days calls for:

| Your revenue, last 28 days | Other airlines in the game |
|---|---|
| under ¤25M | 2 |
| ¤25M or more | 3 |
| ¤100M or more | 4 |
| ¤400M or more | 5 |

This counts every other airline in the game, including other players. In a game with other players, computer airlines only fill the places left over.

**Rivals do not leave on their own.** Your revenue only decides whether a new rival files. A bad month does not make one go away. The only way an airline leaves a game is being [taken over](finance/shares.md#control) by another, and a rival taken over leaves a place for a new one to file.

**Later rivals are stronger.** A rival starts with three times your revenue over the last 28 days, and never less than you started with. One that arrives when you are big also reviews its network more often, times its departures better, and has more unlocked from the start.

## Where they fly
A rival looks for passengers nobody is flying. It weighs each route from home by how many passengers would fly it at its fare against the seats every airline already offers on it. So a route you keep selling out is exactly the kind of route a rival moves into, and a route already crowded with seats at fair fares is not. Nothing is aimed at you: it is where the passengers are.

Once it flies a route, a rival:

- **adds departures** where its flights sell out;
- **moves its fares** the way the morning's signals tell you to: up where it sells out, down where passengers find it too dear. Each kind of rival keeps its fares within its own range, and none sells a seat for less than it costs to fly, so a rival short of money cannot drag a route's fares down for everyone;
- **ends a route** that keeps losing money.

A rival reacts to its own flights and to the timetable, never to you directly. It does not start a price war with you, or follow you around.

## Four kinds of rival
Each rival is one of four kinds. A new rival is a kind nobody in the game is yet, while there is one left.

- **Budget** flies narrowbodies packed with economy seats, with the cheapest seats, entertainment and meals, on short and medium routes with plenty of economy passengers. It undercuts the route's fare, keeps its maintenance to the minimum, and is quick to drop a route that loses money.
- **Legacy** flies narrowbodies and widebodies with first and business cabins, the best seats and the best meals, on long routes with plenty of premium passengers. It charges more than the route's fare, looks after its aircraft, hires the best crew it can find, builds a lounge at home once it can pay for one, and is patient with a route that loses money.
- **Regional** flies regional aircraft on short routes, many times a day, with two-star seats and a snack, at about the route's fare.
- **Opportunist** goes wherever the most passengers are left unserved, at any distance, with whatever aircraft it can buy. It prices a little under the route's fare, and drops a losing route faster than anyone.

## No bankruptcy
Nobody goes bankrupt, not you and not a rival. An airline can stay below zero for as long as it likes, but hiring and buying aircraft still need the money in the bank.

A rival short of money does what you would. It borrows first: Skyway Robbery Finance always lends. Then it cuts back: it ends its losing routes, sells aircraft one at a time, though never its last, and lays off the staff it no longer needs. Big layoffs make the [news](intel/news.md#what-makes-the-news), so you can watch a rival shrink.

Once rivals trade [shares](#shares), a rival short of money also sells its shares in other airlines first, and then some of itself, before it borrows. One with nowhere left to borrow but Skyway Robbery sells a little more of itself at every review, even below half.

## Shares
Rivals buy and sell [shares](finance/shares.md) by the same rules as you, from the same public, at the same prices, and only on weekdays: a rival whose review falls on a weekend leaves its shares until Monday. **None trades until you have the Shares node**, and from then on every rival does.

A rival treats you exactly as it treats every other rival. It does not hunt you in particular.

- **It keeps most of itself.** Each kind keeps a different share of itself, but always more than half: Legacy the most, Opportunist the least.
- **Every few years it raises money** by selling itself down to a little under half, and spends it on growing: more aircraft and routes than it would otherwise add. Over the next month or so it buys itself back, as far as the public still has its shares. With a few rivals in a game, expect one round about every game year, and each one makes the news. That is when a rival can be taken over, by you or by another rival.
- **It buys into airlines that look cheap**, when the market's mood has dropped an airline's price well under what it is worth, and sells again when the price is well over. These buys land on healthy airlines too, so a rival holding a few percent of you does not mean it is after you. Budget never does this.
- **It buys up an airline that stays under half.** Every rival but Budget keeps watching an airline that holds less than half of itself with shares available to buy. A week or two is nothing; after somewhere between three weeks and two months, depending on the rival, it starts buying a few percent at every review until it has control or nothing is left to buy. Opportunist moves first, and Regional last. It forgets slowly: an airline that keeps dipping under half is watched sooner each time. Several rivals can go after the same airline.
- **It never borrows to buy shares**, and spends only part of the money it has spare.

**With control of another rival**, it takes it over at its next review. Legacy always absorbs. Regional absorbs an airline that mostly flies regional aircraft, and liquidates any other. Opportunist liquidates an airline that owes more than it is worth, and absorbs any other. See [Absorbing](finance/shares.md#absorbing) and [Liquidating](finance/shares.md#liquidating).

**With control of you**, it does nothing to your airline: you have been acquired, and the game is over. See [Being taken over](finance/shares.md#being-taken-over).

Every 10%, 25% and 40% a rival gets of another airline makes the [news](intel/news.md), and so does control. With a Competent [financial advisor](personnel/jobs/financial-advisor.md) the market tells you when control of a rival is within your reach, and an Impressive [informer](personnel/jobs/informer.md) tells you who holds it.

## What you can find out
- **The [News](intel/news.md)**, for everyone: a rival filing, opening a new destination or a terminal, laying staff off, an aircraft grounded, a Major incident.
- **The [reputation](reputation.md) dialog**, for everyone: each rival's score and its history.
- **The [Shares](finance/shares.md) market**, for everyone: each rival's share price, what it is worth, and how much of it is available to buy.
- **An [informer](personnel/jobs/informer.md)** for everything else: where each rival flies and what it charges, its fleet, how full its flights are, how it is doing for money and who holds its shares, depending on how good they are.
