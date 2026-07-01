# Adventure Atlas — Master Build File

## Product Description

Adventure Atlas is a curated adventure map for discovering lesser-known outdoor places across the United States.

It is not a normal travel app.
It is not a tourist attraction directory.
It is not a random list of popular parks.

Adventure Atlas is for people who want to find the places that make a trip feel unforgettable:

- hidden swimming holes
- rope swings
- waterfalls
- scenic overlooks
- dispersed camping areas
- cliff viewpoints
- hidden beaches
- backroad stops
- hot springs
- kayaking spots
- surf access points
- photo locations
- quiet lakes
- sunrise and sunset spots
- legal public-access adventure areas

The app should feel clean, premium, simple, and easy to understand within seconds.

The goal is simple:

> Open the app, pick the kind of adventure you want, and find somewhere worth going.

---

# 1. Core Mission

Adventure Atlas helps travelers discover real outdoor adventures that most people never find.

The app should focus on quality, not clutter.

The map should not be packed with every restaurant, gas station, hotel, or obvious attraction. It should only show places that feel special, useful, interesting, scenic, adventurous, or worth saving.

A user should be able to open the map and quickly answer:

- Where should I go this weekend?
- Where can I swim?
- Where can I camp?
- Where can I watch sunset?
- Where can I find a quiet spot?
- What is nearby that most tourists miss?
- Is this spot easy, moderate, or sketchy?
- Can I get there with a normal car?
- Is this place legal/public access?
- Is this safe enough for me?

---

# 2. Brand Direction

## Brand Name

Adventure Atlas

## Tagline Options

Primary:

> Discover the places most people never find.

Alternative:

> A map for the adventures that do not show up on normal travel lists.

Alternative:

> Hidden outdoor places. One simple map.

Alternative:

> Find the places worth pulling over for.

## Brand Personality

Adventure Atlas should feel:

- premium
- trustworthy
- outdoorsy
- simple
- calm
- useful
- practical
- young but not childish
- rugged but not messy
- exciting but not chaotic

It should not feel:

- AI-generated
- cluttered
- fake
- scammy
- overhyped
- like a survival bunker app
- like a cheap travel blog
- like a spammy affiliate website
- like a generic Google Maps clone

## Design Inspiration

The design should take inspiration from:

- Apple Maps
- Garmin
- onX
- Arc'teryx
- National Geographic
- National Park Service signage
- high-end outdoor gear websites
- clean field notebooks
- modern dashboard apps

Use this idea:

> Apple built a map app for people who love road trips, swimming holes, camping, and hidden outdoor places.

---

# 3. Visual Design System

## Color Palette

Use an earthy premium outdoor palette.

Primary dark:
- #07110C — deep forest black

Secondary dark:
- #102018 — dark pine green

Surface:
- #16261D — card background

Muted surface:
- #1F3026 — hover/secondary card

Primary accent:
- #D88C45 — burnt orange / trail marker

Secondary accent:
- #7CA982 — sage green

Text:
- #F3F0E8 — warm off-white

Muted text:
- #B7BDAF — soft stone gray

Border:
- rgba(255,255,255,0.12)

Danger / warning:
- #D76545 — red-orange for warnings and safety notes

Success:
- #8BBF8A — calm green

## Typography

Use clean, premium, readable fonts.

Recommended:
- Inter
- Satoshi
- Geist
- Neue Haas Grotesk style
- system font fallback

Headings:
- large
- bold
- tight line height
- confident

Body:
- simple
- readable
- no tiny text
- no walls of text

## Layout Rules

The app should be easy for young people and old people.

Rules:

- one main action per screen
- no cluttered dashboards
- no giant paragraphs
- no tiny hidden buttons
- no excessive icons
- no flashing animations
- no unnecessary gradients
- no fake AI background images
- large tap targets
- clear labels
- clear filters
- strong contrast
- mobile-first

Every screen should answer one question.

If a screen tries to answer five questions, split it.

---

# 4. App Structure

## Main Screens

### 1. Landing / Home

Purpose:
Introduce the product quickly.

Content:
- Adventure Atlas logo
- short tagline
- main call to action
- map preview
- featured categories

Hero copy:

> Discover the places most people never find.

Subtext:

