# Malawi Football Analytics Platform

A lightweight football analytics app focused on insight, not just information. Designed for leagues with minimal available data.

## Player Analytics

### Player Impact Score
Composite score using goals, assists, and minutes played to rank player influence.

### Goal Contribution %
Shows each player's share of total team goals (goals + assists).

### Scoring Consistency Tracker
Tracks how often a player scores per appearance (e.g., "scored in 4 of last 5").

### Minutes per Goal/Assist
Performance per 90 minutes based on lineup and substitution data.

### Form Timeline
Graph of goals/assists over recent matches to highlight streaks.

## Team Analytics

### Goal Timing Heatmap
Identifies when teams score or concede most frequently during a match.

### Form Momentum Graph
Plots recent match results to show improvement or decline.

### Goal Dependency Index
Shows how much a team relies on a single player for goals.

### Home vs Away Efficiency
Tracks performance variance between home and away matches.

### Impact Substitutions Tracker
Highlights subs who contribute goals or assists — "super sub" detection.

## Trends & Predictive Insights

### Win Probability Factors
E.g., "Team X has not lost when scoring first", "Team Y concedes most after 75th min".

### Efficiency Rankings
Leaderboards based on:
- Goals per shot (if available)
- Points per goal
- Goals per appearance

### Top Assist Combinations
Tracks frequent scorer–assister pairings.

### False Form Detector
Teams winning but with poor goal margins or luck indicators.

## Data Features (to power analytics)

- Match results, scorers, and goal times
- Lineups and substitutions  
- Assists (when available)
- Yellow/red cards (when available)
- Player participation and starting/sub stats
