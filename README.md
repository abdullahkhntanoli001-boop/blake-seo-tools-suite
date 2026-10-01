# 🚀 Blake SEO Tools: Open-Source Structured Data & AI Crawler Directives

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Website](https://img.shields.io/badge/Live%20Platform-blakeseotools.com-emerald.svg)](https://blakeseotools.com)
[![Version](https://img.shields.io/badge/Version-2.5%20Pro-blueviolet.svg)](https://blakeseotools.com)

Welcome to the official open-source toolkit by **[Blake SEO Tools](https://blakeseotools.com/)** — an enterprise-grade suite of validated Google JSON-LD schema markups, Generative Engine Optimization (GEO) directives, and AI bot crawler configurations.

---

## 🌟 Live Interactive Platform
Generate schemas visually with instant live preview and zero registration:
👉 **[Launch Blake SEO Tools Suite](https://blakeseotools.com/)**

### Included Webmaster Generators:
* ❓ **FAQ Page Schema Generator** (Boost SERP CTR with interactive accordion snippets)
* 📰 **Article & Blog Posting Schema** (E-E-A-T validated structured data for publishers)
* 🏬 **Local Business Schema** (NAP consistency & Google Maps local pack optimization)
* 🏷️ **Open Graph & Twitter Cards** (Social snippet debugger & Google SERP previewer)
* 🤖 **Robots.txt & AI Crawler Controller** (Granular access rules for GPTBot, Claude, Gemini, and Perplexity)

---

## 📦 What's Inside This Repository?

```text
├── schemas/
│   ├── faq-schema.json            # Google Rich Snippet FAQ JSON-LD template
│   ├── article-schema.json        # NewsArticle & BlogPosting JSON-LD template
│   └── local-business.json       # Schema.org LocalBusiness with GeoCoordinates
├── robots/
│   ├── ai-friendly-robots.txt     # Optimized robots.txt for AI search citation
│   └── secure-robots.txt          # High-security hardened crawling directives
├── LICENSE                        # MIT License
└── README.md                      # Documentation & Best Practices
```

---

## 🛠️ Quick Implementation Guide

### 1. JSON-LD FAQ Schema
Embed this directly inside the `<head>` of your webpage:

```html
<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "FAQPage",
  "mainEntity": [
    {
      "@type": "Question",
      "name": "How does Schema Markup boost Google organic CTR?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Structured JSON-LD code unlocks Rich Snippets and interactive dropdown accordions in Google SERPs, increasing vertical height and click-through rates by up to 35%."
      }
    }
  ]
}
</script>
```

### 2. Generative Engine Optimization (GEO 2026) Robots.txt
To allow modern AI search engines (**ChatGPT Search, Google Gemini, Anthropic Claude, Perplexity**) to cite and reference your content while keeping sensitive admin paths protected:

```txt
# Standard Search Engine Directives
User-agent: *
Allow: /
Disallow: /admin/
Disallow: /private/

# AI Search & LLM Crawlers (Allow for GEO Citations)
User-agent: GPTBot
Allow: /

User-agent: Google-Extended
Allow: /

User-agent: ClaudeBot
Allow: /

User-agent: PerplexityBot
Allow: /

# Sitemap Reference
Sitemap: https://blakeseotools.com/sitemap.xml
```

---

## 🤝 Contribution & Sponsoring
Maintained by **Blake Phillips**, founder of [Blake SEO Tools](https://blakeseotools.com).  
For editorial collaborations, sponsored case studies, and enterprise SEO tool integrations, visit our **[Partnerships Portal](https://blakeseotools.com/editorial.html)** or contact `blake.phillips.media@gmail.com`.

---

## 📄 License
This project is licensed under the MIT License - feel free to fork, customize, and deploy across commercial projects.
