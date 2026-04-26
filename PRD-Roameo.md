# Product Requirements Document — Roameo

**Project:** Roameo Website (MVP)
**Version:** 1.0
**Date:** 2026-04-26
**Status:** Draft

---

## 1. Overview

Roameo is a travel-social platform that consolidates fragmented travel planning into a single, community-driven experience. It combines personalized destination discovery, social content from local guides, and essential travel logistics — replacing the need for multiple apps with one cohesive product.

---

## 2. Problem Statement

Travelers today must juggle multiple apps — maps, hotel search, restaurant reviews, social media, visa checkers — to plan a single trip. Social platforms like Instagram and TikTok surface travel content but bury it in noise and repetition. No single platform combines the human insight of social media with the practical depth of a travel resource. This fragmentation causes decision fatigue, missed cultural context, and a poor planning experience.

---

## 3. Goals

- Launch a web-based MVP focused on North American destinations
- Enable users to discover destinations through a personalized questionnaire
- Surface guide-generated content (locals and influencers) organized by destination
- Provide essential travel logistics in-app (visa, vaccination, currency)
- Establish a foundation for a social layer and subscription model in later phases

---

## 4. Target Users

| Segment | Description |
|---|---|
| Travel Enthusiasts | Frequent travelers seeking a more efficient, centralized planning tool |
| Busy Professionals | Limited planning time; need streamlined, organized itinerary creation |
| Novice Travelers | Overwhelmed by complexity; need guided, approachable planning support |
| Cultural Explorers | Prioritize immersive local experiences; value cultural insights |
| Budget-Conscious Travelers | Prioritize cost; need visibility into affordable options across categories |

---

## 5. User Stories

**Discovery & Destination Selection**
- As a user, I want to fill out a questionnaire about my budget, timeline, travel style, and must-see destinations so that I receive 2–6 personalized destination suggestions.
- As a user, I want to browse destination suggestions with enough context (climate, vibe, cost range) to make a confident choice.

**Itinerary & Content**
- As a user, I want to browse posts from guides about a destination's restaurants, attractions, local culture, and hidden gems so that I can build an authentic itinerary.
- As a user, I want to filter guide content by category (food, accommodation, activities, cultural norms) so that I find relevant information quickly.

**Travel Logistics**
- As a user, I want to see visa requirements, vaccination recommendations, and currency exchange rates for my destination in-app so that I don't need to visit external sites.

**Guides (Content Creators)**
- As a guide, I want to create and publish posts about destinations I know well so that I can share expertise and build an audience.
- As a guide, I want my content organized by destination and category so that travelers can discover it contextually.

---

## 6. Features — MVP (Phase 1)

### 6.1 Destination Questionnaire
- Multi-step form collecting: budget range, trip duration, travel dates, travel style (adventure / relaxation / culture / food), must-see destinations, group size
- Outputs 2–6 destination recommendations ranked by match score
- Each recommendation includes: destination overview, estimated cost range, best time to visit, vibe summary

### 6.2 Destination Pages
- Hero image and summary
- Guide posts organized by category: Restaurants, Attractions, Accommodation, Cultural Norms, Getting Around
- Essential Info section: visa requirements, vaccination recommendations, currency and exchange rate, language basics, emergency contacts

### 6.3 Guide Posts
- Text + image posts created by verified guides
- Tagged by destination and category
- Displayed chronologically with recency filter
- Guide profile: name, bio, destinations covered, post history

### 6.4 User Accounts
- Sign up / log in (email or OAuth)
- Save destinations and posts to a personal list
- Track questionnaire results and revisit suggestions

### 6.5 Basic Search
- Search by destination name
- Filter by category within destination pages

---

## 7. Features — Future Phases

### Phase 2 — Social Layer + Europe Expansion
- Embedded social feed per destination (follows, likes, comments on guide posts)
- Expand destination library to European cities
- Targeted marketing campaigns (influencer partnerships, email)

### Phase 3 — East Asia Expansion + Premium Subscription
- Add East Asian destinations
- Premium subscription tier: ad-free experience, exclusive guide content, early access to new destinations
- AI-enhanced itinerary builder

### Phase 4 — Global Expansion + Affiliate Revenue
- Expand beyond North America, Europe, East Asia
- Affiliate links to hotels, airlines, local businesses (commission-based)
- Local business partnership program

---

## 8. Revenue Model

| Stream | Mechanism |
|---|---|
| Targeted advertising | Ads served based on user demographics, interests, and destination intent |
| Pay-per-click | Revenue tied to user interactions with advertiser content |
| Sponsorships | Travel brands sponsor destination content or guide posts |
| Affiliate commissions | Commission earned when users click through to partner booking platforms |
| Premium subscription | Recurring fee unlocking exclusive content and features (Phase 3+) |

---

## 9. Non-Goals (MVP)

- Native mobile app (web-first for MVP)
- Real-time flight or hotel booking (affiliate links only)
- User-generated posts from non-verified guides
- Live chat or direct messaging between users
- Offline mode

---

## 10. Design Principles

- **One place for everything:** Users should never need to leave the app to complete a planning task
- **Human-first content:** Guide posts take priority over algorithmic or sponsored content in the feed
- **Low friction:** The questionnaire to destination suggestion flow should take under 3 minutes
- **Trustworthy logistics:** Visa, vaccination, and currency data must be clearly sourced and timestamped

---

## 11. Technical Considerations

- Web-first responsive design (mobile-compatible from day one)
- Cloud-based infrastructure to support scaling across phases
- Data privacy compliance (GDPR, CCPA) required given user profile and preference data
- Content moderation workflow for guide post approval
- API integrations needed: currency exchange rates, visa requirement data, vaccination advisories

---

## 12. Success Metrics — MVP

| Metric | Target |
|---|---|
| Questionnaire completion rate | > 70% of users who start complete it |
| Destination page time-on-page | > 3 minutes average |
| Guide posts per destination (at launch) | Minimum 10 posts across 3+ categories |
| User account creation rate | > 40% of returning visitors |
| Saved destinations per active user | > 2 per session |

---

## 13. Implementation Timeline

| Phase | Scope | Status |
|---|---|---|
| Phase 1 | MVP — North America, questionnaire, guide posts, essential info | In development |
| Phase 2 | Social layer, Europe expansion | Planned |
| Phase 3 | East Asia, premium subscription | Planned |
| Phase 4 | Global expansion, affiliate program | Planned |

---

## 14. Open Questions

- Who verifies and onboards guides for MVP — internal curation or application form?
- What is the source and refresh cadence for visa/vaccination data?
- Is the questionnaire output static (fixed destination list) or dynamic (algorithm-ranked)?
- What is the content moderation policy for guide posts?
- Will guides be compensated in MVP, or is exposure the primary incentive?
