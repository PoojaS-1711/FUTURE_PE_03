# AI SEO Blog & Content Cluster Generator 🔍📝

**By:** POOJA S

**Internship:** Future Interns — Prompt Engineering Track

**Tool Used:** Claude (Anthropic)

---

## What This Project Is

This repository contains a structured AI prompt system that generates complete SEO blog content clusters for local business websites — the same way professional SEO agencies work.

Instead of writing random blog posts, this system plans and generates:
- One strong pillar blog targeting a primary keyword
- Multiple supporting blogs covering related search queries
- Internal linking structure connecting all blogs
- Local SEO keyword integration throughout

---

## Business Case Study

| Field | Details |
|---|---|
| Business Name | Career Success Academy |
| Business Type | NEET Coaching Centre |
| Location | West Tambaram, Chennai – 600045 |
| Primary Keyword | Best NEET Coaching Centre in Tambaram Chennai |
| USP | Specialises in transforming average scorers (50%) into high achievers (85%+) — not just coaching toppers |
| Target Audience | Class 11-12 students and their parents in South Chennai searching for NEET coaching |

---

## Content Cluster Structure

```
PILLAR BLOG
└── Best NEET Coaching Centre in Tambaram, Chennai
    (Primary keyword, ~1,500 words, links to all 4 supporting blogs)

SUPPORTING BLOGS
├── Blog 2: NEET Coaching Fees in Tambaram – What's a Fair Price in 2026?
│   (Keyword: NEET coaching fees Tambaram Chennai)
├── Blog 3: How to Crack NEET If You're Scoring Below 50% Right Now
│   (Keyword: how to crack NEET with low marks)
├── Blog 4: NEET Coaching in Tambaram vs Self-Study – Which Works Better?
│   (Keyword: NEET coaching vs self study)
└── Blog 5: How Career Success Academy Prepares Slow Learners for NEET Success
    (Keyword: NEET coaching for slow learners Tambaram)
```

All supporting blogs include internal links back to the pillar blog.

---

## Keyword & Intent Explanation

| Blog | Primary Keyword | Search Intent |
|---|---|---|
| Pillar | Best NEET coaching centre Tambaram Chennai | Local + Informational |
| Blog 2 | NEET coaching fees Tambaram | Informational (cost research) |
| Blog 3 | How to crack NEET with low marks | Informational (struggling students) |
| Blog 4 | NEET coaching vs self study | Informational (decision stage) |
| Blog 5 | NEET coaching for slow learners Tambaram | Navigational + Informational |

---

## Repository Structure

```
FUTURE_PE_03/
├── README.md
├── prompts/
│   └── seo_blog_prompt_framework.md    — Reusable 3-prompt system
└── blogs/
    ├── 01_pillar_blog.md
    ├── 02_neet_fees_tambaram.md
    ├── 03_crack_neet_below_50.md
    ├── 04_coaching_vs_selfstudy.md
    └── 05_slow_learners_neet.md
```

---

## How to Use This for Any Business

1. Open `prompts/seo_blog_prompt_framework.md`
2. Run **Prompt 3** first to plan your content cluster
3. Run **Prompt 1** to generate the pillar blog
4. Run **Prompt 2** once per supporting blog
5. Add internal links after all content is generated
6. Upload to the business website — one blog per page

Works for any local business: clinic, salon, agency, coaching centre, gym.

---

## Prompt Logic — Why It Works

**1. Cluster before content:** Planning the full cluster first ensures all blogs support each other and target different keywords without overlapping.

**2. Search intent first:** Every blog starts with a specific search intent — what is the reader actually trying to find? This keeps content useful rather than generic.

**3. Local SEO built in:** City, area, and pincode are used naturally throughout — not forced into every sentence, but present enough to signal local relevance to Google.

**4. USP integration:** The business's real differentiator is woven into every blog — not as advertising, but as a genuine answer to reader questions.

**5. Internal linking map:** Supporting blogs link back to the pillar, which improves the pillar blog's ranking authority over time.

---

## Key Learnings

- Random blog posts do not rank. Content clusters built around one primary keyword do.
- Search intent matters more than keyword density — write for what the reader actually wants to know.
- Local SEO requires specificity: "Tambaram" outperforms "Chennai" for local searches near that area.
- A business's USP is the most powerful SEO differentiator — generic content about "best coaching" ranks for nothing.
- Internal linking between blogs is not optional — it is what makes a cluster work as a system.

---

## Tool Used

**Claude by Anthropic** — claude.ai

No paid SEO tools required. Keyword research done using Google Autosuggest and People Also Ask.

---

*This project was completed as part of the Future Interns Prompt Engineering Virtual Internship Program.*
