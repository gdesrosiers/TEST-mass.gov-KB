---
description: 'How to create clear, accessible data tables.'
---

# Tables

### Summary

A data table is a table for organizing and presenting data.

Sometimes web content authors use tables for layout — to position objects and text in space. [While layout tables aren’t inherently inaccessible](https://webaim.org/techniques/tables/), you should avoid using them this way on Mass.gov.

As a general guideline, avoid copying and pasting tables from other places. This often generates tables that behave in unexpected and undesired ways. Instead, re-create tables using the table tool, as described below.

### How to make a data table

#### **The basics**

To make a table, find the table tool in a rich text editor. You can find rich text editors in most content types on Mass.gov. For example, Service Details, How-tos, Location pages, and Guides all have rich text editors. Here’s where to find the table tool:

![](https://cdn-images-1.medium.com/max/800/1*mmdNelOdKDaa6pKnwPKP8g.png)

Clicking the table tool will open up the “Table Properties” menu. This is where you’ll structure your table. You can tell the CMS how many rows and columns you want, and if you want headers or captions. \(Don’t worry if you mess up — you can edit all of these later.\)

![](https://cdn-images-1.medium.com/max/800/1*3QDH4QT25RtU7lm3AWOGHw.png)

### **Headers and captions: Key tools for clarity and accessibility**

**Headers:** You can choose to use headers for your table’s columns, rows, or both. Headers are important for 2 reasons. First, they help users distinguish between labels for data and data itself.

Second, [headers are important for screen readers, tools that help those who have trouble seeing or reading interact with your content](https://www.youtube.com/watch?v=q_ATY9gimOM). Screen readers can cycle through table headers and columns to help users navigate tables — but only if those headers are formatted as headers \(and not, for example, using bold or italics\).

Here’s how row and column headers appear on Mass.gov:

![](https://cdn-images-1.medium.com/max/800/1*UPiWu2CAfJFey2_dLfNllg.jpeg)

Note that the CMS automatically prevents headers from spanning multiple columns or rows, [since spanned headers aren’t always supported by screen readers](https://webaim.org/techniques/tables/data#headers). It’s often a good idea to “flatten” headers \(i.e. just have one\) anyway, since multiple header layers can be confusing for anyone to read.

For example, here’s a table with 2 layers of headers…

![](https://cdn-images-1.medium.com/max/800/1*QrvQ48K6bsgiAQHPcL0i-A.png)

…that could be improved by merging the rows:

![](https://cdn-images-1.medium.com/max/800/1*MKOPHb362U0iO-QuYtivvA.png)

**Captions:** Think of a caption like a table’s title. You can use a caption to explain or provide context for the data in your table. As with headers, screen readers can associate captions with the tables they describe.

By default, table captions are plain text and center-aligned. However, you can format them as bold, italic, or even as a heading. At this time, you can’t realign captions: they must be centered.

### Entering data into and editing data tables

Compared to other things you can do with the rich text editor, tables are complicated. As a result, getting the most out of them requires a little more effort than other aspects of the CMS. It’s even helpful to know how to change the HTML, which you can examine by using the “source” tool in the rich text editor. [Here’s a resource that will help acquaint you with table-related HTML](https://www.quackit.com/html/tags/html_table_tag.cfm).

When you first create your table, you’ll see something that looks like this:

![](https://cdn-images-1.medium.com/max/800/1*ukwXMTPaFckuMI__tLqfSQ.png)

It looks this way because it has no data in it. It will automatically resize itself as you begin to enter data.

It can also be hard to place your cursor in a data-less table’s cell, since they’re so thin. However, if you place your cursor at the end of the caption or above the table, you can move your cursor into the top left cell by using the right arrow or the down arrow. If you place your cursor beneath the table, you can move into the bottom right cell by using the left arrow or the up arrow.

Once your cursor is in the table, you can move left to right using:

* Right arrow
* Down arrow
* Tab

You can also move right to left using:

* Left arrow
* Up arrow
* Shift+tab

#### **What if there’s nowhere to put my cursor above or below the table \(i.e. how do I add a line break?\)**

To add a line break before or after your table, hover your cursor near the first or last row. A horizontal, red, dotted line will appear across the editor. Find and click the arrow on the line’s right to insert a line break.

![](https://cdn-images-1.medium.com/max/800/1*zra_74ND0Hk0q0LkHFG4cQ.png)

### **Adding and deleting rows and columns**

If you need to add columns or rows to your table, move your cursor to a column or row that is next to where you want your new column or row. Right click to open the table menu. Then, open the “column” or “row” submenu, and select “insert…before” or “insert…after” \(depending where you want your new column or row to go\).

![](https://cdn-images-1.medium.com/max/800/1*KkAxJGVBJ0-K50pkj8Fwxw.png)

To delete a column or row, right click on the column or row you want to remove. Then, open the “column” or “row” submenu and select “delete.”

It’s also possible to add a single cell by right clicking in a row, opening the “cell” submenu and selecting “insert cell before” or “insert cell after.” Currently, both options only add a cell to the end of the row.

**Note:** You will not be able to change the number of rows or columns from the “table properties” menu after you’ve created the table. Use the method above instead.

### **Adding and deleting captions to existing table**

You can add a caption to an existing table by right clicking anywhere on the table and selecting “Table Properties.” This will bring up the menu you saw when you first clicked the table option, and you can type in a caption.

![](https://cdn-images-1.medium.com/max/800/1*f7RQDDtrYT7CHmPRx6XWMw.png)

![](https://cdn-images-1.medium.com/max/800/1*w2g1GyAfynLrLCXdnieR_g.png)

Removing a caption is a little harder. You can highlight and erase the caption text, but you may find that the caption formatting is stubborn: Your cursor will remain center-aligned over the table, and you won’t be able to “backspace” to the beginning of the line.

You can easily remove the caption by removing its HTML tags. Click on the “source” button at the far right of the rich text editor:

![](https://cdn-images-1.medium.com/max/800/1*r35nhIzYE8TEQ_qIQ2D3gg.png)

Next, find the table with the offending caption. You can identify a table in HTML by looking for the &lt;table&gt; tag. Beneath the table tag, you’ll see more HTML tags and the content that you’ve entered in the table.

Once you’ve found the right table, look for tags that indicate the beginning and end of the caption: &lt;caption&gt; &lt;/caption&gt;. Highlight and delete them.

![](https://cdn-images-1.medium.com/max/800/1*5OIUEc7bNGuHrFOBjMrFxQ.png)

Then, click “source” again to return to the normal content editing view.

Here’s a video that provides an example of how to effectively use headers and captions:

### **More information on accessibility**

You can learn more about online accessibility and how people with disabilities experience the internet from [W3C](https://www.w3.org/), the authoritative source for accessibility best practices. Here’s a selection of informative resources:

* [Tables Concepts](https://www.w3.org/WAI/tutorials/tables/)
* [How People with Disabilities Use the Web: Overview](https://www.w3.org/WAI/intro/people-use-web/)
* [Web Accessibility Perspectives Videos: Explore the Impact and Benefits for Everyone](https://www.w3.org/WAI/perspectives/)

Need advice on accessibility? Reach out to [EOTSS accessibility expert Sarah Bourne at Sarah.Bourne@mass.gov.](mailto:sarah.bourne@mass.gov)

### Was this resource helpful?

[Take this 1-minute survey and tell us if this resource was useful.](https://massgov.formstack.com/forms/resource_library_feedback?Article=Tables)

