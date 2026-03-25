<p align="center">
  <img src="./assets/notum-logo.svg" alt="Notum logo" width="240" />
</p>

# Notum Technologies

We build **Strapi-based systems that don’t fall apart at scale**.

Most CMS setups work fine... until:
- Multiple teams start editing content
- Multiple markets need different rules
- Integrations pile up
- Releases become risky

That’s where we usually come in.



## Our clients

### SaaS scale-ups (Series A/B, $20M+)

- https://strapi.io  
- https://www.meilisearch.com  
- https://lokalise.com  

You have:
- Fast product iteration  
- Global content + localization  
- A small team doing everything  

Things start breaking when:
- Content models don’t match product complexity  
- Marketing layer slows you down  
- Editors don’t have proper tooling  



### Mid-market / enterprise platforms (500–3,000 people)

- https://www.direct.cz  
- https://optitrack.com  

You have:
- Multiple brands / regions  
- CMS connected to internal systems  
- Several teams touching the same platform  

Things start breaking when:
- Content ops become slow across markets  
- Integrations get fragile  
- Releasing changes feels risky  



## What we actually build

- CMS architecture that survives multi-team usage  
- Next.js frontends (SSR / ISR where it makes sense)  
- Integrations with CRM / ERP / internal APIs  
- Content models for multi-brand / multi-locale setups  
- Migrations from legacy CMSs → Strapi  
- Fixing your Strapi that became unmaintainable  



## How we work

We don’t sit outside your team.

- Same repo  
- Same CI/CD  
- Same release cycle  

We take ownership of parts of the system (FE / BE / QA) and **ship continuously**.



## Open source & community

We put a lot of our work back into the ecosystem.

- Our **Strapi + Next.js starter** is public  
- We use it on every new project  
- We **continuously backport improvements from real production work**  
- We build plugins when something is missing  

Why we do this:
- Good defaults remove entire classes of problems  
- Shared tooling → faster teams, fewer mistakes  



## What you’ll find here

Not demos. Not experiments.  
This is code that comes from actual projects.

### 🚀 Starter

**[`strapi-next-monorepo-starter`](https://github.com/notum-cz/strapi-next-monorepo-starter)**

- Turborepo (apps + shared packages)  
- Strapi + Next.js + shadcn/ui  
- structure that works with multiple apps and teams  



### 🔌 Plugins

- [`strapi-plugin-seo`](https://github.com/notum-cz/strapi-plugin-seo) → structured SEO fields  
- [`strapi-plugin-location`](https://github.com/notum-cz/strapi-plugin-location) → PostGIS + geo queries  
- [`strapi-plugin-record-locking`](https://github.com/notum-cz/strapi-plugin-record-locking) → no more overwrites  
- [`strapi-plugin-tiptap-editor`](https://github.com/notum-cz/strapi-plugin-tiptap-editor) → usable rich text editor  
- *Deprecated* [`strapi-plugin-content-versioning`](https://github.com/notum-cz/strapi-plugin-content-versioning) → content history taken over by Strapi team into v5  



### ⚙️ Other

- buildpacks (Turbo / Next optimizations)  
- migration + scraping scripts  
- small internal tools we decided to share  


## Track record

- 50+ CMS / web platforms  
- Apps handling 10M+ monthly users  
- Long-term work with the Strapi core team  


## Stack

- [Strapi](https://github.com/strapi/strapi) 
- Next.js, React  
- Node.js, TypeScript, NestJS  
- PostgreSQL (+ PostGIS)  
- API-first architecture  



If your CMS is:
- Slowing releases down  
- Breaking with multiple teams or regions
- Or becoming “that thing nobody wants to touch” 


you’ll likely recognize the problems this code is solving.