> A curated map of hidden swimming holes, waterfalls, rope swings, campsites, scenic overlooks, and outdoor adventures across the United States.

Buttons:
- Explore the Map
- View Categories

### 2. Map Screen

Purpose:
The main product.

Layout:
- full-screen map
- search bar at top
- filter chips below search
- location cards slide up from bottom on mobile
- side panel on desktop
- clean pins with category icons

The map should feel like the center of the app.

### 3. Spot Detail Page

Purpose:
Tell the user everything they need to know about one place.

Must include:
- name
- category
- state
- county/region if available
- short description
- photos
- coordinates
- difficulty
- adventure score
- crowd level
- best season
- parking notes
- access notes
- safety notes
- road condition
- 4WD required?
- dog friendly?
- swimming allowed?
- camping allowed?
- restrooms?
- cell service?
- time required
- nearby spots
- save/favorite button
- directions button
- report/update button

### 4. Saved Places

Purpose:
Let users save spots.

Features:
- saved list
- categories
- notes
- visited/not visited
- trip folders later

### 5. Submit a Spot

Purpose:
Let users help grow the map.

Submission form:
- spot name
- category
- coordinates or dropped pin
- photos
- description
- public access confirmation
- safety notes
- parking notes
- season notes
- difficulty
- whether user has personally visited

All submissions should be pending approval.

### 6. Admin Dashboard

Purpose:
Let the owner manage the database without editing code.

Admin features:
- add spot
- edit spot
- delete spot
- approve user submissions
- reject submissions
- mark spot as verified
- upload photos
- assign categories
- update safety notes
- feature a spot
- hide a spot

---

# 5. Core User Experience

## First-Time User Flow

1. User opens app.
2. Sees clean hero: "Discover the places most people never find."
3. Taps Explore Map.
4. Map opens to the United States.
5. User taps a filter like Swimming.
6. Map shows hidden swimming places.
7. User taps a pin.
8. Bottom card opens.
9. User sees quick details.
10. User saves the place or opens details.

The experience should feel obvious.

No tutorial should be required.

## Map Interaction

Map should support:
- pan
- zoom
- click pins
- mobile bottom drawer
- desktop side panel
- category filters
- search
- state filter
- location permission optional
- "near me" button later
- cluster pins at low zoom
- show exact locations only when allowed/verified

## Pin Design

Pins should be simple and readable.

Examples:
- water drop for swimming
- waterfall icon for waterfalls
- tent for camping
- camera for photo spots
- mountain for scenic view
- rope icon for rope swing
- wave for surf
- road icon for scenic drive
- star for featured

Do not make pins too colorful or childish.

Use muted category colors.

---

# 6. Categories

The app should focus only on outdoor adventure categories.

## Primary Categories

### Swimming Holes

Places where people can swim in natural water.

Fields:
- water type
- depth
- current strength
- seasonal?
- water temperature notes
- access difficulty
- safety warnings

### Rope Swings

Natural or man-made rope swings near water.

Fields:
- public access
- condition unknown warning
- water depth unknown warning
- safety disclaimer
- last verified date

Important:
Rope swings can be dangerous. The app should never encourage unsafe use. It should provide warnings and tell users to inspect conditions and obey local rules.

### Bridge Jump / Cliff Jump Viewpoints

Handle carefully.

Do not encourage illegal or unsafe jumping.

Better category name:
- Jump Spots / Cliff Views

Safety language:
This app provides location information only. Always verify legality, depth, current, obstacles, and local rules. Do not jump where prohibited.

Fields:
- legal status
- known restrictions
- danger level
- water depth unknown warning
- emergency access notes

### Waterfalls

Fields:
- hike distance
- swimming allowed?
- slippery rock warning
- best season
- flow level notes

### Hidden Beaches

Fields:
- ocean/lake/river
- parking
- tide warning
- beach access
- crowds
- dogs allowed

### Scenic Overlooks

Fields:
- sunrise/sunset
- road access
- hiking required?
- parking
- photo rating

### Dispersed Camping

Fields:
- land agency
- road condition
- 4WD required
- fire restrictions reminder
- stay limit
- permit notes
- Leave No Trace reminder

### Campsites

Non-commercial or lesser-known camping areas.

Fields:
- fee/free
- reservation?
- restrooms
- water
- fire rings
- cell service

