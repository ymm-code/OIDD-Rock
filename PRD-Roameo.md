# Product Requirements Document — Roameo

**Project:** Roameo Website (MVP)
**Version:** 2.0
**Date:** 2026-04-26
**Status:** Draft

---

## 1. Overview

Roameo is a travel-social platform that consolidates the most fragmented parts of travel research — restaurant discovery, attraction recommendations, local cultural insight, transportation, and accommodations — into a single, community-driven experience. Where travelers today bounce between Yelp, TikTok, Reddit, TripAdvisor, and a hotel booking site, Roameo serves as the one destination for the full journey: from deciding where to go, to planning what to do, to sharing live updates while you're there.

The MVP is a responsive website designed to feel and behave like a mobile app, launching with a curated set of European destinations.

---

## 2. Problem Statement

Planning a trip today is deeply fragmented. A traveler going to Lucerne, Switzerland might use:
- **TikTok or Instagram** for attraction inspiration
- **Yelp or Google Maps** for restaurant reviews
- **Reddit** for local customs and honest advice
- **TripAdvisor** for hotel reviews
- **A separate booking site** for accommodations and flights
- **Government sites** for visa and vaccination requirements

Each platform surfaces a flood of content with no shared context or continuity. Users waste hours synthesizing information that should live in one place. Roameo solves this by becoming the single platform travelers open — before, during, and after a trip.

---

## 3. Goals

- Launch a responsive web MVP covering European destinations
- Enable destination discovery through a personalized questionnaire (2–6 suggestions)
- Surface community-generated photo/video content organized by destination and category
- Link out to trusted third-party sources (TripAdvisor, Google Reviews, Yelp) for supplementary reviews
- Link out to booking partners (OpenTable, Resy, hotels, experiences) for reservations
- Support live content posting by travelers currently in a destination
- Establish the foundation for boosted listings and affiliate revenue

---

## 4. Target Users

| Segment | Description |
|---|---|
| Travel Enthusiasts | Frequent travelers seeking a centralized, efficient planning tool |
| Busy Professionals | Limited planning time; want a streamlined path from inspiration to itinerary |
| Novice Travelers | Overwhelmed by complexity; need guided, approachable support |
| Cultural Explorers | Prioritize immersive local experiences; value authentic community insight |
| Budget-Conscious Travelers | Need visibility into cost across food, accommodation, and activities |

---

## 5. The Three Phases of User Experience

Roameo serves users across three distinct moments in a trip:

**Phase A — Research**
User explores destinations, reads community posts, and links out to external review platforms to evaluate options.

**Phase B — Planning**
User completes the questionnaire, receives destination suggestions, and builds an itinerary by clicking through to partner booking platforms (restaurants, hotels, experiences).

**Phase C — Live Travel**
User is in-destination and posts photo/video updates to their destination's community feed in real time — enriching the platform for future travelers.

---

## 6. User Stories

**Discovery & Destination Selection**
- As a user, I want to fill out a short questionnaire (budget, dates, travel style, interests) so I receive 2–6 destination suggestions matched to my preferences.
- As a user, I want each suggestion to include a destination overview, estimated cost range, best time to visit, and vibe summary so I can make a confident choice.

**Research & Content**
- As a user, I want to browse photo/video posts from other travelers and locals, organized by category (food, attractions, culture, accommodation, transport) so I can research authentically.
- As a user, I want to see curated links to TripAdvisor, Google Reviews, and Yelp for a destination so I can access third-party reviews without leaving Roameo's context.

**Booking**
- As a user, I want to see restaurant and hotel recommendations with direct links to OpenTable, Resy, or hotel booking pages so I can complete reservations without searching elsewhere.

**Travel Logistics**
- As a user, I want to see visa requirements, vaccination recommendations, currency exchange rates, and language basics for my destination so I have everything I need in one place.

**Live Posting**
- As a traveler currently in a destination, I want to post photos and short videos to that destination's community feed so I can share my real-time experience.
- As a user researching a destination, I want to see live posts from travelers currently there so I get the most current perspective.

**Content Creators / Guides**
- As a guide (any user with destination experience), I want to create posts about a destination tagged by category so other travelers can discover my content contextually.
- As a guide, I want a profile page showing my posts, the destinations I've covered, and basic engagement stats.

---

## 7. Features — MVP

### 7.1 Destination Questionnaire
- Multi-step form: budget range, trip duration, travel dates, travel style (adventure / relaxation / culture / food / nightlife), group size, must-see destination types
- Outputs 2–6 European destination recommendations ranked by match
- Each result card includes: destination name, hero image, vibe summary, estimated daily cost, best season to visit

### 7.2 Destination Pages
Each destination has a dedicated page containing:

**Community Feed**
- Instagram-style photo/video posts from any user who has visited or is currently visiting
- Filterable by category: Food & Drink, Attractions, Accommodation, Local Culture, Getting Around
- Sorted by recency by default; option to sort by engagement
- "Live Now" tag on posts made within the last 48 hours

**External Resources (linked, not embedded)**
- TripAdvisor link for the destination
- Google Reviews link
- Yelp link (where available)
- Links open in a new tab

