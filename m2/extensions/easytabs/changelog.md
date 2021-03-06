---
layout: default
title: Easy Tabs Changelog
description: Easy Tabs changelog
keywords: easytabs changelog, easytabs updates
category: Easy Tabs
---

# Changelog

### Version 1.9.5

> Dec 8, 2020

 -  [Swissup_Pagebuilder](/m2/extensions/pagebuilder/) integration.

### Version 1.9.4

> Nov 26, 2020

  - Fixed "Your session has expired" error message when ajax tab has product listing.

### Version 1.9.3

> Oct 13, 2020

 -  Do not show disabled tabs in the Easytabs widget form

### Version 1.9.2

> Sep 23, 2020

  - Fixed missing reviews at AMP page.

### Version 1.9.1

> Aug 25, 2020

  - Fixed not expanded tab when use direct link to tab (link with tabs alias in anchor).

### Version 1.9.0

> Aug 5, 2020

 -  Prevent page jumping while scripts are initializing.
 -  Fixed automatic cache invalidation on content and tab update.

### Version 1.8.12

> Jun 9, 2020

  - Fixed missing description tab after last release.
  - Fixed typos.

### Version 1.8.11

> Jun 5, 2020

  - Added config option to enable/disable product tabs.
  - Fixed broken Delete action in action column.

### Version 1.8.10

> May 7, 2020

 -  Added config for product tabs to enable accordion layout on desktop
 -  No limits for product attribute tab - add as many attributes as you need
 -  UX improvements in admin. Colorized tabs grid.
 -  Added alias column in grid
 -  Fixed attribute tab rendering
 -  16 locales added to translate backend and frontend phrases:
    - Arabic
    - Chinese
    - Dutch
    - French
    - Hebrew
    - Italian
    - German
    - Japanese
    - Norwegian
    - Korean
    - Polish
    - Portuguese
    - Russian
    - Spanish
    - Swedish
    - Ukrainian

### Version 1.8.8

> Mar 20, 2020

 -  Improvement for tab content loaded with ajax. Initialize UI components at tab load.

### Version 1.8.7

> Mar 11, 2020

 -  Fixed attribute tab rendering.
 -  Easy Tabs grid UX improvements.

### Version 1.8.6

> Feb 17, 2020

 -  [Marketplace](https://github.com/swissup/module-marketplace) module compatibility improvements.

### Version 1.8.5

> Jan 31, 2020

 -  Fixed not working ajax tabs at [AMP](/m2/extensions/amp/) pages.
 -  Stability improvements.

### Version 1.8.3

> Dec 13. 2019

 -  Small improvement to edit tab form.
 -  Fixed to work at Magento Enterprise Cloud Edition.

### Version 1.8.2

> Dec 6, 2019

 -  Fixed scroll to reviews when click view reviews link.
 -  Improvement for options of product attribute tab at edit form in Magento Admin.

### Version 1.8.1

> Dec 4, 2019

 -  Show loader when content of the tab is loading with ajax.
 -  Reduce page content jumps on tab opening.

### Version 1.8.0

> Dec 2, 2019

 -  New option for tab "Load content with Ajax". The biggest benefit from this option is reduce initial page size.
 -  Totally reworked admin interfaces for tab editing. Edit form build as Magento 2 UI Component. It looks up to date and works like a charm.
 -  No more separate grids for product tabs and widget tabs. All in one place. Product tabs has field "Hide on Product" as No and widget tabs "Hide on Product" - Yes.
 -  Block HTML cache and Full Page Cache marked as invalidated after tab save.

### Version 1.7.5

> Nov 11, 2019

 -  Fixed exception 'The XML in file "../easytabs.xml" is invalid'.
 -  Fixed JS error "this.value.push is not a function". Error occurs for tab type `Product Attribute` when user selects attribute.
 -  Fixed section title'<span>Conditions</span>' in admin at Magento 2.3.3 when edit tab.
 -  Add LESS vars to customize expanded tabs.

### Version 1.7.4

> Oct 22, 2019

 -  Show multiple attributes for _Product attribute_ tab. Thanks [@erankitsrivastava](https://github.com/erankitsrivastava) for contribution.
 -  Few minor tweaks to edit tab form in Magento Admin - attribute select is UI Component; spinner while options blocks loads on initial page load.
 -  Product attribute tab has two templates:
     +  `tab/catalog/product/attribute.phtml` - show attribute content without attribute label;
     +  `tab/catalog/product/attribute-with-label.phtml` - show attribute content with label.

### Version 1.7.2

> Sep 25, 2019

 -  Use theme less variable for tab control border width.

### Version 1.7.1

> Sep 5, 2019

 -  Fix no tabs when Easytabs widget is added via Magento Admin interface

### Version 1.7.0

> Aug 19, 2019

 -  **New tab condition** - Show tab for selected Product Type only.
 -  Widget tabs have new tab type - product reviews. This can be helpful at Argento Luxury design when you want to move reviews from product tabs to additional tabs block.

### Version 1.6.0

> Jun 18, 2019

 -  Support of [Swissup AMP module](../../amp/). Now you can have tabs (accordion) at AMP version of your site.
 -  New condition to have tab for AMP version only. Works with Swissup AMP.

### Version 1.5.2

> Jun 7, 2019

 -  Merge styles with theme and use its less variables.
 -  Minor JavaScript improvements.

### Version 1.5.1

> May 24, 2019

 -  Fixed error during data install - area code not set.

### Version 1.5.0

> Apr 16, 2019

 -  New feature - conditions for tabs. Now it is possible to show tab when customer is signed in or when product has some attribute value.
 -  Improved stability when there is tab for some third-party module but module is disabled or removed.

### Version 1.3.4

> Sep 21st, 2018

 -  Fix error caused by review tab when there is other non-tab review block on product page.

### Version 1.3.3

> Sep 6th, 2018

 -  Fixed delete mass action and store filter in admin grids.

### Version 1.3.2

> Aug 3rd, 2018

 -  Fixed activate and scroll to tab on external link click.

### Version 1.3.1

 -  Fixed possible "Requested product doesn't exist" error, when editing cart item

### Version 1.3.0

 -  Expanded tabs layout added.
 -  Fix tab's assigned stores output in grid in Magento Admin.

### Version 1.2.1

 -  Widget feature added: add tabs at any page now!

### Version 1.0.5

 -  Magento 2.2 compatibility

### Version 1.0.4

 -  ACL instructions added to UI components according to latest Magento requirements

### Version 1.0.3

 -  ACL sort order fixes

### Version 1.0.2

 -  Updated installation instruction
 -  Corrected grid acl
 -  Review block jsLayout config added to prevent js error

### Version 1.0.1

 -  Menu item moved to `Swissup > General`

### Version 1.0.0

 -  Initial Release