### Hot Springs

Fields:
- developed/natural
- clothing rules if relevant
- access
- temperature warning
- crowd level

### Caves

Only legal public-access caves.

Fields:
- permit required?
- gear required?
- bat protection notes
- do not enter closed caves

### Scenic Drives

Fields:
- road type
- vehicle needed
- season
- fuel range notes
- highlights

### Off-Road / Backroad

Fields:
- difficulty
- vehicle clearance
- 4WD required
- seasonal closures
- road legality
- public land notes

### Photography Spots

Fields:
- best time
- lens suggestion
- tripod allowed?
- sunrise/sunset
- composition notes

### Surf Spots

Fields:
- skill level
- board type
- tide
- parking
- local etiquette

### Kayaking / Canoeing

Fields:
- launch point
- takeout
- flow/current notes
- permit notes
- shuttle needed?

### Fishing Spots

Fields:
- license reminder
- species if known
- access
- season

### Stargazing

Fields:
- light pollution
- road access
- camping nearby
- best conditions

### Wildflower / Seasonal

Fields:
- best months
- bloom type
- trail distance
- crowd level

---

# 7. Spot Data Model

Use this as the master schema.

```ts
export type AdventureCategory =
  | "swimming"
  | "waterfall"
  | "rope_swing"
  | "jump_spot"
  | "hidden_beach"
  | "scenic_overlook"
  | "camping"
  | "dispersed_camping"
  | "hot_spring"
  | "cave"
  | "scenic_drive"
  | "off_road"
  | "photography"
  | "surf"
  | "kayaking"
  | "fishing"
  | "stargazing"
  | "wildflower"
  | "other";

export type Difficulty =
  | "easy"
  | "moderate"
  | "hard"
  | "expert"
  | "unknown";

export type CrowdLevel =
  | "quiet"
  | "moderate"
  | "busy"
  | "seasonal"
  | "unknown";

export type AccessStatus =
  | "public"
  | "permit_required"
  | "paid"
  | "seasonal"
  | "unclear"
  | "closed"
  | "private_do_not_enter";

export type VerificationStatus =
  | "unverified"
  | "community_submitted"
  | "owner_verified"
  | "official_source"
  | "needs_update";

export interface AdventureSpot {
  id: string;
  slug: string;
  name: string;
  shortDescription: string;
  longDescription: string;

  category: AdventureCategory;
  secondaryCategories: AdventureCategory[];

  latitude: number;
  longitude: number;

  country: "United States";
  state: string;
  county?: string;
  region?: string;
  nearestCity?: string;

  accessStatus: AccessStatus;
  publicAccessNotes: string;
  parkingNotes: string;
  directionsNotes: string;

  difficulty: Difficulty;
  adventureScore: number; // 1-10
  crowdLevel: CrowdLevel;
  safetyLevel: number; // 1-10 where 10 means more dangerous

  bestSeasons: string[];
  bestTimeOfDay: string[];

  estimatedTimeRequired?: string;
  hikeDistanceMiles?: number;
  elevationGainFeet?: number;

  roadCondition?: string;
  requires4WD: boolean;
  highClearanceRecommended: boolean;

  dogFriendly?: boolean;
  kidFriendly?: boolean;
  restrooms?: boolean;
  waterAvailable?: boolean;
  cellService?: "yes" | "limited" | "no" | "unknown";

  swimmingAllowed?: boolean;
  campingAllowed?: boolean;
  firesAllowed?: boolean;

  warnings: string[];
  leaveNoTraceNotes: string[];

  photos: AdventurePhoto[];

  sourceType: "owner" | "community" | "public_dataset" | "official" | "manual_research";
  sourceNotes?: string;
  verificationStatus: VerificationStatus;
  lastVerifiedAt?: string;

  isPremium: boolean;
  isFeatured: boolean;
  isHiddenFromPublic: boolean;

  createdAt: string;
  updatedAt: string;
}

export interface AdventurePhoto {
  id: string;
  url: string;
  alt: string;
  credit?: string;
  isPrimary: boolean;
}
```

---

# 8. Search Requirements

Search should be fast and forgiving.

Users should be able to search:

- "swimming near Utah"
- "rope swing"
- "waterfalls Colorado"
- "easy camping Arizona"
- "sunset overlook California"
- "dog friendly hike"
- "4wd camping"
- "quiet lake"
- "hot springs"
- "hidden beach"

Search should look at:

- spot name
- category
- description
- state
- region
- nearest city
- tags
- access notes
- difficulty
- season

## Search Result Design

Results should show:
- name
- state
- category
- short description
- difficulty
- crowd level
- adventure score
- distance from user if location allowed

---

# 9. Filter System

Filters should be easy and not overwhelming.

## Primary Filter Chips

- Swimming
- Waterfalls
- Rope Swings
- Camping
- Scenic Views
- Beaches
- Hot Springs
- Off-Road
- Photography
- Surf
- Kayaking

## Advanced Filters

Only show advanced filters when user taps "More Filters."

Advanced filters:
- State
- Difficulty
- Crowd level
- Dog friendly
- Kid friendly
- Free
- Public access
- 4WD not required
- Restrooms
- Camping allowed
- Best in summer
- Best in winter
- Sunrise
- Sunset
- Under 1 mile
- Under 3 miles
- No hiking required
- Verified only

---

# 10. Safety and Legal Rules

This app must be careful with dangerous places.

Especially:
- rope swings
- cliff jumping
- bridge jumping
- swimming holes
- caves
- abandoned places
- off-road routes
- dispersed camping

The app should not encourage illegal entry, trespassing, vandalism, unsafe jumping, or dangerous behavior.

## Safety Disclaimer

Use this language throughout the app:

> Adventure Atlas provides location and planning information only. Conditions change. Always verify access, weather, water depth, road conditions, local rules, and safety before going.

## For Jump Spots

Use stronger wording:

> Jumping into natural water is dangerous and may be illegal. Adventure Atlas does not verify water depth, submerged hazards, current, or legality. Do not jump unless you have personally verified conditions and local rules.

## For Private Property

Never include private property unless there is explicit public access.

If access is unclear, label it:

> Access unclear — verify before visiting.

If private:

> Private property — do not enter.

---

# 11. Data Sourcing Strategy

Important:
Do not scrape random websites without permission.

The app should grow from:

1. Owner-curated spots
2. User submissions
3. Public datasets where allowed
4. Official sources
5. Licensed data
6. Manual research

## Good Sources

- public land agency pages
- National Forest pages
- state park pages
- recreation datasets with reuse permissions
- public GIS datasets
- user submissions
- personal travel research
- original creator content

## Avoid

- copying blog articles
- scraping all websites
- stealing photos
- copying paid guidebooks
- copying private map databases
- revealing sensitive ecological sites
- encouraging overcrowding fragile places

---

# 12. Quality Standard for Adding a Spot

A spot should only be added if it passes at least one of these:

- It is visually interesting.
- It is useful for road trips.
- It offers a unique outdoor experience.
- It is less crowded than obvious nearby attractions.
- It is publicly accessible.
- It has enough information to visit responsibly.
- It fits a clear adventure category.

Do not add:
- generic city parks unless unusually special
- random restaurants
- obvious tourist traps
- unsafe illegal places
- private property
- places with no practical info
- fragile secret ecosystems that should not be promoted

---

# 13. Premium / Free Strategy

The first version can have no payments.

But the app should be designed to support this later.

## Free Version

Free users can:
- view some pins
- search categories
- see general regions
- save limited places
- submit spots

## Premium Version

Premium users can:
- see exact coordinates for premium spots
- save unlimited places
- access full guides
- download offline packs
- use trip planning features
- access state packs
- see advanced filters
- access verified notes

## Premium Locking Rule

Do not make the free version useless.

Free should prove the product is real.

Premium should unlock depth.

---

# 14. Database Tables

Recommended database: Supabase PostgreSQL.

## Tables

### profiles

Fields:
- id
- email
- username
- full_name
- avatar_url
- role
- created_at
- updated_at

Roles:
- user
- premium
- moderator
- admin

### spots