**Booking Links**
- Restaurant recommendations with OpenTable / Resy click-through links
- Hotel recommendations with booking platform click-through links
- Experience recommendations (tours, activities) with partner click-through links

**Essential Info**
- Visa requirements (with source link)
- Vaccination recommendations (with source link)
- Currency and current exchange rate
- Language basics (greetings, phrases)
- Emergency contacts

### 7.3 Post Creation
- Any logged-in user can create a post for a destination
- Supports photo upload and short video upload
- Required: destination tag, category tag
- Optional: caption, location within destination, rating
- Posts appear immediately in the destination's community feed

### 7.4 User Profiles
- Sign up / log in via email or OAuth (Google)
- Profile displays: posts created, destinations visited, saved destinations
- Users can follow other users and see their posts in a personal feed

### 7.5 Saved & Personal Feed
- Save destinations to a personal list
- Save individual posts
- Personal feed showing posts from users you follow

### 7.6 Search
- Search by destination name
- Filter by category within destination pages
- Browse all European destinations via an explore page

### 7.7 Boosted Listings (Advertising)
- Local restaurants, hotels, and travel brands can pay for boosted placement within destination pages
- Boosted posts are visually labeled ("Sponsored") and appear at the top of relevant category feeds
- Both local businesses and travel brands are eligible advertisers

---

## 8. Features — Future Phases

### Phase 2 — North America + Enhanced Social
- Add North American destinations
- Direct messaging between users
- Influencer partnership program (verified guide badges)
- Targeted email marketing campaigns

### Phase 3 — East Asia + Premium Subscription
- Add East Asian destinations
- Premium tier: ad-free experience, exclusive content, early destination access
- AI itinerary builder based on questionnaire output

### Phase 4 — Global + Deep Affiliate Integration
- Global destination coverage
- Deeper affiliate integrations (in-app booking flow vs. click-through)
- Local business partnership and affiliate program
- Commission sharing with creators who drive bookings

---

## 9. Revenue Model

| Stream | Mechanism | MVP? |
|---|---|---|
| Boosted listings — local businesses | Restaurants, hotels pay for featured placement in destination feeds | Yes |
| Boosted listings — travel brands | Airlines, tourism boards, travel brands pay for sponsored content | Yes |
| Affiliate commissions — dining | Cut from bookings via OpenTable / Resy click-throughs | Yes |
| Affiliate commissions — accommodation | Cut from hotel bookings via partner links | Yes |
| Affiliate commissions — experiences | Cut from tour / activity bookings via partner links | Yes |
| Influencer / creator sponsorships | Brands pay to sponsor specific guide profiles or posts | Phase 2 |
| Premium subscription | Ad-free access + exclusive features for a recurring fee | Phase 3 |

---

## 10. Non-Goals (MVP)

- Native iOS or Android app
- In-app booking completion (click-through only for MVP)
- Inline embedding of TripAdvisor / Google / Yelp content (external links only)
- Content moderation system
- Direct messaging
- Flight search or booking
- Offline mode

---

## 11. Design Principles

- **App-like feel on web:** Responsive design, bottom navigation on mobile, fast transitions — users should forget they're in a browser
- **Community first:** User-generated photo/video content leads every destination page; curated links are secondary
- **Recency matters:** Live posts from travelers currently in a destination are surfaced prominently
- **Frictionless booking:** Partner links should be 1 tap away from any restaurant or hotel mention
- **Trustworthy logistics:** Visa, vaccination, and currency data is always sourced and timestamped

---

## 12. Technical Considerations

- Responsive web app (mobile-first layout, functions as a PWA where possible)
- Photo and video upload + storage (cloud storage: S3 or equivalent)
- OAuth login (Google as minimum)
- External link management for TripAdvisor, Google, Yelp, OpenTable, Resy, hotel partners
- Currency exchange rate API (refreshed daily)
- GDPR compliance required given European launch and user data collection
- No content moderation pipeline needed for MVP

---

## 13. Success Metrics — MVP

| Metric | Target |
|---|---|
| Questionnaire completion rate | > 65% of users who start |
| Destination page time-on-page | > 4 minutes average |
| Posts per destination at launch | Minimum 15 posts across 3+ categories |
| Booking link click-through rate | > 10% of destination page visitors |
| User account creation rate | > 35% of returning visitors |
| Live posts (tagged in last 48h) per destination per week | > 3 |

---

## 14. Implementation Timeline

| Phase | Scope | Geography | Status |
|---|---|---|---|
| Phase 1 — MVP | Questionnaire, destination pages, photo/video posts, external links, boosted listings, affiliate links | Europe | In development |
| Phase 2 | Social graph, DMs, influencer program | + North America | Planned |
| Phase 3 | Premium subscription, AI itinerary builder | + East Asia | Planned |
| Phase 4 | In-app booking, creator affiliate program | Global | Planned |

---

## 15. Open Questions

- What is the source and refresh cadence for visa/vaccination data — government APIs or manual curation?
- How are boosted listing advertisers onboarded for MVP — self-serve portal or direct sales?
- Which European destinations are included at launch — curated shortlist or open to any European city?
- What affiliate partnerships need to be established before launch (OpenTable, Resy, hotel platforms)?
- Is there a minimum post threshold before a destination page goes live?
