# Aashish K

I run **Bhima Capital**, a holding company that acquires, builds and operates online businesses. I do the technical work myself: SEO tooling, web and e-commerce builds, and the infrastructure underneath them.

Most of my code lives in private repos tied to live businesses. The contribution graph shows how much I ship. This page shows what it is.

---

## What I build

**SEO and link-building tooling**
- **link404**: a FastAPI broken-link auditing service running on a VPS. It classifies redirects, detects hijacked domains, ranks link opportunities by semantic relevance and discovers resource lists on GitHub. This is mostly useful for hunting 301 redirects that link sellers tend to provide and is used to find boosted sites, it also helps to find out why certain sites have inflated domain metrics, and which kinds of links tend to correlate with traffic. → [bhima-audit.pages.dev](https://bhima-audit.pages.dev)
- **Domain enrichment**: domain status checks over RDAP and DNS-over-HTTPS, plus a Google Apps Script pipeline that enriched ~1,800 domains with traffic, authority and contact data. The pipeline uses resumable triggers to work around execution limits.
- **Prospecting**: tools that find newsletters and editorial link opportunities.

**Web and e-commerce**
- WordPress / WooCommerce stores and block (FSE) themes. I build on native hooks rather than page builders.
- Static sites built with Eleventy on Cloudflare Pages, proxied into main domains.
- A multi-site build queue. Daily checks and indexing jobs for each site run on GitHub Actions.

**Outreach and PR automation**
- A reactive PR pipeline that matches journalist queries to experts.
- Email discovery and verification feeding outreach campaigns.

**AI-assisted workflows**
- Reusable Claude Code skill pipelines for SEO audits, content operations and link building.

---

## Stack

`Python` `FastAPI` `PHP` `WordPress` `WooCommerce` `JavaScript` `Google Apps Script` `Cloudflare Pages & Workers` `Ubuntu / Vultr` `GitHub Actions` `Claude Code`

---

## Businesses I operate

- **GulfPhysio**: a physiotherapy and clinic supply store in the UAE
- **HealthSpark PR**
- **PowerYourCurls**
