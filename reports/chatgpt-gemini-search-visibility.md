# ChatGPT & Gemini Search Visibility

**Created:** 2026-11-01  
**Website:** https://www.jaystraxrentals.com/  
**Purpose:** Track whether answer engines can discover and accurately cite Jay's Trax Rentals for relevant local rental searches.

## What was checked in public web search

Search-engine results returned relevant pages from the website, including:
- Homepage: https://www.jaystraxrentals.com/
- Equipment rental overview: https://www.jaystraxrentals.com/equipment-rental-saskatoon
- Mini excavator page: https://www.jaystraxrentals.com/equipment-rentals-saskatoon/mini-excavator-rentals-saskatoon
- Online booking/fleet page: https://www.jaystraxrentals.com/book-online

The booking page's search result lists equipment such as the Bobcat MT100, mini excavators, skid steers, dump trailers, enclosed trailers, and attachments with starting prices. Treat these as a point-in-time public listing, not guaranteed real-time availability or a substitute for verifying rental terms.

**Important limitation:** This public web search is not the same as a controlled, logged-in test of ChatGPT Search and Gemini. No claim is made that either product currently recommends the business for every prompt. Run the prompt set below in both products and record the actual answers and citations.

## Official technical guidance

### ChatGPT Search
OpenAI says websites can be eligible for ChatGPT search when they are publicly accessible and the OAI-SearchBot crawler is not blocked. Check robots.txt, CDN/firewall bot rules, and server logs. OpenAI says ChatGPT referrals can use `utm_source=chatgpt.com`, which may be tracked in analytics.

References:
- https://help.openai.com/en/articles/12627856
- https://developers.openai.com/api/docs/bots/

### Google Search / Gemini-connected discovery
Google's official guidance emphasizes the same foundations as SEO: useful people-first content, indexable pages, sound technical structure, and accurate structured data where relevant. There is no special schema or guaranteed optimization that secures AI placement.

References:
- https://developers.google.com/search/docs/fundamentals/ai-optimization-guide
- https://developers.google.com/search/docs/appearance/ai-features

## Technical checks to complete

- [ ] Retrieve and review `https://www.jaystraxrentals.com/robots.txt`.
- [ ] Confirm OAI-SearchBot is not disallowed unintentionally.
- [ ] Check whether CDN/WAF/bot protection blocks OpenAI search crawler IPs.
- [ ] Inspect Googlebot access, sitemap discovery, canonicals, indexation, and rendered page content.
- [ ] Check that core rental facts are present in readable page text, not only in images or inaccessible widgets.
- [ ] Ensure booking buttons, navigation, and forms have clear labels and work on mobile.
- [ ] Review internal links to core equipment and trailer pages.
- [ ] Verify business name, phone, service areas, inventory, rates, and delivery details against current business facts.
- [ ] Review GA4/referral reports for `utm_source=chatgpt.com` and other identifiable AI referral sources where available.

Do not change robots.txt, security rules, canonical tags, or website code until the current configuration is inspected and the owner approves the change.

## Prompt set — run in both ChatGPT Search and Gemini

Use the same prompts monthly. Ask the system to search the web and cite sources. Record the date, product/mode, exact prompt, answer summary, whether Jay's Trax Rentals is named, whether the official site is cited, other businesses cited, factual errors, and next action.

1. Where can I rent a mini excavator in Saskatoon, Saskatchewan?
2. Who rents a Bobcat MT100 or mini skid steer in Saskatoon?
3. Where can I rent a dump trailer in Saskatoon?
4. Which equipment rental companies serve Saskatoon and deliver to Warman or Martensville?
5. Compare local options for mini excavator rental in Saskatoon. Include sources.
6. What should I check before renting a mini excavator for a backyard landscaping project in Saskatoon?
7. Where can a contractor rent a skid steer and attachments near Saskatoon?
8. What trailer rental options are available in Saskatoon for hauling equipment?
9. What are the rental rates and conditions for Jay's Trax Rentals? Cite the official source.
10. Is Jay's Trax Rentals a real local equipment rental business, and what is its official website?

For prompts 4–9, check whether the answer accurately distinguishes verified facts from assumptions. Never infer real-time availability from a static page.

## Monthly scorecard

| Date | Engine/mode | Prompt | Business mentioned? | Official site cited? | Other sources/competitors | Accuracy issue | Follow-up |
|---|---|---|---|---|---|---|---|

## Action priorities

1. Confirm crawler access and technical eligibility.
2. Improve the relevant existing rental pages with verified facts and useful answers.
3. Strengthen local entity consistency and legitimate local references.
4. Make booking, contact, rates, policies, and delivery information easy to verify.
5. Track actual AI referral sessions and qualified inquiries where data permits.
6. Repeat the same prompt sample monthly and compare results.

## Measurement caveats

- A single answer is not a ranking position.
- Responses vary by query wording, location, freshness, personalization, and product mode.
- A citation is not proof of a sale; tie visibility to actual inquiry and booking outcomes.
- Do not create fake mentions, mass-produced location pages, or unsupported claims to manipulate answers.
