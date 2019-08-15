# Find out how many times your files have been downloaded

## Overview

You can use Google Analytics to find out how many times your files have been downloaded on Mass.gov pages. If you don’t have access to Google Analytics, MA Digital Service is happy to grant you access. [Here’s how to associate your state email with a Google Account](). You’ll need to do this before we can give you a Google Analytics login.

## Getting Started

Once you’ve logged in to [Google Analytics](analytics.google.com), make sure you’re viewing the correct property. It should say “Mass.gov \(Drupal\), All Public Traffic” in the upper left:

![](https://lh5.googleusercontent.com/qtytfjNd-313JCqO7FNsfI_DKHbEOZHlyyOQ2Ekf4rgLEl_0iQ8XKtDS8QZ2Wt_-nGVT8pkgieuIl_dAobgXS9t3Wt73MVHM7SbUMsj6fQCQN0oezF_uM0gJYzipTmcSL7iR-3ZH)

If it doesn’t, click the drop-down arrow and select the correct property \(Mass.gov \(Drupal\)\) and view \(All Public Traffic\).

## Ways to learn about file downloads

In this article, we’ll show you how to:

* Search for a page to see how many times any file on that page has been downloaded
* Search for a specific file to see how many times it has been downloaded across all content

You can also search for downloads by organization. If this is something you’re interested in learning about, please submit a ServiceNow request, and we’ll walk you through the process.

_Note_: We can’t know how many times someone downloaded your files directly from Google, since Google does not share that information. We can find out how often they’re downloaded from search.mass.gov. To learn about this, please [submit a ServiceNow support request](https://massgov.service-now.com/sp?id=sc_cat_item&sys_id=0bb8e784dbec0700f132fb37bf9619fe).

We’ll be using the events report to learn what we want to know. In Google Analytics \(and in web analytics in general\), an “event” is any interaction \(that you track\) between your web pages and site visitors. Link clicks, downloads, and scrolling are all examples of events.

## Find a page to learn how many times any file on that page has been downloaded

### Step 1: Open the “pages” report in the toolbar on the left

Behavior ➜ Events ➜ Pages

![](https://lh3.googleusercontent.com/iB5fYohZqHhp_IgZ-rPg08tFObga6hsRGHmzRGFfW-wZha0d5kQvIV4pE3Ssric4eTByT6MZA1bYzBUyCaWNYkPiO9TAHeXqbwXdOAjpZWF6kd8JVvyuD3pfUSXzFLEkdpTczDsr)

The report you’ve opened shows how many events have happened on each page on Mass.gov. To find the page and the download you’re looking for, we’ll need to filter out all the results we don’t want.

### Step 2: Find the page you’re looking for

To do this, enter the URL of the page in the little search bar on the right. Make sure you don’t include the `https://www.mass.gov` – just everything after it. For example, enter`/how-to/order-a-birth-marriage-or-death-certificate`, and not `https://www.mass.gov/how-to/order-a-birth-marriage-or-death-certificate`.

Click the magnifying glass to search for your page.

![](https://lh3.googleusercontent.com/8KXDkx9MrB89IPftkHJCdUmMh4Sfxo1K91yzr6YgA5p70oD2SVuKilVwv2VZ9X7N42exGt36vDM0HfTVDROAaWAscX1jSCpY8aPx1urgl4tsF5ikxxdA_LTj6XgOdo3p9d6PPEow)

### Step 3: Drill down to see your page’s events

You’re now seeing all the events that have happened for your page in the past week. \(There’s a time filter in the upper right. You can change this at any point.\) However, we track lots of events. You want to know specifically about a download \(or several downloads\). To see these, click the page’s title in the table:

### Step 4: Click “Event label”

You’re now seeing the different categories of events that MA Digital Service tracks that have happened on this page. Click “Event label:”

![](https://lh5.googleusercontent.com/KAwsRcsmBlmUhCkLDtaX7QGEBPRCvb1kanNKSZLZQnYeggMqAduxxyoE1I4rl-uEol2qq370JqsmZjUfliBG2Zspke8mhFfFo652GwzgsZfqHX7jJCvcxJLWrdIlQ9YmhzvBtU-I)

### Conclusion

We’ve landed on a list of the URLs clicked on this page. If your files have been downloaded, you’ll find them listed under the “Event labels” column. If you have lots of links and files, you might need to use the bottom right drop-down menu to expand the table.

The “Total events” column tells you how many times each file was downloaded, and the “Unique events” column tells you the number of sessions in which a file was downloaded. [Learn more about the difference between “total” and “unique” in GA](https://support.google.com/analytics/answer/1257084?hl=en#pageviews_vs_unique_views).

![](https://lh4.googleusercontent.com/X4pS7BvXN2a2_cnuzAqaBBv-mNAd7M5WgBPi12reuVjVoPclUwgges9_wEKj_KpAvrHwrk5k_z8_uLwmyRJNQLPu07a8LqdCep_AX-dKJsRLU5i5DNdTnIguPTnM0ZkPIEzLBV4R)

## Find out how many times a specific file has been downloaded across all your Mass.gov content

### Step 1: Get the file’s URL

Find the file you want to learn about. Once you’ve found it, right-click it and select “copy link address.”

### Step 2: Open the events report

Behavior ➜ Events

![](https://lh6.googleusercontent.com/wvBQATvsh2N5NsaCn1Qgom1YsPFoNOz-tVFpoRlHGmFF_klLw4aW69T8nozGwR1UOqjyXWY1m3Z6-xrOqTG9K5bI2p2zPMfI8jJ2hD1dVGeyun0oIyTXPvgjOagAHvPpTSyLsIjR)

### Step 3: Click “View full report” in the bottom right

![](https://lh3.googleusercontent.com/ieggqsErp9IFbgsCqijjKRAv4zUjn976oPbgyMPIT7QGcUuc4BYfZiAFuFEGq6zFY-nU2inxWP8XtBNz1V2QYnENMeRiWQs-7sLn6QiBYnO8yWKyS7hKg12j2CuCmExMDQr-LSMS)

### Step 4: Click “event label” \(above the table\)

![](https://lh3.googleusercontent.com/DXYUvVQP4igacr6KzxPfG2S4xQcW5jT_iKXWD2hUsQet2GJqKqxdLKeitn11-FmX95lnvw-X0hmxwA4u4hRRVjVfsk-sgFwvQhoAXbrm_QWgScBfRoHcKaMzTC_4N5LSvMF0h4Ro)

### Step 5: Paste the file URL that you copied in step 1 into the search bar on the right.

Remember to remove the `https://www.mass.gov` from the front of the URL before clicking the magnifying glass.

![](https://lh5.googleusercontent.com/McUQ89Z1J6a9mi4qyjvmxoWmEg7fIe63Fj9xrh0Vjr29YQxci6fuPCIXQf9VTLpHx0snsr1veroJNUgwj4v0m4srs2Lqfx6z1J2Qaq_KYG8F3Ew8rKmjfRiv8ReICJQCkUQEAQuG)

### Conclusion

If your file has been downloaded, its URL will appear in the “Event label” column. “Total events” tells you how many times it has been downloaded on every Mass.gov page, and “Unique events” tells you the number of sessions in which it was downloaded. [Learn more about the difference between “total” and “unique” in GA](https://support.google.com/analytics/answer/1257084?hl=en#pageviews_vs_unique_views).

You can also change the date using the date filter in the upper right. This won’t affect your report’s filters.

## Was this article helpful?

[![Tell us what you think button](https://blobscdn.gitbook.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-LJ04qJGAHkvdE13BfdG%2F-LSz77NBAwnSNpMPT3df%2F-LSz7xSmyKXltd4avaCt%2FKB%20survey%20button%20POC%202.png?alt=media&token=8d071cab-8b95-48a3-a332-13e3fc8d9f96)](https://massgov.formstack.com/forms/mass_gov_knowledge_base_feedback?article=find-out-how-many-times-your-files-have-been-downloaded)

