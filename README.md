# Awesome GPT Image 2 Work Prompts

50 bilingual GPT Image 2 prompts for practical work visuals: marketing, ecommerce, sales, brand systems, operations, education, HR, customer success, community, and founder strategy.

This repository is designed for builders who want prompt examples that can be used in real websites, SaaS prompt libraries, content operations, and business design workflows. Each prompt includes a structured JSON record, English and Chinese Markdown versions, and a generated PNG example image.

[中文说明](README.zh-CN.md)

## What This Repository Provides

- 50 original GPT Image 2 / ChatGPT Images 2.0 prompts for workplace use cases.
- Bilingual prompt content in English and Simplified Chinese.
- A website-friendly JSON dataset at `data/prompts.json`.
- One Markdown file per prompt under `prompts/en/` and `prompts/zh-CN/`.
- 50 generated PNG examples under `images/`.
- Category indexes for content browsing and GitHub navigation.

## Who It Is For

Use this prompt library if you are building:

- an AI prompt directory or prompt marketplace;
- a GPT Image 2 prompt gallery;
- a SaaS website with image-generation examples;
- an internal marketing, sales, HR, or operations prompt library;
- a bilingual AI tools page targeting both English and Chinese users.

## Categories

| Category | Use cases |
| --- | --- |
| Marketing & Growth | LinkedIn launch visuals, ads, email banners, app store graphics |
| Product & Ecommerce | Product hero images, listing infographics, demo visuals |
| Brand & Design System | Moodboards, design tokens, logo guides, icon direction |
| Sales & Pitch | Investor slides, ROI visuals, sales one-pagers, case studies |
| Education & Training | Microlearning cards, diagrams, workshop posters, certificates |
| Data & Operations | Dashboards, process maps, timelines, planning boards |
| HR & Internal Comms | Onboarding maps, benefits explainers, all-hands slides |
| Customer Success & Support | Help center visuals, adoption headers, escalation flows |
| Events & Community | Webinar banners, community posters, meetup covers |
| Founder & Strategy | Market maps, pricing concepts, roadmap posters, operating models |

## Dataset Format

`data/prompts.json` is the canonical source for applications and websites. Each record includes:

- `id` and `slug`
- bilingual `title`
- bilingual `category`
- bilingual `target_user`
- bilingual `use_case`
- bilingual `prompt`
- prompt structure and constraints
- `image_path`
- generation metadata without local machine paths

Example:

```json
{
  "id": "gptimg2-work-001",
  "slug": "linkedin-launch-carousel-cover",
  "category": {
    "slug": "marketing-growth",
    "en": "Marketing & Growth",
    "zh": "营销增长"
  },
  "image_path": "images/gptimg2-work-001-linkedin-launch-carousel-cover.png"
}
```

## Prompt Philosophy

The prompts are organized around user work needs rather than entertainment styles. The goal is to make every prompt usable as a business asset request: it should define the audience, deliverable, visual layout, text rules, composition constraints, and negative constraints.

These prompts are original rewrites synthesized from public research into GPT Image 2 prompt patterns. Public community collections, X discussions, GitHub lists, and prompt galleries were used for inspiration and taxonomy only; this repository does not copy third-party prompts verbatim.

## SEO And GEO Notes

This repository targets search intents such as:

- GPT Image 2 prompts
- ChatGPT Images 2.0 prompts
- GPT Image 2 prompt examples
- AI image prompts for work
- business AI image generation prompts
- bilingual AI image prompt dataset
- prompt library JSON for websites

For generative engine optimization, the content is written in an answer-first structure with clear category names, direct use cases, reusable JSON, and explicit source policy. This makes the repository easier for AI search engines and answer engines to cite accurately.

## Repository Structure

```text
.
├── categories/
├── data/
│   ├── prompts.json
│   └── sources.json
├── images/
├── prompts/
│   ├── en/
│   └── zh-CN/
├── LICENSE
├── README.md
└── README.zh-CN.md
```

## Model Naming

The public naming around the release uses both `GPT Image 2` and `ChatGPT Images 2.0`. This repository keeps both terms in the metadata so the dataset can work for developer documentation, website pages, and prompt-library search.

## License

See [LICENSE](LICENSE).
