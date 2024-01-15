---
layout: post
title:  "Decentralized vs. Centralized: Twitter and Mastodon System Design"
date:   2022-10-23 12:23:45 +0530
categories: jekyll update
---

# Decentralized vs. Centralized: A Dive into System Design

Social media platforms play a pivotal role in connecting people worldwide. However, the way these platforms are designed can significantly impact user experiences and the overall online community dynamics. In this post, we'll explore the system design of two prominent platforms: Twitter, representing a centralized model, and Mastodon, exemplifying decentralization.

## Twitter: A Centralized Social Hub

### Data Points in the Twitter Ecosystem

1. **User Profiles:**
   - Usernames, display names, bio information, and profile pictures.

2. **Tweets:**
   - Text-based messages, multimedia attachments, timestamps.

3. **Interactions:**
   - Likes (favorites), retweets, replies, mentions.

4. **Followers and Following:**
   - Lists of followers and accounts being followed.

5. **Media Storage:**
   - Storage of images, videos, and other media attachments.

6. **Notifications:**
   - Notifications for likes, retweets, mentions.

7. **User Preferences:**
   - Settings and preferences, including notification preferences.

8. **Analytics and Metrics:**
   - Engagement metrics, user activity data.

### Centralization at its Core

- **Unified Database:**
  - All data points are stored in a centralized database controlled by Twitter.
- **Unified Moderation:**
  - Twitter enforces a consistent set of moderation policies across the entire platform.
- **Single Point of Control:**
  - Twitter has complete control over user data, content policies, and platform rules.

### ![Twitter System Design Flowchart](/assets/twitter_system_design_flowchart.png)

## Mastodon: Embracing Decentralization

### Data Points in the Mastodon Universe

1. **User Profiles:**
   - Usernames, display names, bio information, and profile pictures.

2. **Toots (Posts):**
   - Text-based messages, multimedia attachments, timestamps.

3. **Interactions:**
   - Boosts (similar to retweets), likes, replies, mentions.

4. **Followers and Following:**
   - Lists of followers and accounts being followed.

5. **Media Storage:**
   - Storage of images, videos, and other media attachments.

6. **Notifications:**
   - Notifications for boosts, likes, mentions.

7. **User Preferences:**
   - Settings and preferences, including notification preferences.

8. **Analytics and Metrics:**
   - Engagement metrics, user activity data.

### The Essence of Decentralization

- **Federated Architecture:**
  - Mastodon operates on a federated model, with multiple instances (servers) communicating with each other.
- **Instance Independence:**
  - Each Mastodon instance is independently operated, with its community and moderation policies.
- **User Data Control:**
  - Users have more control over their data, choosing instances that align with their preferences.

### ![Mastodon System Design Flowchart](/assets/mastodon_system_design_flowchart.png)

## Decentralization Explained

- **Federated Communication:**
  - Instead of a single database, Mastodon instances communicate with each other, allowing users from different instances to interact.
- **Community Independence:**
  - Each instance is like a separate community with its own rules, policies, and moderation, fostering diverse and customized user experiences.
- **User Empowerment:**
  - Users have a say in the rules of their chosen instance, emphasizing user empowerment and control over their online experience.

In conclusion, the architecture of a social media platform significantly influences the user experience. Whether centralized or decentralized, each model comes with its own set of advantages and trade-offs. Users must consider factors such as data control, moderation policies, and community dynamics when choosing their online social hubs.

