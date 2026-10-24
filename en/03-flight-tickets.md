[🏠 Home](../README.md) › [📚 Contents](README.md) › Chapter 3

---

<p align="center"><img src="../assets/images/ch03-header.png" alt="Chapter 03" width="300"></p>

# Why the Same Flight Ticket Has 200 Different Prices

Open any flight app. Search Mumbai to Delhi, next Friday.

₹4,800. You note it.

Close the app. Open it again tomorrow morning.

₹6,600. Same flight. Same seat class. Same date. You didn't do anything. The price jumped ₹1,800 while you were asleep.

Now ask your friend to search the same flight on their phone right now. Show each other the prices. Different prices again. Possibly.

This is not a glitch. This is one of the most sophisticated pricing systems ever built — and once you understand it, you will never book a flight the same way again.

> **BY THE NUMBERS**
>
> **The Scale of Airline Price Variation**
>
> On a single IndiGo Mumbai–Delhi flight, different passengers sitting side by side might have paid anywhere from ₹1,800 to ₹18,000 — a 10x price range for the exact same aircraft, destination, crew, fuel, and flight time. The seat in 14C is identical whether you paid ₹2,200 or ₹12,000 for it. Every rupee of difference is pure pricing strategy.

## The Economic Fact That Changes Everything

An empty seat on a departed flight is worth exactly zero. Forever.

A clothing retailer with unsold stock can hold a sale, move it to an outlet, store it for next year. A restaurant with unsold food at 9 pm can discount it, use it in tomorrow's prep, give it to staff. A phone company with excess inventory can reduce prices or hold it.

An airline has none of these options. The moment that cabin door closes, every empty seat becomes a permanent, unrecoverable loss. The seat cannot be stored. Cannot be transferred to tomorrow's flight. It evaporates — at precisely the same cost to the airline as if a full-fare passenger had been sitting there.

This asymmetry — massive fixed costs, near-zero variable cost per additional passenger — creates a pricing imperative unlike any other industry: fill every seat at the maximum each specific buyer will pay, because the cost of not filling a seat is total revenue loss, and the cost of filling it at any price above zero is nearly nothing.

| Product | If unsold after peak... | Recovery options | Marginal cost of one more sale |
| :--- | :--- | :--- | :--- |
| T-shirt (retail) | Fashion season over | Sale, outlet, next season | Production cost |
| Restaurant meal | 9 pm leftovers | Discount, staff meal, tomorrow's prep | Ingredients + some labour |
| Hotel room | Night is gone | None — night can't repeat | Cleaning, utilities |
| Airline seat | Departure door closes | NONE — permanently zero | One meal + grams of fuel |

*Airlines face the most severe version of perishable goods economics in any industry*

## Yield Management: Selling 200 Prices for One Product

Airlines solved the perishable seat problem by inventing yield management — the most sophisticated real-time pricing system ever applied to a mass consumer product. Developed in the 1980s by American Airlines. Today, variants are used in hotels, ride-sharing, concert ticketing, and streaming.

Every flight operates with invisible 'pricing buckets' — from cheapest at the bottom to highest at the top. When booking opens, the cheapest bucket is available. The traveler who books four months early gets ₹1,800. As cheap seats sell out, the system moves buyers to the next price bucket. The person who searches two weeks later isn't paying more because the seat changed — they're paying more because earlier price-sensitive buyers exhausted the cheaper inventory.

