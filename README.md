# Reddit News Reader

A planned, read-only personal application for discovering and organizing recent public Reddit discussions in one place.

## Overview

Reddit News Reader is a personal developer project intended to make it easier to keep up with technology news, AI developments, software engineering, and other topics discussed on Reddit.

The goal is to build a lightweight dashboard that retrieves permitted public post data through Reddit's official Data API and organizes it into a convenient, chronological feed.

**Project status:** Planning and API access request stage. The application is not yet implemented.

## Planned Features

- **Recent posts:** Retrieve recent public posts from a selected list of subreddits, subject to API permissions.
- **Topic filtering:** Filter posts by keywords, subreddit, and recency.
- **Unified feed:** Organize relevant discussions in one personal dashboard.
- **Original links:** Open posts on Reddit to read the complete discussions.
- **Read-only access:** No automated posting, commenting, voting, messaging, or moderation.
- **Responsible API usage:** Use authorized OAuth access, an identifiable User-Agent, reasonable request rates, and caching where appropriate.

## Intended Use

This project is intended for personal, non-commercial use by its developer.

The initial use case is monitoring public discussions about:

- Technology news
- Artificial intelligence and machine learning
- Software development and programming
- Open-source projects and developer tools

Initial target communities may include `r/technology`, `r/programming`, `r/artificial`, `r/MachineLearning`, and `r/LocalLLaMA`, subject to API access and applicable rules.

## Data Handling and Privacy

The planned application will:

- Request only the API access necessary for its intended functionality.
- Prefer public post metadata and links relevant to the user's selected topics.
- Avoid collecting unnecessary personal information.
- Respect Reddit's API terms, rate limits, content restrictions, and applicable deletion requirements.
- Avoid selling or redistributing Reddit data.
- Not use Reddit content to train AI models.

Any implementation will be developed in accordance with the permissions Reddit grants and the policies applicable at the time of development.

## Technology

The implementation technology has not yet been finalized. The project is intended to use Reddit's official Data API, subject to approval.

## Roadmap

- [ ] Review Reddit's Responsible Builder Policy and API terms.
- [ ] Request the appropriate Reddit Data API access.
- [ ] Implement authorized authentication and read-only post retrieval.
- [ ] Build a minimal personal news feed.
- [ ] Add topic filters and links to original discussions.
- [ ] Test rate limiting and responsible data handling.

## Disclaimer

This is an independent personal project and is not affiliated with or endorsed by Reddit, Inc.

Access to Reddit's Data API has not yet been approved. Planned features are subject to Reddit's approval, API availability, and applicable policies.

## License

No license has been selected yet. All rights remain with their respective owners unless otherwise stated.
