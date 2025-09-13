CrunchyStreamDB
📌 Project Overview

CrunchyStreamDB is an Anime Streaming Platform Database System designed to provide a secure and centralized way to manage anime content, users, reviews, and viewing history.

The system replicates the functionality of major streaming platforms by:

Managing anime titles, seasons, episodes, and studios.

Supporting multiple audio tracks and structured episode management.

Allowing users to write reviews, rate anime, and post comments on episodes.

Tracking watch history with timestamps and playback progress.

Supporting subscription-based access with role-based authentication (Admin/User).

Enabling efficient search, content discovery, and recommendations.

🎯 Key Features

User Management – profiles, subscriptions, authentication.

Anime & Seasons – structured handling of series and multi-season content.

Episodes & Audio Tracks – episode-level interaction with multilingual support.

Reviews & Comments – user-generated feedback and engagement.

Watch History – automatic tracking of viewing activity.

Admin Control – manage anime, studios, and episode details.

Scalability – supports millions of users and growing content.

🛠️ Entities & Relationships

User → Subscribes to Plans, Watches Episodes, Writes Reviews, Posts Comments.

Anime → Has Seasons, Belongs to Genre(s), Produced by Studio.

Season → Contains Episodes.

Episode → Has multiple Audio Tracks, Watch History, and Comments.

Review & WatchHistory → Link users to anime and episodes.

📈 Future Enhancements

Genre-based filtering and advanced search.

Recommendation system using collaborative filtering.

Live streaming events & simulcast support.

Payment gateway integration for premium tiers.

Analytics dashboards for user engagement.

⚡ Tech Stack

Database: Oracle SQL (with indexing, triggers, and constraints).

Design: ER Diagram & Relational Schema.

Backend/Integration: Scalable and extensible to integrate with streaming platforms.
