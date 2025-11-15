# Controversial Game Updates vs. Player Engagement and Sentiment

### How do controversial updates or announcements affect player engagement and sentiment in popular online games?

I think this question has some good direction going for it. It's no surprise that players respond to game updates according to whether they like them or not, and this is no different. What I want to explore deeper is how drastically playercount and reviews affected, and if there are any long term affects on a game's community.

A lot of data may end up being sourced from scraping instead of official APIs, but I'm willing to work with it for the sake of discovery!

---

## Research Question & Hypothesis

### Core Research Question:
**How do controversial updates or announcements affect player engagement and sentiment in popular online games?**

### Competing Hypotheses:
1. **The Short-Term Outrage Hypothesis:** Controversial updates cause immediate player count drops and negative sentiment spikes, but communities recover within weeks as players adapt or accept changes
2. **The Long-Term Erosion Hypothesis:** Major controversial updates cause sustained damage to player retention and community sentiment that persists for months or permanently alters the game's trajectory
3. **The Vocal Minority Hypothesis:** Online outrage is amplified by a small subset of vocal players, while actual player engagement metrics remain relatively stable
4. **The Cumulative Impact Hypothesis:** Individual controversial updates may have minimal impact, but multiple controversies compound to create significant long-term player base decline

---

## Methodology Overview

### Case Studies:
1. **Overwatch 2: PvE Mode Cancellation (May 2023)**
   - Blizzard's cancellation of promised PvE content
   - Community backlash and "review bombing"
   - Data sources: Reddit sentiment, Twitch viewership, unofficial player trackers

2. **RuneScape: Evolution of Combat (2012) & Other Controversies**
   - Fundamental combat system overhaul
   - "Old School RuneScape" split as direct response
   - Subscription-based model amplifies financial impact
   - Additional controversial updates: Wilderness removal, microtransactions, etc.

### Data Collection Strategy:
1. **Player Engagement Metrics:**
   - Steam player counts (where available)
   - Third-party player trackers

2. **Sentiment Analysis:**
   - Steam review scores and timeline

3. **Timeline Analysis:**
   - Mark exact dates of controversial announcements/updates
   - Track metrics weekly for 3 months before and after
   - Identify immediate impact vs. sustained trends

### Analytical Approach:
- **Time Series Analysis:** Track engagement metrics before, during, and after controversies
- **Sentiment Analysis:** NLP on Reddit/Twitter to quantify community mood
- **Comparative Analysis:** Compare magnitude of different controversies
- **Longitudinal Study:** Assess whether games recover or experience permanent damage
- **Control Comparisons:** Compare controversial updates to non-controversial updates

---

## Expected Challenges & Limitations

1. **Data Availability:** 
   - Many games lack public player count APIs
   - Historical data may be incomplete or unavailable
   - Some platforms (console) don't share engagement metrics

2. **Attribution Complexity:**
   - Multiple factors affect player counts (seasonal trends, competing games, holidays)
   - Difficult to isolate update impact from other variables
   - Confounding events (other controversies, content droughts, marketing)

3. **Sample Bias:**
   - Online sentiment may not represent silent majority
   - Reddit/Twitter users may be more vocal than average players
   - Self-selection bias in review bombing

4. **Temporal Factors:**
   - Natural player attrition over time
   - Game lifecycle stages (launch, mid-life, decline)
   - Seasonal variations in engagement

5. **Platform Fragmentation:**
   - Multi-platform games require aggregated data
   - Different platforms may show different trends

---

## Potential Implications

### If we find evidence of significant impact:
- **Game Development:** Importance of community communication and transparency
- **Update Strategy:** Risk assessment for controversial changes
- **Community Management:** Early warning signs and damage control strategies
- **Business Models:** Financial implications of player churn from controversies

### If we find minimal long-term impact:
- **Vocal Minority Effect:** Online outrage may not translate to actual player behavior
- **Player Retention:** Established player bases may be more resilient than assumed
- **Risk Tolerance:** Developers may have more freedom to make bold changes

### Cross-Game Patterns:
- Do certain types of updates consistently cause more damage? (monetization, gameplay, content removal)
- Do subscription-based games suffer more than free-to-play?
- Does genre matter? (MMO vs. competitive shooter vs. battle royale)
- Can games recover from controversies, and if so, how?

---

## Analysis Framework

### Metrics to Track:
1. **Engagement Metrics:**
   - Daily/weekly active players
   - Peak concurrent players
   - Session duration (if available)
   - Twitch viewership hours

2. **Sentiment Metrics:**
   - Review score changes
   - Reddit sentiment polarity
   - Positive vs. negative keyword frequency
   - Subreddit growth/decline

3. **Community Health:**
   - Post frequency
   - Comment engagement
   - Content creator activity
   - New player onboarding rates

### Statistical Tests:
- Time series analysis with breakpoint detection
- Pre-post comparison t-tests
- Correlation between sentiment and player counts
- Regression analysis controlling for confounding variables