> **CONCEPT**
>
> **Yield Management**
>
> A pricing strategy that adjusts prices in real time based on demand levels, buyer behaviour, and time remaining before the product expires. Airlines invented it. Hotels refined it (hence why a Mumbai Marriott costs twice as much on New Year's Eve). Uber uses it as surge pricing. BookMyShow uses it for concerts. The goal: maximise total revenue by charging each buyer exactly what they're willing to pay.

> **ASIDE**
>
> *The airline pricing algorithm doesn't know you personally. It just knows someone searched the same flight three times this week and still hasn't booked. That pattern has a name in yield management: 'high-intent, high-willingness.' The algorithm is not cruel. It is just extremely, mechanically good at its job.*

## Why Tuesday Is Cheaper Than Friday (It's Not Random)

Same route. Same aircraft. Same crew. Same fuel burned. Dramatically cheaper on Tuesday afternoon than on Friday evening. This is systematic price discrimination based on who is actually sitting in the seats on each day.

The airline industry has spent decades carefully mapping customer types to booking behavior. Business travelers book close to departure, fly on specific days because meetings are non-negotiable, and are not paying from their own wallets. Leisure travelers book weeks or months in advance, can shift dates by two or three days to save money, and feel every rupee of cost because it comes from their own savings. These two customer populations have almost perfectly inverted behavior patterns — and the pricing algorithm exploits every dimension of that difference.

| Characteristic | Business traveler | Leisure / student traveler |
| :--- | :--- | :--- |
| Typical travel days | Monday morning, Friday evening | Whenever it's cheapest |
| Booking timeline | 0–14 days before departure | Weeks or months in advance |
| Who's paying? | Employer (company expense) | Own savings |
| Price sensitivity | Very low — meeting is non-negotiable | Very high — will shift dates to save ₹1,500 |
| Flexibility | None — schedule is fixed by work | High — can fly Tuesday vs Friday |
| Economic term | Price inelastic demand | Price elastic demand |

*Two passenger types with opposite economics — airlines exploit this difference systematically*

> **ASIDE**
>
> *Business travelers flying on company money are, economically speaking, the airline industry's most valuable customers. Every ₹3,200 leisure fare exists because someone's employer somewhere is paying ₹18,000 for the same seat on the same flight. The next time you get a cheap fare, quietly thank all the business travelers who paid full price on that route.*

This is third-degree price discrimination — charging different prices to different identifiable groups based on observable demand characteristics. The airline doesn't ask 'are you a business traveler?' It uses proxies: Friday evening vs. Tuesday afternoon, two-week booking vs. three-month advance. Same plane. Same distance. Completely different economic value captured.

## How IndiGo Rewrote Indian Aviation Economics

Before 2006, flying in India was a status symbol reserved for the wealthy and corporate. IndiGo entered with the Low-Cost Carrier model: one aircraft type only (reducing maintenance complexity), 25-minute gate turnarounds instead of 60 (more flights per aircraft per day), no free meals, no included seat selection, every optional add-on sold separately.

The base fare is the hook. The add-ons are where additional revenue comes from — seat selection (₹200–700), checked baggage (₹500–1,500), airport meals (₹300–600), priority boarding. IndiGo now controls over 60% of India's domestic aviation market — the largest single-airline market share in any major aviation market globally.

In 2000, India had approximately 25 million air passengers per year. By 2023, it was 152 million. The low-cost model IndiGo pioneered made flying accessible to the Indian middle class in a way that genuinely hadn't been true before 2006.

To understand what IndiGo built, compare it to what came before. Air India — the government-owned legacy carrier — operated with the cost structure and service mentality of a state entity: generous employee benefits, full-service meals on every flight, a wide fleet of different aircraft types each requiring different maintenance certifications and spare parts, and the institutional inertia of an organisation that had never needed to compete seriously for customers. Air India's costs per available seat kilometre — the standard aviation efficiency metric — were dramatically higher than IndiGo's. When low-cost carriers entered, Air India couldn't match their prices without losing money on every seat, and couldn't maintain their service differentiation because passengers increasingly chose price over the modest service advantage.

The IndiGo model also introduced a different relationship between the airline and its cost structure. By flying only Airbus A320-family aircraft, IndiGo needed one set of pilot type ratings, one maintenance training program, one spare parts inventory. A pilot qualified on A320s can fly any IndiGo aircraft in the fleet. A maintenance technician trained on A320 engines can service any engine in the fleet. This standardisation created cost advantages that compounded over time: lower training costs, higher asset utilisation, simpler scheduling, and significant bulk purchasing power with Airbus — IndiGo has historically been one of Airbus's largest single customers globally, giving it pricing leverage that smaller airlines with mixed fleets simply cannot achieve.

## How to Actually Beat the Algorithm

| Strategy | Why it works | Typical savings |
| :--- | :--- | :--- |
| Book 6–8 weeks ahead | Cheap buckets still open, algorithm not panic-pricing | 30–50% vs same-day |
| Fly Tuesday/Wednesday | Leisure pricing segment, not business pricing | 20–40% vs Friday |
| Search in incognito mode | Avoids repeated-search demand signal | Varies, always worth doing |
| Morning flights | Lower demand, lower algorithm price | 10–20% vs evening |
| Flexible ±3 days on dates | Google Flights shows cheapest day in range | ₹1,000–3,000 typical |
| Compare train for under 500km | Airport time often nets negative vs train | Sometimes not worth flying |

*Use the system's logic against it — the algorithm has zero loyalty to you*

Each of these strategies works because it exploits the internal logic of the yield management algorithm. The algorithm is designed to extract maximum revenue from each booking as it comes in — it is not designed to give you a good deal. But because it follows rules, understanding the rules means you can time and structure your booking to land in cheaper pricing buckets.

The incognito mode point deserves specific elaboration because it is widely misunderstood. The evidence for price increases based on repeated searches is mixed — some airlines and booking platforms definitely use cookie-based demand signals; others do not. What is certain is that using incognito mode costs you nothing and might save you hundreds of rupees, so it is always worth doing. More importantly, comparing prices across multiple platforms — not just one app — consistently reveals price differences for the same flight. Airline websites, MakeMyTrip, Cleartrip, Ixigo, and Google Flights often show different prices for the same route because each has different commercial agreements with airlines and different real-time inventory access. Checking two or three sources takes five extra minutes and regularly saves more than that effort is worth in rupee terms.

There is also a conceptual lesson in the 'how to beat the algorithm' discussion that applies far beyond flight booking. Once you understand that a price you see is not a neutral, objective fact but an output of a system designed to maximize the seller's revenue based on information about you and the market at that moment — you start to approach all pricing differently. The sticker price on a car. The insurance renewal premium. The contractor's first quote. The bank's offered interest rate. All of these are opening bids, calibrated to what the seller believes you will accept. In every case, more information and willingness to compare alternatives shifts power toward the buyer. This is one of the most practical applications of economics in daily financial life.

> **THE TAKEAWAY**
>
> What This Means For You: Every flight price you see is the result of an algorithm calculating what you specifically are willing to pay at that specific moment, based on your search history, the day, the time, remaining seats, and dozens of variables. It has zero loyalty to you. Use incognito mode, be flexible on dates when possible, and book when the algorithm isn't watching you search the same route repeatedly.

---

### ✅ Quick Check

*Let's see if you were actually reading, or just admiring the tables...*

**1. Why is an empty airline seat at departure worth exactly zero?**

- **A** — Because airlines don't track unsold seat inventory
- **B** — Because it creates a permanent, unrecoverable revenue loss — it can't be stored, moved, or sold later
- **C** — Because airlines issue refunds for empty adjacent seats
- **D** — Because seat manufacturing costs are already fully depreciated

**2. The primary goal of yield management is to:**

- **A** — Maximise fuel efficiency per passenger carried
- **B** — Ensure that all passengers pay equal prices for fairness
- **C** — Maximise total revenue by charging each buyer what they're willing to pay
- **D** — Comply with DGCA domestic fare regulations

**3. Why do business travelers consistently pay more than leisure travelers for the same seat?**

- **A** — They receive larger seats and better meals included in the price
- **B** — They typically book last-minute and have low price sensitivity because someone else is paying
- **C** — Airlines apply corporate customer surcharges to business accounts
- **D** — Business class routes have higher fuel and navigation costs

**4. IndiGo's low-cost carrier model works primarily because:**

- **A** — IndiGo uses significantly older and cheaper aircraft than full-service airlines
- **B** — Pilots at IndiGo earn substantially lower salaries than at Air India
- **C** — The government provides IndiGo with fuel cost subsidies
- **D** — Base fares are kept attractively low while revenue comes from optional paid add-ons

<details>
<summary><b>REVEAL ANSWERS</b></summary>

1. **B** — Because it creates a permanent, unrecoverable revenue loss — it can't be stored, moved, or sold later
2. **C** — Maximise total revenue by charging each buyer what they're willing to pay
3. **B** — They typically book last-minute and have low price sensitivity because someone else is paying
4. **D** — Base fares are kept attractively low while revenue comes from optional paid add-ons

</details>

---

<div align="center">

[← Chapter 2](02-netflix.md) · [📚 Contents](README.md) · [Next: Chapter 4 →](04-iphone.md)

</div>
