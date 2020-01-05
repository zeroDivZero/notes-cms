# HEADLESS

Headless CMS is backend-only CMS built as content repo that makes content accessible via RESTful API for display on any device.

_Headless_ comes from concept of chopping _head_ (frontend) off _body_ (backend, i.e., content repo).

Traditional CMS combines content and presentation layers (and templates, site structure, design, etc.). Headless CMS has only content component and focuses on admin interface for content creators, facilitation of content workflows and collaboration, and organization of content into taxonomies. Stores content in pure format and provides access to other components (frontends, analytics tools, etc.) through stateless or loosely coupled APIs.

Allows personalized content via multiple channels at all stages of customer journey. Content in headless CMS considered _pure_ (no presentation layer attached), one instance can be used for display on any device.

## Vs Coupled CMS

Traditional (monolithic) CMS systems are _coupled_, combining content management application (**CMA**) and content delivery application (**CDA**) into single app. Backend tools, content editing and taxonomy, website design, and templates are inseparable.

Coupled systems are useful for blogs and basic websites as everything can be managed in one place. But code cannot be easily moved to another CMS.

Decoupled CMS and headless one are often mistaken for one another because they have lots in common.

Decoupled CMS separates CMA and CDA, typically with content created behind firewall, then synchronized and pushed to delivery environment. Main difference between decoupled and headless is decoupled architecture is active -- it prepares content for presentation and then pushes into delivery environment, whereas headless is reactive -- it sits idly until request sent for content.

Decoupled architecture allows for easier scalability and provides better security than coupled architecture, but it does not provide same support for omnichannel delivery. Also, managing multiple environments means higher infrastructure and maintenance costs.
