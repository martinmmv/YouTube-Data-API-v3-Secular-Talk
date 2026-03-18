# YouTube Data API v3 — Secular Talk

Analysis of Kyle Kulinski’s YouTube channel using the YouTube Data API v3.

## Project Goal
This project collects and analyzes video-level data from the Secular Talk channel to study:
- upload volume over time
- publishing patterns
- total content output
- engagement metrics
- view/like/comment rates

## Data Source
- YouTube Data API v3
- Channel analyzed: Secular Talk
- Channel ID: UCldfgbzNILYZA4dmDt4Cd6A

## Project Structure
data/
notebooks/
README.md

## Workflow
1. Pull raw video metadata from the API
2. Clean and transform the dataset
3. Analyze upload counts
4. Analyze publish times
5. Measure total content duration
6. Compare views and likes
7. Build scatter plots
8. Calculate engagement rates

## How to Run
1. Create a YouTube Data API key
2. Store it as an environment variable
3. Install dependencies
4. Run notebooks in order

## Future Improvements
- automate extraction with a Python script
- add sentiment/topic analysis
- compare multiple political channels
