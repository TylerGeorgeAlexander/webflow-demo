quick mockup notes

# colossalmedia demo template using webflow

CMS collections tab appears to be where we can set the similar link structure with the slugs.

The pattern I recognized on their work page follows either
work
https://colossalmedia.com/work/gucci
or 
case-studies - their blog essentially
https://colossalmedia.com/case-studies/vans-2023

![Webflow CMS collection menu](webflow-cms-collection-menu.png)

The Projects template may emulate the closest design to their original site.



here is a brief guide

To recreate a website similar to Colossalmedia using Webflow's CMS collections, you can follow these steps:

1. **Create CMS Collections:**
   - In your Webflow project, go to the CMS Collections tab.
   - Create two collections: one for "Work" and one for "Case Studies."
   - Add fields to each collection, including Title, Slug, Description, and any other relevant information.

2. **Design CMS Templates:**
   - Design templates for both "Work" and "Case Studies" pages. These templates should include fields for Title, Description, and any other content you want to display.
   - You can use the Projects template as a reference for the design, making it resemble the original Colossalmedia site.

3. **Set Up Collection Pages:**
   - Create collection pages for "Work" and "Case Studies" in Webflow.
   - Link these collection pages to their respective CMS collections and templates.
   - Make sure to set the slug field in the collection pages to match the URL structure you mentioned:
     - For "Work," set the slug to use "work" like this: `/work/{slug}`.
     - For "Case Studies," set the slug to use "case-studies" like this: `/case-studies/{slug}`.

4. **Populate the Collections:**
   - Start adding content to your CMS collections. Each entry should have a unique slug, title, description, and any other content you've designed for.

5. **Create Navigation:**
   - Design a navigation menu that includes links to "Work" and "Case Studies."
   - Set these links to go to the respective collection pages.

6. **Publish Your Website:**
   - Once you've set up your CMS collections, templates, and pages, publish your website.

By following these steps, you can create a website in Webflow that replicates the structure of Colossalmedia, with CMS collections for "Work" and "Case Studies" and templates that match the original design. Remember to customize the design elements, styles, and interactions to achieve the desired look and functionality.


Newport is a free photography template that emulates closely to their existing site.

Creating a new CMS `Work` it can then be linked to slugs.
Similarly `case-studies` or `field notes` could be created as a new CMS collection.

Here are instructions on how to potentially migrate from Wordpress to Webflow
https://university.webflow.com/lesson/migrate-from-wordpress-to-webflow-cms?topics=cms-dynamic-content

By default, WordPress exports your content in XML format, but there are many plugins available that let you export specific content types and fields as a CSV. 
Some of the plugins may be deprecated but there seems to be different options (possibly pay for plugin)
However, after it's exported we should be able to Import your CSV into Webflow.

Important to note, Webflow is a low to no code platform. It seems that reverting history is their form of version control. There may be a limit on 0-10 editors, and collaboration may be different than working on GitHub or another Git platform.

## Key features and functionalities:

Contact form tailored for service inquiries:
https://university.webflow.com/lesson/homepage-contact-form

Suggested content pieces for visitors on site:
It may be possible using MemberStack, however there is discourse over the topic:
https://discourse.webflow.com/t/displaying-personalised-content/99742/5

Search/filter capabilities on case study and field notes pages:
https://webflow.com/blog/dynamic-filtering-and-sorting
https://university.webflow.com/lesson/site-search?topics=elements

Responsive design optimized for desktop, tablet, and mobile viewing:
Should be achievable through their GUI breakpoints for each device.

Great video hosting & gallery/library capabilities:
Self hosting may pose challenges so researching video hosting sites as an alternative may increase performance.

Newsletters capabilities:
Discourse on the topic:
MJML - The Responsive Email Framework 
https://mjml.io/
May help in this venture, but it may bypass webflow
https://discourse.webflow.com/t/can-you-create-an-email-newsletter-in-webflow/251928

"Webflow is not a suitable tool to build HTML for email campaign use. All you need to do is understand the lack of support for various HTML/CSS features in most mail clients. There is a reason that email service providers exist."

Google metrics tracking:
https://university.webflow.com/lesson/set-up-google-analytics?topics=seo


