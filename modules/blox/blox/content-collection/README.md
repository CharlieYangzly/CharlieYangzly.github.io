# Collection Block

**Transform your content into stunning, organized displays**

The Collection block is your ultimate content curation tool, designed to showcase your blog posts, publications, projects, or any content type in beautifully organized, filterable displays.

## ✨ Key Features

- **Smart Filtering**: Filter by folders, tags, categories, authors, publication types, and more
- **Flexible Sorting**: Sort by date, title, or any custom field in ascending or descending order
- **Multiple Views**: Choose from `card`, `article-grid`, `citation`, `date-title-summary`, `slides-gallery`, or `event-row` layouts — see [Available Views](#-available-views)
- **Pagination Ready**: Built-in support for limiting items and pagination
- **Archive Integration**: Automatic "See All" links to full archive pages
- **Responsive Design**: Perfectly optimized for all screen sizes

## 🎯 Perfect For

- **Blog Showcases**: Display your latest blog posts with beautiful card layouts
- **Publication Lists**: Showcase academic papers and research with citation views
- **Project Galleries**: Present your portfolio work in stunning visual grids
- **News & Updates**: Keep visitors informed with filtered content streams
- **Content Archives**: Create organized content hubs by topic or category

## 🖼️ Available Views

Set `view` in a section's `_index.md` front matter (or `design.view` on a Collection block) to
control how items are rendered. Views are resolved by name; an unrecognised value falls back to
`card`.

| `view` | Best for | Layout |
|--------|----------|--------|
| `card` _(default)_ | Blog posts, projects | Cover-image cards (title, summary, metadata) stacked in a single reading-width column. |
| `article-grid` | Portfolios, showcases | The same cards arranged in a responsive multi-column grid (`columns` configurable). |
| `citation` | Publications | Formatted APA/MLA citation rows (authors · year · title · venue) with attachment links. |
| `date-title-summary` | News, changelogs | Minimal chronological list: date, title, and a short summary with a "Read more" link. |
| `slides-gallery` | Slide decks | 16:9 thumbnails with a play overlay and slide count. |
| `event-row` | Talks, events, press | Compact row: logo · title · date · location, with the summary beneath. |

```yaml
# In the collection's `_index.md` front matter:
view: event-row
```

## 🚀 Why Choose Collection Block?

**Effortless Content Management**: No manual updates needed - your content automatically appears as you publish

**Advanced Filtering**: Powerful filtering system that works with Hugo's built-in taxonomies and custom parameters

**SEO Optimized**: Clean markup and semantic HTML structure for better search engine visibility

**Performance First**: Lightweight and fast, with optimized queries and lazy loading support

## 📊 Use Cases

- Academic portfolios showcasing publications by research area
- Corporate blogs with category-based content organization
- Creative portfolios with project filtering by type or client
- News sites with topic-based content streams
- Personal blogs with tag-based content discovery

Start building engaging content displays that keep your visitors exploring and discovering more of what you have to offer.