Fields:
- id
- slug
- name
- short_description
- long_description
- category
- secondary_categories
- latitude
- longitude
- country
- state
- county
- region
- nearest_city
- access_status
- public_access_notes
- parking_notes
- directions_notes
- difficulty
- adventure_score
- crowd_level
- safety_level
- best_seasons
- best_time_of_day
- estimated_time_required
- hike_distance_miles
- elevation_gain_feet
- road_condition
- requires_4wd
- high_clearance_recommended
- dog_friendly
- kid_friendly
- restrooms
- water_available
- cell_service
- swimming_allowed
- camping_allowed
- fires_allowed
- warnings
- leave_no_trace_notes
- source_type
- source_notes
- verification_status
- last_verified_at
- is_premium
- is_featured
- is_hidden_from_public
- created_at
- updated_at

### spot_photos

Fields:
- id
- spot_id
- url
- alt
- credit
- is_primary
- created_at

### saved_spots

Fields:
- id
- user_id
- spot_id
- notes
- visited
- created_at

### submissions

Fields:
- id
- user_id
- name
- category
- latitude
- longitude
- state
- description
- access_notes
- safety_notes
- photo_urls
- status
- admin_notes
- created_at
- reviewed_at

Submission statuses:
- pending
- approved
- rejected
- needs_more_info

### reports

Fields:
- id
- user_id
- spot_id
- report_type
- message
- status
- created_at

Report types:
- closed
- dangerous
- wrong_location
- private_property
- bad_info
- duplicate
- other

---

# 15. Tech Stack

Recommended stack:

- Next.js
- React
- TypeScript
- Tailwind CSS
- Supabase
- Mapbox GL JS or MapLibre
- Vercel hosting
- Stripe later
- Supabase Storage for images

## Why

Next.js:
- good for websites and apps
- easy to deploy
- scalable

Supabase:
- database
- auth
- storage
- admin tools
- easy for beginners compared to custom backend

Mapbox/MapLibre:
- interactive map
- pins
- filters
- mobile support

Vercel:
- easy deployment
- connects to GitHub
- free to start

---

# 16. Folder Structure

Use this structure:

```txt
adventure-atlas/
  app/
    page.tsx
    map/
      page.tsx
    spot/
      [slug]/
        page.tsx
    saved/
      page.tsx
    submit/
      page.tsx
    admin/
      page.tsx
  components/
    layout/
      Header.tsx
      MobileNav.tsx
      PageShell.tsx
    map/
      AdventureMap.tsx
      MapPin.tsx
      MapControls.tsx
      SpotPreviewCard.tsx
      SpotDetailDrawer.tsx
      FilterChips.tsx
    spots/
      SpotCard.tsx
      SpotDetail.tsx
      SpotStats.tsx
      SafetyNotes.tsx
    search/
      SearchBar.tsx
      SearchResults.tsx
    ui/
      Button.tsx
      Card.tsx
      Badge.tsx
      Modal.tsx
      Drawer.tsx
  data/
    sample-spots.ts
    categories.ts
  lib/
    supabase.ts
    map.ts
    filters.ts
    search.ts
  styles/
    globals.css
  types/
    spot.ts
  README.md
```

---

# 17. Initial Sample Data

Use this for early testing.

