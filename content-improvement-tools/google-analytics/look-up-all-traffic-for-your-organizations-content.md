# Look up all traffic for your organization's content

## **Overview**

You can use Google Analytics to get a report that shows how much traffic all your organization’s content gets. While you can also [see all your content’s pageviews in the CMS](https://massgovdigital.gitbook.io/knowledge-base/tools-for-improving-your-content/get-a-snapshot-of-your-contents-performance#summary), Google Analytics offers more detail and allows you to filter by date.

### **You’ll need:**

* [A Google Analytics account](https://massgovdigital.gitbook.io/knowledge-base/~/edit/drafts/-LWN-JxyBzf87Uh4P2Cn/tools-for-improving-your-content/google-analytics/associate-your-state-email-with-a-google-account)
* To know how Google Analytics formats your organization’s name. If you’re not sure, we’ll help you find this in this guide.

## **Getting started**

Log in to [Google Analytics](www.analytics.google.com). Check in the upper left to make sure that you’re in the Mass.gov \(Drupal\) property and the “All Public Traffic” view. If you’re not, you can click the drop-down arrow to switch.  


![](https://lh5.googleusercontent.com/NDfbaLirDsNuWq3_zVIRwzinfX_Qm-sQNfEPXozGUibui9h_tex4vVvtJGFA2TWS93Vb_7vliacXTTlAFFhZxymFNcxWu7vXMiaI-J9xwuVUwe9colX1yHucfqe7KelbLWMEVLrg)

### **Step 1: Create a custom report**

Navigate to custom reports: Customization -&gt; Custom Reports. Then click the `+ New Custom Report` button.  
****

![](https://lh4.googleusercontent.com/h8BALLFDGHG7p7Zi8SrwSJ5l-JKBeQ4bE1xn-360rwV6y4_kvlIuYPUC-nR6WjRR5zBM6t6sAfrU5cdk9ob1L11uSOKdjRBGi504rLWh_LUO28H10ZNLI2p1bpjwzjFkk4ovBHe-)

### **Step 2: Set up the custom report**

* Give your custom report a title
* Set the type to “Flat Table”

![](https://lh4.googleusercontent.com/5IyZlJCRIxWSMOPm_Y1AMrY3H3oyIRaJ2nnObdtwehSLZCE04LyxWo25kieo9sQsufwwQZHqtiHMBJV7jqsdYSC4Ciwef1JaXhEC8Hfz3ybZr6A7yXs2AiQgfPR4PVGUzkHM2MAE)

### **Step 3: Add your dimensions**

We want to add 2 dimensions to this report: Page and Organization. To do this, click the `+ add dimension` button and begin typing. When the dimension you’re looking for appears, click it \(or scroll to it and click it\).

![](https://lh3.googleusercontent.com/to7vKdsPXPUYDreia9WCHAr0rp_nfQrFDdxHkb3Nq8WE8JG1qHQTGtYGaz3sy2DIqhoTVEYY_KO076VtaexKuDlOwpiS05QmXDTqcEUZ1lEMt31CupI9GCx-TtvCUu9DmkZbRdRX)

### **Step 4: Add your metrics**

Since you want to learn about your organization’s traffic, you should add pageviews and/or unique pageviews as metrics. To do this, click the `+ add metric` button and begin typing. You’ll have to scroll to find them; they don’t appear right at the top.

Pageviews is the total number of times a page is loaded. Unique pageview is the number of sessions a page appeared in. [Learn more about the difference.](https://support.google.com/analytics/answer/1257084?hl=en#pageviews_vs_unique_views)

![](https://lh5.googleusercontent.com/TBEuZxWMs9ydPuldlOjklIklJE7BgAprjq1YGYb6BDMMWEt2fH3Tr_2Nzbbp28KCq43aZs6KuEUiAVIlsw3tPcYCCSHBzy-LOrnNwHVJgFV4hcg9nHHDfNNEHod7JUGBKzSqT_2t)

### **Step 5: Set up the filter**

Click the `+ add filter` button and add an Organization filter:

![](https://lh4.googleusercontent.com/2Gj9zrDGG5qPhOqZ-ha_AnS8PFGr3X0tTc8KVhw48Hp6WN_dSmvRKiSQ7FZdb1qHmGCcMGrE26ZiIXhN8cbH7cq83EVdNdzH1Ke83srAvEoA8MkdyAzXk6EQJ2SLetj9E-eHVWuz)

Make sure you change `Exact` to `Regex` \(as in the image\).  

{% hint style="info" %}
Note: You can save your report right now. That way, if you have to come back later, you can simply re-open it from the Custom Reports menu.
{% endhint %}

### Step 6: If you know how your organization is listed in Google Analytics: Create the regular expression string \(regex\)

Next, we want to filter out all traffic that’s not your organization’s. This is the tricky part, though. In January 2019, the Mass.gov team changed the way organization names were formatted in the site’s metadata. The reason this matters for you is that we need to create a filter that includes both formats.

If you already know what your organization’s name was before the January update, you can figure out the rest without doing any detective work. All you have to do is remove the hyphens. Or, if you know the un-hyphenated version, add them.

#### Examples:

division-of-fisheries-and-wildlife ➜ divisionoffisheriesandwildlife

department-of-unemployment-assistance ➜ departmentofunemploymentassistance

If you don’t know your organization’s name in Google Analytics, move to step 7.

#### Regular expression syntax

To create the filter that Google Analytics will use to look up your organization’s traffic, connect the 2 organization name formats with a vertical pipe: \| . 

#### Examples:

division-of-fisheries-and-wildlife\|divisionoffisheriesandwildlife

department-of-unemployment-assistance\|departmentofunemploymentassistance

Paste the entire regex string into the empty box to the right of `Regex`

![](https://lh3.googleusercontent.com/d0u4ICIUD14V9Gg7bqdG_Evn0fcPh0FmdQ9nBVwJSGFeP3qfFpYUOZ95QWz-hVV8Cowvzzd7kmYFDIlfS6BqnkLswMxREpX8kBrDfJLP9IjnPtlTSUmRqTy2RBhfHzzYIUhw4-vl)

Once you’ve set up your filter, click save. Move on to Step 8 to learn more about using the report.

### Step 7:  If you don’t know how your organization is listed in Google Analytics: Check the metadata

To find out what your organization is called in Google Analytics, open any one of your pages in a new browser tab. Right click anywhere on the page and select “view page source” or “view source.” \(The exact wording depends on which browser you are using\).

This will open the HTML code that generated your page. It might look overwhelming at first, but we just need whatever is listed in the line beginning with &lt;meta name="mg\_organization"&gt;. To find this line, use control + F \(on a PC\) or command + F  \(on a Mac\) and search for &lt;meta name="mg\_organization."

![](https://lh3.googleusercontent.com/lfKMU6wNabCQc7gbIvsbA87MO2h89GqlE0wRu8WHhYiKl9urFuX1ekNkNM0I1XE8JujfZYADe7FTmHZVHTyJWEurSzDnOW32EgANgaHBMcztctjYXH8OtPQw3AcbakcqsBbXdSfo)

You’ll find your organization listed in this line after content=”. 

{% hint style="info" %}
**Important:** You might find more than 1 organization, e.g.: digitalservices,executiveofficeoftechnologyservicesandsecurity. You only need yours – not your parent’s.
{% endhint %}

Once you have this, return to step 6.

### Step 8: Using your custom report

Once you’ve saved the report, it will always be available under the Custom Reports menu. You can change the date range using the selector in the upper right.

![](https://lh4.googleusercontent.com/RDHCZLWPbLgsdlWVXoPrnNubjbUS0s7VJuajtNZDbErsiuCCr5Knf-ENrDh1gdAAeA9cc-k0NG_3OBtSBK9i8mBjJwZ-OHb08e0-BfjVVuQ4wxTJeaVM8C173XTbisiHry1EFSns)

You can also export the data using the button above the date picker.

## Was this article helpful?

[![Tell us what you think button](https://blobscdn.gitbook.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-LJ04qJGAHkvdE13BfdG%2F-LSz77NBAwnSNpMPT3df%2F-LSz7xSmyKXltd4avaCt%2FKB%20survey%20button%20POC%202.png?alt=media&token=8d071cab-8b95-48a3-a332-13e3fc8d9f96)](https://massgov.formstack.com/forms/mass_gov_knowledge_base_feedback?article=look-up-traffic-for-your-organizations-content)

