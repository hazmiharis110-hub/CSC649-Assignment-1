# Part B3: User Stories and Acceptance Criteria

Each story uses the form "As a [user], I want [goal], so that [benefit]". Each story is linked to requirements in [requirements.md](requirements.md).

## US1: Post an ad faster (Seller)

**As a** seller, **I want** the system to suggest my ad title, category and condition from my photos, **so that** I can publish my ad quickly.

**Linked requirements:** FR1, FR2, FR3, FR4, NFR1

**Acceptance criteria:**

1. When I upload 3 photos, a title, a category and a condition label appear within 3 seconds.
2. I can change any suggested value before I publish.
3. If I change a value, the ad is published with my value and not the suggested one.

## US2: Find items in good condition (Buyer)

**As a** buyer, **I want** to filter ads by condition label, **so that** I can avoid items in poor condition.

**Linked requirements:** FR9, FR3

**Acceptance criteria:**

1. When I choose "Like New", only ads with the Like New label are shown.
2. When I clear the filter, all ads are shown again.
3. Every ad in the results shows its condition label.

## US3: Get answers when the seller is offline (Seller)

**As a** seller, **I want** an AI agent to answer simple buyer questions when I am offline, **so that** I do not lose buyers while I am away.

**Linked requirements:** FR7, FR8, NFR3

**Acceptance criteria:**

1. If a buyer asks a question that is answered in my ad (for example price, size or condition), the agent replies with the correct detail from my ad.
2. Every agent reply shows an "AI Assistant" badge.
3. If the answer is not in my ad, the agent does not guess and the question is passed to me.
