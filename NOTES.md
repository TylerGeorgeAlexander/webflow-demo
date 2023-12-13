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