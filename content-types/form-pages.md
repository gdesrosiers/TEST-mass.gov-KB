---
description: Use along with Formstack to gather data and feedback from users.
---

# Form Pages

### **Summary**

This resource will help you use the Form Page content type to gather data and feedback from users. To create Form Pages on Mass.gov, you or someone you work with will need access to and familiarity with Formstack, a tool for creating online forms.

You can link to Form Pages:

* in the **Featured tasks** section of a Service Page
* on Curated Lists
* in **Related Links** sections throughout the site

**Note:** If you are working with an older Formstack form, you might need to change its theme to Mayflower. To do this, open it in Formstack, and click the “Build” tab. Select “theme” from the bottom left menu, and make sure “Mayflower” is selected:

![](https://cdn-images-1.medium.com/max/800/1*P6nd64f12_oAB6jpVvO2mQ.jpeg)

### Form Pages with file uploads vs. Form Pages without file uploads

Currently, you need to follow different steps for Form Pages that allow users to upload a file than for Form Pages that only ask users to answers questions.

**Important:** It doesn’t matter if the file upload is required or optional. If your Formstack form includes a file upload, but you don’t follow the “Create a Form Page _with_ a file upload” steps, you won’t receive any of the files users upload. Additionally, users won’t get an indication that they’ve submitted the form. The user experience will be that they’ve clicked “submit,” but nothing has happened.

#### Create a Form Page _with_ a file upload

This resource assumes that you’ve already built your form in Formstack. \(If it is an older form, make sure you change the theme to Mayflower.\)

#### **Step 1: Create a “submission received” page**

The first thing you’ll need to do is create the page that tells users they’ve successfully submitted a form. We suggest you use a Service Detail for this. You can also use this Service Detail to link to other, related pages of interest to survey respondents.

![](https://cdn-images-1.medium.com/max/800/1*kxO5uiEVsYImeZyetS9u-g.jpeg)

#### **Step 2: Link to this page in Formstack**

Open your form in Formstack. Under the “Settings” tab, open the “Email & Actions” menu on the right side. Click the “Add a submission message” button.

![](https://cdn-images-1.medium.com/max/1000/1*G8UiDT39gtyL4fzPgT1_CA.jpeg)

Select the bottom option: “Redirect to a custom URL.” Paste the URL of your “submission received page.”

![](https://cdn-images-1.medium.com/max/1000/1*KGWnWUTVriI7m8c_omoKjA.jpeg)

**Important:** Don’t forget to change “edit.mass.gov/” to “[www.mass.gov/](http://www.mass.gov/)” after you paste.

![](https://cdn-images-1.medium.com/max/1000/1*x0_ulNICrKwy-t2K6i-c8A.jpeg)

#### **Step 3: Embed the form on your Form Page**

Open your form in Formstack and click the “Publish” tab. Copy the code that appears beneath the “Embed this form on your website:” header. Then, paste it into the **embedded form** section of your Form Page:

![](https://cdn-images-1.medium.com/max/800/1*40ihQHcOBjRuJ8j2HHpxiw.jpeg)

#### **Step 4: Select “Formstack with file upload \(success message on different page\)” from the Form Embed Type menu:**

![](https://cdn-images-1.medium.com/max/1000/1*4sut1bfBxIcTRzXU9iQ0TQ.jpeg)

#### **Step 5: Make sure the process is working smoothly**

Since you’re coordinating between 2 tools — Mass.gov and Formstack — it’s a good idea to try to submit a form yourself to make sure everything works the way you want it to. Some things that can go wrong include:

* If you forget to change your Service Detail page’s URL from “edit” to “www” in Formstack, users won’t be able to access it.
* If you forget to publish the Service Detail page, users won’t be able to access it.
* If you forget to select “Formstack with file upload \(success message on different page\),” users won’t be taken to the submission success page, and their files won’t be uploaded.

#### **Optional: Prevent your “submission received” page from showing up in searches.**

Any page that’s published on Mass.gov is searchable. However, you can prevent users from accidentally landing on your “submission received” page. To do this, open the “metatags” in the gray authoring box on the right.

![](https://cdn-images-1.medium.com/max/800/1*iH5s2U1EtN-FNpD5DvlUUw.jpeg)

Then, open the “Advanced” dropdown, and click the box next to “Prevents search engines from indexing this page.”

![](https://cdn-images-1.medium.com/max/800/1*zLSDeHGeISMRPavt8-gMpw.jpeg)

### Creating a Form Page _without_ a file upload

This resource assumes that you’ve already built your form in Formstack. \(If it is an older form, make sure you change the theme to Mayflower.\)

#### **Step 1: Embed the form on your Form Page**

Open your form in Formstack and click the “Publish” tab. Copy the code that appears beneath the “Embed this form on your website:” header. Then, paste it into the **embedded form** section of your Form Page:

![](https://cdn-images-1.medium.com/max/1000/1*40ihQHcOBjRuJ8j2HHpxiw.jpeg)

#### **Step 2: Select “Formstack with no file upload \(success message on same page\)” from the Form Embed Type menu:**

![](https://cdn-images-1.medium.com/max/1000/1*HWz4ZRPze9lxYJxaZo6d4Q.jpeg)

You may want to edit the message that Formstack normally displays to tell users that they’ve successfully submitted. To do this:

1. Open your form in Formstack.
2. Under the “Settings” tab, open the “Email & Actions” menu on the right side. Click the “Add a submission message” button.

![](https://cdn-images-1.medium.com/max/1000/1*G8UiDT39gtyL4fzPgT1_CA.jpeg)

3. Select the middle option, “Display a custom message.” Enter the text you want users to read after they’ve successfully submitted a form, and then “Save Submission Message.”

![](https://cdn-images-1.medium.com/max/1000/1*3cjUXT0lULKq9d8WKXc43g.jpeg)

#### **Step 3: Make sure the process is working smoothly**

Since you’re coordinating between 2 tools — Mass.gov and Formstack, it’s a good idea to try to submit a form yourself to make sure everything works the way you want it to.

### Was this resource helpful?

[Take this 1-minute survey and tell us if this resource was useful.](https://massgov.formstack.com/forms/resource_library_feedback?Article=Forms)

