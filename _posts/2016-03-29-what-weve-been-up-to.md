---
layout:     post
title:      What we've been up to lately...
date:       2016-03-29 14:31:19
summary:    See what we've been up to lately here at Nudge over past few months.
categories:
tags:       nudge release updates
---

Wow it's nuts it's already the end of march, it really doesn't feel like it's been that long. What feels even more nuts though is the amount of work we have released for Nudge in just 3 months!

### MongoDB <br>
  We have rebuilt our DB structure from the ground up, migrating from PostgreSQL to MongoDB. We will be rolling this out to all our clients over the next few weeks. The biggest improvement is how much faster we can deliver the data to the dashboard, decreasing loading times dramatically! We are really excited about this one and think you will love it too!

### RSS Whitelisting<br>
  You can now add a RSS feed when whitelisting content instead of a single url. Nudge will then automatically add any new content in the feed into the whitelist.

### UTM tags support<br>
  We now support the use of all utm tags / parameters! This means if you are already using these to track traffic sources you will see these sources displayed in the Traffic Source tables.

### Conversion page upgrades <br>
  This is just the start of a series of upgrades we have coming for conversions, but to get the ball rolling we are going to continue to release these as we go.
  - Upgraded overview conversions page allowing you to quickly see which conversion is performing the best.
  - Clicking the setting cog will take you to the campaign edit screen where you can view / add / remove conversion pixels.

## Other
  - Removed the last step in the campaign creation. This was confusing and was a legacy step no longer needed.
  - We have overhaulded the way we handle timezones and moved this all the backend. This has fixed the annoying issue where Insights days / dates would be out for some users.
  - Fix a bug that was causing some url titles to not render correctly and showing up with "No Title"
  - Better category support when creating a new campaign.
  - Users who had a lot of traffic sources listed will notice we now have an accordian to display the rest. With only the top performing shown at the top.
  - Many many upgrades to our URL normalization. This has fixed almost all cases of the pesky url merging many of you have had to deal with. 
