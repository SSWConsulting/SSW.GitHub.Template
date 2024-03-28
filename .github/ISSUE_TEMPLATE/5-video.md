---
name: "🎥 Video"
about: "Upload weekly Sprint Review & Planning videos to YouTube channel"
title: "🎥 Upload Sprint {{ SPRINT_NUM }} video to YouTube channel"
labels: "Type: Video"
assignees: ""

---

Cc: {{ PRODUCT_OWNER }}

Video Title
```
Sprint {{ SPRINT_NUM }} - {{ PROJECT }} - Review & Planning Meeting {{ YYYY-MM-DD }}
```

Video Description:
```
Join us for Sprint {{ SPRINT_NUM }} - {{ PROJECT }} - Review & Planning Meeting

{{ TIMESTAMP_SUMMARY_FROM_AI }}

🔗  Links:
{{ PUBLIC_LINKS }}
<!-- product page or social media page, if applicable -->

```

Video Thumbnail Template:
{{ PATH_TO_POWERPOINT_FILE }}
<!--
Thumbnail Generation - take a screenshot in PowerPoint fullscreen mode (1920x1080)
 -->

### Acceptance Criteria
1. Public can see this week's video on YouTube channel

### Tasks
- [ ] Upload this week's Sprint video with Title and Description to YouTube channel
- [ ] Generate thumbnail from the template and add it to the video
- [ ] Add the video to the Playlist

### Information
- YouTube Channel {{ YOUTUBE_CHANNEL_LINK }}
- Playlist {{ PLAYLIST_LINK }}