```ts
export const sampleSpots = [
  {
    id: "spot-001",
    slug: "alpine-lake-pulloff-colorado",
    name: "Alpine Lake Pull-Off",
    shortDescription: "Quiet mountain pull-off with sunrise views and cold alpine water nearby.",
    longDescription: "A peaceful roadside stop with mountain views, a short walk to the water, and enough space to sit for sunrise. Best used as a quiet photo stop or quick break during a mountain drive.",
    category: "scenic_overlook",
    secondaryCategories: ["photography"],
    latitude: 39.7392,
    longitude: -105.7821,
    country: "United States",
    state: "Colorado",
    nearestCity: "Idaho Springs",
    accessStatus: "public",
    publicAccessNotes: "Public roadside access. Verify parking signs before stopping.",
    parkingNotes: "Small roadside pull-off. Limited space.",
    directionsNotes: "Use coordinates and check road conditions in winter.",
    difficulty: "easy",
    adventureScore: 7,
    crowdLevel: "quiet",
    safetyLevel: 2,
    bestSeasons: ["summer", "fall"],
    bestTimeOfDay: ["sunrise", "sunset"],
    estimatedTimeRequired: "20-45 minutes",
    roadCondition: "Paved mountain road",
    requires4WD: false,
    highClearanceRecommended: false,
    dogFriendly: true,
    kidFriendly: true,
    restrooms: false,
    waterAvailable: false,
    cellService: "limited",
    swimmingAllowed: false,
    campingAllowed: false,
    firesAllowed: false,
    warnings: ["Limited shoulder parking", "Winter ice possible"],
    leaveNoTraceNotes: ["Pack out all trash", "Do not block road"],
    photos: [],
    sourceType: "manual_research",
    verificationStatus: "unverified",
    isPremium: false,
    isFeatured: true,
    isHiddenFromPublic: false,
    createdAt: "2026-01-01",
    updatedAt: "2026-01-01"
  },
  {
    id: "spot-002",
    slug: "desert-slot-walk-utah",
    name: "Desert Slot Walk",
    shortDescription: "Short sandstone walk with narrow walls and dramatic desert light.",
    longDescription: "A compact desert route with beautiful sandstone textures. Best visited in dry weather. Avoid during storms or flash flood risk.",
    category: "hiking",
    secondaryCategories: ["photography"],
    latitude: 37.1041,
    longitude: -111.8820,
    country: "United States",
    state: "Utah",
    nearestCity: "Kanab",
    accessStatus: "public",
    publicAccessNotes: "Verify current land status and local restrictions.",
    parkingNotes: "Dirt pull-off. Avoid after rain.",
    directionsNotes: "Use offline maps. Service may be limited.",
    difficulty: "moderate",
    adventureScore: 8,
    crowdLevel: "seasonal",
    safetyLevel: 6,
    bestSeasons: ["spring", "fall"],
    bestTimeOfDay: ["morning", "late afternoon"],
    estimatedTimeRequired: "1-2 hours",
    hikeDistanceMiles: 1.5,
    elevationGainFeet: 150,
    roadCondition: "Dirt road",
    requires4WD: false,
    highClearanceRecommended: true,
    dogFriendly: false,
    kidFriendly: false,
    restrooms: false,
    waterAvailable: false,
    cellService: "no",
    swimmingAllowed: false,
    campingAllowed: false,
    firesAllowed: false,
    warnings: ["Flash flood danger", "Extreme heat possible", "No cell service"],
    leaveNoTraceNotes: ["Stay on durable surfaces", "Do not carve sandstone"],
    photos: [],
    sourceType: "manual_research",
    verificationStatus: "unverified",
    isPremium: true,
    isFeatured: true,
    isHiddenFromPublic: false,
    createdAt: "2026-01-01",
    updatedAt: "2026-01-01"
  }
];
```

---

# 18. Homepage Copy

## Hero

Headline:

> Discover the places most people never find.

Subheadline:

> Adventure Atlas is a curated map of hidden swimming holes, waterfalls, rope swings, campsites, scenic overlooks, and outdoor adventures across the United States.

Primary button:

> Explore the Map

Secondary button:

> See Categories

## Problem Section

Title:

> Normal maps show everything. Adventure Atlas shows what is worth finding.

Body:

> Search engines are crowded with tourist spots, ads, and places everyone already knows. Adventure Atlas is built for the places that make a road trip feel real.

## Feature Cards

### Hidden Outdoor Places

> Find swimming holes, waterfalls, rope swings, scenic overlooks, campsites, and more.

### Built for Road Trips

> Save places before you go and build trips around the stops that actually matter.

### Curated, Not Cluttered

> The goal is not millions of pins. The goal is places worth your time.

### Safety and Access Notes

> See parking, access, difficulty, road conditions, and important warnings before you go.

---

# 19. App UX Copy

## Empty State

> No spots found.

Subtext:

> Try removing a filter or searching a nearby state.

## Locked Premium Spot

> Premium spot

Subtext:

> Upgrade to see exact coordinates, access notes, and detailed safety information.

## Save Button

> Save

After saving:

> Saved

## Report Button

> Report an update

Report text:

> Is this place closed, unsafe, private, or listed incorrectly? Let us know.

## Submit Spot

Title:

> Know a place worth adding?

Subtext:

> Submit it for review. We only add places with public access and enough information to visit responsibly.

---

# 20. Admin Rules

Admin should be able to mark a spot as:

- Draft
- Published
- Featured
- Premium
- Needs update
- Closed
- Private / do not show

Admin should review:
- public access
- safety notes
- coordinates
- photo rights
- category
- description quality

