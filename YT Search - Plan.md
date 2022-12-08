# YT Search
## Current Situation
YT Search is relatively unhelpful:
- Includes Ads
- Includes recommended videos that are unrelated to the search
- Provides only just a few videos that are actually related to the search
- Difficult to find old videos
- Almost impossible to find videos by date
- Can't blacklist channels
- Can't blacklist keywords

## Goal
Research and explore YT's API in order to find ways to solve these issues and enhance the search experience

## Steps
1. ✔️ Read YT API Docs
2. ✔️ Run Basic Query
3. 🔨 Complete YTS - 1 API Exploration
4. Explore filters and parameters
5. List which issues can be solved and how
6. Start a backlog of ideas, features and future enhacements
7. Fix each issue
8. Mockup a Frontend for the tool
9. Design the architecture for the tool
10. Build it
11. Deploy it in GCP/AWS

## Open Questions
- When to use video.list() and search.list()?
    video.list() -> when videoId is known (one or multiple)
    search.list() -> when you have a query string (like the one you use on the search bar)

***

# Experiments
- YTS 1 - API Exploration: Basic Search Functionality