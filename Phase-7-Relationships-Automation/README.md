# Phase 7 – Relationships & Automation

## Relationships

A relationship was created between the **Player** and **Match Performance** objects.

### Master-Detail Relationship
- Match Performance is related to Player using a Master-Detail relationship.
- This connects match performance records with their corresponding player.

## Roll-Up Summary Fields

Roll-Up Summary fields were created in the Player object to calculate performance statistics.

The fields include:
- Matches Played
- Number of 50s
- Number of 100s
- Total 4s
- Total 6s
- Total Runs
- Total Overs
- Total Wickets
- Total Stumpings
- Total Catches

## Salesforce Flow

A **Screen Flow** was created for displaying player performance.

The flow:
1. Allows the user to select a team.
2. Retrieves Player records based on the selected team.
3. Displays player performance information.
4. Shows details such as profile picture, player name, total runs, AVG score, batting style, bowling style, matches played, and number of 50s/100s.

## Automation

The Screen Flow was added to the application Home page to provide automated access to player performance information.
