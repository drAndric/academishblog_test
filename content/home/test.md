---
title: Feed
type: landing

sections:
  - block: markdown
    content:
      title: Feed de mastodon
      # subtitle: My subtitle
      text: acá sigue una feed de mastodon
    design:
      # See Page Builder docs for all section customization options.
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
---

<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@idotj/mastodon-embed-timeline@4.4.2/dist/mastodon-timeline.min.css" integrity="sha256-1UGgxsonaMCfOEnVOL89aMKSo3GEAmaRP0ISbsWa6lU=" crossorigin="anonymous">

<script src="https://cdn.jsdelivr.net/npm/@idotj/mastodon-embed-timeline@4.4.2/dist/mastodon-timeline.umd.js" integrity="sha256-E6WPG6iq+qQIzvu3HPJJxoAeRdum5siq13x4ITjyxu8=" crossorigin="anonymous"></script>

<div id="mt-container" class="mt-container">
  <div class="mt-body" role="feed">
    <div class="mt-loading-spinner"></div>
  </div>
</div>

<script>
      const myTimeline = new MastodonTimeline.Init({
        instanceUrl: "https://sigmoid.social",
        timelineType: "profile",
        userId: "112951258425774547",
        profileName: "@guia",
      });
    </script>