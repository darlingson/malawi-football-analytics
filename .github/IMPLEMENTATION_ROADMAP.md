# Implementation Tasks – Malawi Football Analytics

## 1. Data Models
Define the database structure to power everything else.

- [ ] Create Team model
- [ ] Create Player model
- [ ] Create Match model (date, teams, score, etc.)
- [ ] Create Goal model (match, scorer, minute, assist if available)
- [ ] Create Card model (yellow/red, player, match, minute)
- [ ] Create Substitution model (player in/out, minute, match)
- [ ] Create Lineup model (player, match, team, starting/sub)
- [ ] Add Appearance model or logic (derived or stored)

## 2. Data Input & Admin Setup
Enable easy input of match data for analysis.

- [ ] Configure Django admin for all models
- [ ] Create match form (goals, scorers, cards, etc.)
- [ ] Add inline admin for goals, cards, subs per match
- [ ] Build initial CSV importer (optional for bulk load)

##  3. Core Analytics Engine
Implement the logic for analysis and stats generation.

### Player Analytics
- [ ] Calculate Player Impact Score (goals, assists, minutes)
- [ ] Track Goal Contribution % per player
- [ ] Count Scoring Consistency (e.g., games with goals / appearances)
- [ ] Approximate Minutes Played using lineups & subs
- [ ] Generate Form Timeline (last N matches, goals/assists)

### Team Analytics
- [ ] Group goals by time blocks for Goal Timing Heatmap
- [ ] Track last 5 match results for Form Momentum
- [ ] Calculate Goal Dependency Index (team reliance on top scorer)
- [ ] Split performance into Home vs Away categories
- [ ] Count Sub Goals/Assists for Super Sub Tracker

### Trends & Insights
- [ ] Detect Win Probability Factors (e.g., scoring first)
- [ ] Build Efficiency Rankings (goals/appearance, goals/shot if available)
- [ ] Track Top Assist Combos between players
- [ ] Flag teams with poor xG vs result outcomes (basic False Form logic)

## 4. Visual Output / UI
Expose the analytics in your frontend (template or API).

### Player Pages
- [ ] Create player detail view with goals, assists, and impact score
- [ ] Add form graph (goals over last N matches)
- [ ] Show goal contribution % and minutes per goal

### Team Pages
- [ ] Show recent results and form
- [ ] Display goal timing heatmap (bar or pie chart)
- [ ] Include super sub highlights
- [ ] Compare home vs away performance

### Leaderboards / Trends
- [ ] Top impact players leaderboard
- [ ] Top assist combinations
- [ ] Team efficiency rankings (goal/point ratios)
- [ ] Most goal-contributing subs

## Enhancements
- [ ] Create basic API endpoints for data-driven frontend
- [ ] Export analytics to CSV or JSON
- [ ] Add caching or pre-computation for heavy stats

## Docs
- [ ] Add README instructions for local setup
- [x] Push initial version to GitHub
- [x] Add license (Apache 2.0)
- [ ] Write basic user guide or walkthrough in Markdown
