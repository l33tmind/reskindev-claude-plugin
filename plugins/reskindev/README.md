# Reskindev plugin for Claude

Reskindev (https://reskindev.com) is a freelance marketplace. This plugin lets you use it by chatting with Claude.

## What you can do

**Buyers (no sign-in needed)**
- Find freelancers for a job: "Find someone on Reskindev to edit my YouTube videos, budget $30."
- Compare gigs by price, delivery time, stars and reviews.
- Read a seller's profile and what buyers said about them.
- Ordering and payment happen on reskindev.com or in the Reskindev app.

**Sellers (sign in to Reskindev once)**
- Post a gig by chatting: Claude asks simple questions, writes the title and description in English and Bangla, builds Basic / Standard / Premium packages, suggests prices from similar gigs, and prepares the thumbnails.
- Sell in the Bangladesh market (taka), the Global market (dollars), or both, with a separate thumbnail for each.
- Edit a gig, and (Reskindev Pro) ask how your gigs are doing.
- Every gig is reviewed by Reskindev before it goes live.

## What is inside

- Two connectors: `reskindev-hire` (https://reskindev.com/mcp/hire, public, read-only) and `reskindev` (https://reskindev.com/mcp, sign in with your Reskindev account).
- Two skills: `hire-freelancer` and `post-gig`.

## Privacy

The buyer connector returns only what reskindev.com shows to signed-out visitors. The seller connector can read and create your own gigs; it cannot see your password, orders, money or messages. Privacy policy: https://reskindev.com/privacy-policy

## Support

https://reskindev.com/support
