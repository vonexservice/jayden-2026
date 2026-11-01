# Booking and Inquiry Conversion Tracking

## Objective

Measure whether organic search and local visibility produce qualified rental inquiries and completed bookings. Do not treat clicks or impressions alone as sales outcomes.

## Events to audit

Confirm which events are already tracked before adding anything.

| Event | Suggested meaning | Important notes |
|---|---|---|
| `view_item` | Visitor views an equipment or trailer detail | Include a stable item identifier where possible |
| `select_item` | Visitor selects a rental from a list/category | Use consistent item/category naming |
| `click_book` | Visitor clicks a booking CTA | This is a step, not a completed booking |
| `begin_checkout` | Visitor begins a booking/checkout flow | Validate with the booking platform |
| `generate_lead` | Visitor submits a genuine inquiry | Avoid counting validation errors or spam |
| `purchase` | Completed booking/payment, if supported | Use transaction ID to prevent duplicates |
| `click_to_call` | Visitor clicks a phone link | A click is not proof of a connected call |
| `email_click` | Visitor clicks a mail link | A click is not proof of a qualified lead |

## Implementation workflow

1. Identify the site's current platform and booking provider.
2. Audit existing GA4, tag manager, and booking-platform integrations.
3. Test events in a staging/test flow where available.
4. Confirm consent/privacy settings and avoid sending personal information to analytics.
5. Mark only meaningful lead or completed-booking events as conversions.
6. Test duplicate firing, cross-domain measurement, referral exclusions, and attribution.
7. Compare event counts with actual booking/inquiry records where authorized.
8. Document event names, triggers, parameters, owner, and validation date.

## Core dashboard

- Organic sessions and landing pages
- Search Console clicks, impressions, CTR, average position
- Booking CTA clicks and booking starts
- Submitted inquiries
- Completed bookings and booking revenue, if available
- Lead-to-booking rate
- Organic and local lead share
- Performance by equipment type and location where data is reliable

## Reporting cautions

- Never label booking starts as completed bookings.
- Do not assume every call click becomes a call.
- Note tracking gaps and changes in instrumentation.
- Use consistent date ranges and compare like-for-like periods.
- Protect customer data; report aggregate results whenever possible.
