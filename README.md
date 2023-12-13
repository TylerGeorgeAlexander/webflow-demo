# Colossalmedia Demo Template Using Webflow

In the CMS Collections tab, you can configure a similar link structure with slugs, much like Colossalmedia's site.

The pattern observed on their work page is typically one of two types:
- Work: `https://colossalmedia.com/work/gucci`
- Case-Studies (essentially their blog): `https://colossalmedia.com/case-studies/vans-2023`

![Webflow CMS Collection Menu](webflow-cms-collection-menu.png)

The Projects template may be the best option to closely emulate the original site's design.

## Brief Guide to Recreating Colossalmedia's Website Using Webflow's CMS Collections

1. **Create CMS Collections:**
   - Navigate to the CMS Collections tab in your Webflow project.
   - Establish two collections: "Work" and "Case Studies."
   - Include fields such as Title, Slug, Description, etc., in each collection.

2. **Design CMS Templates:**
   - Craft templates for "Work" and "Case Studies" pages, incorporating elements like Title and Description.
   - Utilize the Projects template as a baseline for design, aiming to mirror Colossalmedia's site.

3. **Set Up Collection Pages:**
   - Generate collection pages for "Work" and "Case Studies" in Webflow.
   - Connect these pages to their corresponding CMS collections and templates.
   - Configure the slug field in the collection pages to align with your desired URL structure:
     - For "Work," format the slug as: `/work/{slug}`.
     - For "Case Studies," format the slug as: `/case-studies/{slug}`.

4. **Populate the Collections:**
   - Fill your CMS collections with content, ensuring each entry has a unique slug, title, description, etc.

5. **Create Navigation:**
   - Design a navigation menu linking to "Work" and "Case Studies."
   - Ensure these links direct users to the respective collection pages.

6. **Publish Your Website:**
   - After configuring your CMS collections, templates, and pages, go ahead and publish your site.

By adhering to these guidelines, you can construct a Webflow website that mirrors Colossalmedia's layout, featuring CMS collections for "Work" and "Case Studies," along with templates that replicate the original site's aesthetics. Be sure to tailor the design elements, styles, and interactions to suit your specific needs and vision.
