---
name: hire-freelancer
description: Find, compare and choose a freelancer on Reskindev (reskindev.com) for a job the user needs done, such as a logo, video editing, Facebook ads, a website or an app. Use when the user wants to hire someone, asks who can do a task, or asks about a Reskindev gig, seller, price or review.
---

# Hire a freelancer on Reskindev

Reskindev (reskindev.com) is a freelance marketplace. Sellers post gigs (services at a fixed price); buyers order a gig and pay through Reskindev, which holds the money until the work is delivered.

Use the `reskindev-hire` tools. They need no sign-in. (The signed-in `reskindev` server has the same five tools.)

## Steps

1. Understand the job: what the user needs, the budget and the deadline. Ask only what is missing, one question at a time. Talk in the user's language (Bangla or English).
2. Pick the market: a buyer in Bangladesh who pays in taka uses `market: "bangladesh"` (prices in ৳, links to reskindev.com/bd). Everyone else uses the default `"global"` (prices in $). Ask only if it is unclear.
3. Search with `find_freelancers` using the user's own words. Typos, Bangla and Banglish work. Use `max_price` and `sort` when the user gave a budget or wants the cheapest or best rated.
4. Compare the best 3 to 5 gigs in a short table: title, seller, stars and number of reviews, starting price, fastest delivery, link.
5. Before recommending one, check it: `get_gig` for the packages and what each includes, `get_seller_profile` for reply speed, languages and the blue tick, `get_seller_reviews` for what buyers said.
6. Recommend one or two with the reason, and say which package fits the user's budget and deadline.
7. To order, pay or message the seller, the user opens the gig link on reskindev.com or in the Reskindev app and signs in. These tools cannot place orders or send messages.

## Rules

- Show only what the tools return. Never invent gigs, prices, ratings or reviews.
- Always give the gig's `url` so the user can open it.
- A new seller with no reviews is not bad; say so honestly and point to their profile and reply speed.
- If nothing matches, try simpler words or drop the filters, then say so plainly.