Admin should never publish:
- private property
- illegal trespass spots
- sensitive ecological locations
- dangerous locations without warnings
- user-submitted locations with unclear access

---

# 21. Launch Strategy

Do not launch with "every hidden spot in America."

Launch with:

> 500 hand-picked outdoor spots across the U.S.

or

> Top 1,000 lesser-known outdoor adventures in America.

Better to have fewer high-quality places than a huge messy map.

## Suggested Launch Categories

Start with:
- swimming holes
- waterfalls
- scenic overlooks
- dispersed camping
- rope swings
- hidden beaches
- hot springs
- scenic drives

## Suggested First States

Focus on adventure-heavy states:
- Colorado
- Utah
- Arizona
- California
- Oregon
- Washington
- Idaho
- Montana
- Wyoming
- New Mexico
- North Carolina
- Tennessee
- Hawaii
- Alaska

---

# 22. Instagram Marketing Angles

Since the founder has a travel audience, the app should be marketed through videos.

## Video Hooks

- "I built a map for places Google does not make easy to find."
- "This is for people who hate tourist traps."
- "Imagine Google Maps, but only for hidden outdoor adventures."
- "If you road trip, camp, swim, hike, or chase sunsets, this is for you."
- "I wanted one map for every place worth pulling over for."

## Content Ideas

- Show a pin on the app, then show the real place.
- "Free spot of the week."
- "Hidden swimming hole in [state]."
- "Three places to save before your next road trip."
- "Would you go here?"
- "I am building the ultimate adventure map."

---

# 23. Monetization Ideas

Start simple.

## Option 1: One-Time Purchase

$19-$49 for access.

Pros:
- simple
- good for audience launch
- no subscription friction

## Option 2: Subscription

$4.99-$9.99/month.

Pros:
- recurring revenue
- supports updates

Cons:
- higher expectations

## Option 3: State Packs

Example:
- Colorado Pack — $9
- Utah Pack — $9
- Western U.S. Bundle — $29
- Full U.S. — $49

## Option 4: Freemium

Free:
- limited pins
- general regions
- basic filters

Premium:
- exact coordinates
- full database
- saved lists
- offline packs later

Best first model:
Start with freemium + one-time lifetime launch deal.

---

# 24. MVP Definition

The first real version should include:

- landing page
- U.S. map
- category filters
- search
- clickable pins
- spot detail cards
- saved spots using local storage
- submit spot form
- admin data file or simple admin page
- sample database
- mobile responsive design

No need yet:
- subscriptions
- AI
- reviews
- complex social features
- messaging
- full offline mode
- massive automation

Focus on making the map feel amazing.

---

# 25. First Development Prompt

Use this with an AI coding tool:

```text
Build the first production-style version of Adventure Atlas.

Adventure Atlas is a premium curated map of lesser-known outdoor adventures across the United States.

Create a Next.js + TypeScript + Tailwind app.

The first version should include:

1. A clean landing page with premium outdoor branding.
2. A full-screen map page.
3. A search bar.
4. Category filter chips.
5. Clickable adventure pins using sample data.
6. A mobile bottom sheet and desktop side panel for spot details.
7. Saved spots using localStorage.
8. A submit-a-spot form.
9. A clean data model for adventure spots.
10. A calm, premium design using deep forest green, off-black, warm white, sage green, and burnt orange.

Design should feel like Apple Maps + Garmin + National Geographic.

Do not make it cluttered.
Do not use fake AI background images.
Do not use touristy stock design.
Make it simple, premium, and easy enough for anyone to understand.

Use sample data from this file and structure the project so it can later connect to Supabase and Mapbox.
```

---

# 26. Definition of Done

The first version is done when:

- It looks premium on mobile.
- It looks premium on desktop.
- The map is the main focus.
- Filters work.
- Search works.
- Clicking a pin opens a good detail card.
- Users can save a spot.
- Users can submit a spot.
- The code is organized.
- New spots can be added easily.
- It does not feel like an AI-generated demo.
- It feels like the foundation of a real product.

---

# 27. Final Product Standard

Adventure Atlas should feel like something people would send to a friend.

Not because it has a million features.

Because it immediately makes them think:

> I want to go there.

That is the whole product.

Everything else supports that feeling.
