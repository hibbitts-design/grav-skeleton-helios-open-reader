<div align="center">

# 📖 Grav Helios Open Reader

### Ready-to-Run Skeleton Package

<p><em>Publish open textbooks, course readers, student projects, and other OER on the web – with content in portable Markdown files you fully control.</em></p>

[![Grav Discord Chat](https://img.shields.io/discord/501836936584101899.svg?logo=discord&colorB=728ADA&label=Grav%20Discord%20Chat)](https://chat.getgrav.org) [![Latest Release](https://img.shields.io/github/v/release/hibbitts-design/grav-skeleton-helios-open-reader?style=flat-square&label=Release)](https://github.com/hibbitts-design/grav-skeleton-helios-open-reader/releases/latest) [![License](https://img.shields.io/badge/License-MIT-blue.svg?style=flat-square)](https://github.com/hibbitts-design/grav-skeleton-helios-open-reader/blob/master/LICENSE) [![PHP](https://img.shields.io/badge/PHP-%3E%3D8.0-8892BF?style=flat-square&logo=php&logoColor=white)](https://learn.getgrav.org/17/basics/requirements)

<p>A free, open-source skeleton that transforms the <a href="https://getgrav.org/premium/helios">Grav Premium Helios theme</a> into a web-first open textbook and reader platform, built on <a href="https://getgrav.org">Grav CMS</a> with Markdown file-based content, a built-in Admin panel, and no database required. Purchasing the Helios theme also directly supports Grav's open-source development.</p>

<table>
  <tr>
    <td width="49%">
      <a href="https://raw.githubusercontent.com/hibbitts-design/grav-skeleton-helios-open-reader/refs/heads/main/screenshots/screenshot-1.png">
      <picture>
        <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/hibbitts-design/grav-skeleton-helios-open-reader/refs/heads/main/screenshots/screenshot-1-dark.png">
        <img alt="Reader home page with cover image, section cards, and Start Reading button" src="https://raw.githubusercontent.com/hibbitts-design/grav-skeleton-helios-open-reader/refs/heads/main/screenshots/screenshot-1.png" width="100%">
      </picture>
      </a>
    </td>
    <td width="49%">
      <a href="https://raw.githubusercontent.com/hibbitts-design/grav-skeleton-helios-open-reader/refs/heads/main/screenshots/screenshot-2.png">
      <picture>
        <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/hibbitts-design/grav-skeleton-helios-open-reader/refs/heads/main/screenshots/screenshot-2-dark.png">
        <img alt="Section reading page with sidebar navigation and Section N header" src="https://raw.githubusercontent.com/hibbitts-design/grav-skeleton-helios-open-reader/refs/heads/main/screenshots/screenshot-2.png" width="100%">
      </picture>
      </a>
    </td>
  </tr>
  <tr>
    <td align="center">Open Reader – Reader home</td>
    <td align="center">Open Reader – Section reading page</td>
  </tr>
  <tr><td colspan="2">&nbsp;</td></tr>
  <tr>
    <td width="49%">
      <a href="https://raw.githubusercontent.com/hibbitts-design/grav-skeleton-helios-open-reader/refs/heads/main/screenshots/screenshot-admin-1.png">
      <img alt="Admin Panel pages overview showing reader content tree" src="https://raw.githubusercontent.com/hibbitts-design/grav-skeleton-helios-open-reader/refs/heads/main/screenshots/screenshot-admin-1.png" width="100%">
      </a>
    </td>
    <td width="49%">
      <a href="https://raw.githubusercontent.com/hibbitts-design/grav-skeleton-helios-open-reader/refs/heads/main/screenshots/screenshot-admin-2.png">
      <img alt="Admin Panel section page editor with frontmatter fields" src="https://raw.githubusercontent.com/hibbitts-design/grav-skeleton-helios-open-reader/refs/heads/main/screenshots/screenshot-admin-2.png" width="100%">
      </a>
    </td>
  </tr>
  <tr>
    <td align="center">Admin Panel – Pages overview</td>
    <td align="center">Admin Panel – Section page edit</td>
  </tr>
</table>

</div>

A complete, pre-configured package for publishing open textbooks, course readers, and OER publications on the web — a place to openly share reading material that you keep and control. Runs on nearly any web hosting service.

## What Sets It Apart

- **Built for open education from the ground up** — CC license display, OER attribution footer, callout blocks (Learning Objectives, Key Takeaways, Examples, Exercises), and a section structure designed for course reading — not repurposed from a software documentation tool.
- **Readers never lose their place** — Save My Place records the last page visited and surfaces a "Continue reading" strip on return. Most open textbook and reader platforms don't offer this at all.
- **Content you own and can take anywhere** — everything lives as portable Markdown files on your server, fully independent of any platform or service. Switch tools, migrate hosts, or open a pull request — your content travels with you, not with the platform.
- **Embeds cleanly into any LMS** — one URL parameter displays content only, without surrounding navigation; internal links carry it forward automatically. No LTI configuration or institutional integration required.
- **No build pipeline, ever** — edit in the browser-based Admin panel and changes go live immediately. Unlike static site generators for open textbooks, there's nothing to install locally and no commit → push → build → deploy cycle.
- **A CMS and Git, not a choice between them** — most platforms give you one or the other: a browser editor that locks content in a database, or a Git workflow that requires technical setup. Helios Open Reader gives you both: browser-based editing and automatic Git Sync with GitHub or Codeberg.
- **Plain text export for open access** — optionally publish all reader content as structured plain text, portable and format-neutral, ready for search indexing, ebook pipelines, and any tool that can read a URL.

## When is Grav Helios Open Reader a Good Candidate?

Grav Helios Open Reader is a strong fit when you:

- Need a structured reader layout with sections and sub-pages, auto-detected from your folder naming
- Want callout blocks (Learning Objectives, Key Takeaways, Examples, Exercises, Definitions, Reflections, Case Studies) without coding
- Need to embed reader pages directly into an LMS (Canvas, Moodle, Brightspace) as clean iframes, with flexible Table of Contents positioning
- Need rich content embedding (H5P, iFrames, Google Slides, PDFs, Embedly) without coding
- Want dark mode, mobile-friendly design, and keyboard-accessible navigation out of the box

Other publishing tools might be better candidates when you:

- Need packaged export formats (PDF, ePub, DOCX) for offline distribution — browser print-to-PDF works, but no dedicated export pipeline is included
- Need built-in math/LaTeX rendering for STEM content (requires a separate Grav MathJax plugin)
- Need social annotation or inline commenting features (e.g. Hypothesis integration)
- Need zero-server, instant publishing directly from GitHub without any hosting setup
- Prefer a large ecosystem of themes and plugins beyond what Grav currently offers

Still unsure? Install the skeleton package on almost any Web server, add your [Grav Premium Helios theme](https://getgrav.org/premium/helios) license, replace the demo content with your own, and your reader is ready. Your content stays in portable Markdown files you own completely, and those same files work with other tools if your needs change. For zero-setup publishing directly from GitHub or Codeberg without a Web server, [Docsify-This](https://docsify-this.net) is a natural companion.

## Features

Helios Open Reader provides a ready-built open textbook or reader site using portable Markdown files you fully control. Highlights include a configurable sections structure, a full set of callout blocks, Save My Place navigation, and optional Git Sync for open collaborative authoring.

### Reader Structure
- **Sections structure** — top-level folders named `section-N` are auto-detected as sections and render as section cards on the reader home
- **Optional parts grouping** — rename section folders to `part-N-section-M` (e.g. `part-1-section-1`, `part-2-section-1`) to group sections into parts; part headings appear automatically on the reader home, and Prev/Next navigation and reading progress are scoped per part
- **Section N header** — section pages automatically display their section number in the page header; inherits correctly for all sub-pages within a section. The label is configurable (e.g. Chapter, Project, Unit, Module) via **Admin → Pages → Reader Home → Section Label**
- **Section sub-pages** — sections can contain any number of sub-pages, all shown in the sidebar and navigable with Prev/Next controls
- Reader home page with cover image, title, subtitle, authors, edition, and CC license badge

### Callout Blocks
- **Learning Objectives** — `[objectives]...[/objectives]` (green); also available as frontmatter (`learning_objectives:`) for automatic rendering at the top of a section page
- **Key Takeaways** — `[key-takeaways]...[/key-takeaways]` (blue)
- **Example** — `[example]...[/example]` (purple)
- **Exercise** — `[exercise]...[/exercise]` (amber)
- **Definition** — `[definition]...[/definition]` (blue)
- **Reflection** — `[reflection]...[/reflection]` (green)
- **Case Study** — `[case-study]...[/case-study]` (red)
- **Announcement** — `[announcement]...[/announcement]` (purple by default; configurable type)
- **Project Brief** — `[project-brief]...[/project-brief]` (amber); frames the assignment or challenge prompt
- **Feedback Requested** — `[feedback-requested]...[/feedback-requested]` (purple); flags content awaiting review — useful in student projects and draft OER alike
- **Process Note** — `[process-note]...[/process-note]` (blue); documents iterations, decisions, or pivots during a project
- All callouts accept an optional `title="..."` parameter and support Markdown content
- Five built-in GitHub-style callouts via the github-markdown-alerts plugin: `> [!NOTE]`, `> [!TIP]`, `> [!IMPORTANT]`, `> [!WARNING]`, `> [!CAUTION]`

### Navigation & Reading Experience
- **Save My Place** — records the last section page visited in localStorage; a dismissable "Continue reading" strip appears on the reader home page on return
- **Reading progress indicator** — shows current page position (e.g. Page 4 of 22) with an accessible progress bar above the Prev/Next navigation on section pages
- **Prev/Next navigation** — configurable position: top, bottom, or both
- **TOC scroll spy** — active heading highlighted in the Table of Contents as the reader scrolls
- **Start Reading button** — on the reader home; links directly to the first section
- Search across the full reader via the simplesearch plugin

### LMS Embedding

Append `?embedded=true` to any page URL to display only the page content — no sidebar, header, or pagination. Designed for embedding individual Helios Open Reader pages in an LMS iframe (Canvas, Moodle, Brightspace, etc.).

- All internal links automatically carry the `?embedded=true` parameter forward, so navigating between pages stays in embedded mode
- `?chromeless=true` is also supported as an alternative parameter name
- Combine with `?toc_position=hidden` to also hide the Table of Contents
- Combine with `?toc_position=left` or `?toc_position=right` to reposition the Table of Contents to suit surrounding LMS navigation
- Combine with `?edit_link=false` (or `?hidegitlink=true`) to hide the "Edit this Page" link

**Example iframe:**

```html
<iframe src="https://yoursite.com/section-1/introduction?embedded=true" width="100%" height="600" style="border:none;"></iframe>
```

### Authoring & Customization
- Git Sync plugin included for syncing reader content with GitHub, Codeberg, or similar Git hosting
- Automatic "Edit this Page" link via the Helios theme, defaulting to **View Page Markdown** for open access to reader content; optionally configurable to direct editing for contributors with repository access
- OER attribution block — display a CC license statement in the footer, drawn from reader home page frontmatter
- Plain text version (disabled by default) — optionally generate `/llms.txt` (structured index) and `/llms-full.txt` (full content) endpoints for open access to all reader content in a portable, format-neutral form; useful for ebook generation (e.g. Pandoc), search and indexing tools, and AI-compatible tools; a "Plain text version" footer link is included
- Customize CSS and JavaScript via the bundled plugin assets
- Print stylesheet with page break control, absolute link URLs displayed inline, and consistent page margins across browsers

## Quick Start

Helios Open Reader is best suited for authors and educators comfortable with web hosting and folder-based content structure. An online Admin panel is included for browser-based editing – no code editor required.

The skeleton is a **complete package** – Grav CMS, the Helios Open Reader plugin, and demo content are all included; the [Grav Premium Helios theme](https://getgrav.org/premium/helios) requires a separate license. The home page is a reader landing page showing demo sections.

### Pre-flight Checklist
1. Confirm your web server meets [Grav's requirements](https://learn.getgrav.org/17/basics/requirements) (PHP 8.0 or higher)
2. Have your web server login credentials ready (username and password)

### Installation Steps
1. **Download** the [Grav Helios Open Reader Skeleton](https://github.com/hibbitts-design/grav-skeleton-helios-open-reader/releases/latest) package
2. **Unzip** the package onto your desktop
3. **Copy** the entire Grav Helios Open Reader folder to your web server (e.g. into `public_html/` or a subfolder within it)
4. **Open your browser** and go to your site's URL (e.g. `https://yoursite.com/grav-open-reader`)
5. **Create your site administrator account** when prompted
6. **Enter your Helios and SVG Icons license keys** (or import an existing license file), then install and activate the theme
7. **You're done!** – press the preview icon in the Admin Panel to view your site

See [Reader Setup](#reader-setup) to rename folders and edit your pages.

> [!TIP]
> When copying the Grav Helios Open Reader folder to your web server, copy the **entire folder** – it contains hidden files (such as `.htaccess`) that are not selected by default. Omitting these hidden files can cause problems when running Grav.

## Reader Setup

All reader content lives within `user/pages/`. The skeleton ships with a reader home page and three pre-configured demo sections.

```
user/pages/
├── 00.sections/              # Reader home page
│   └── section-list.md           # Reader title, subtitle, authors, edition, license, cover image
├── 01.section-1/           # Section 1 (published by default)
│   ├── section-page.md     # Section settings (section_number, description, icon, learning_objectives)
│   ├── 01.section-one/     # Sub-page (also uses section-page.md)
│   └── 02.section-two/     # Sub-page (also uses section-page.md)
├── 02.section-2/
├── 03.section-3/
└── readme/
```

Rename section folders to match your content, either in the Admin Panel or via FTP. The number prefix on each folder (e.g. `01.section-1/`) controls the order in the sidebar navigation.

> [!TIP]
> After adding, renaming, or removing a section folder, update `versioning.labels` in `user/config/themes/helios.yaml` (or via **Admin → Themes → Helios → Versioning → Version Labels**) to add the new folder name as a key — this sets the section name shown in the sidebar and browser tab title.

### Grouping Sections into Parts

To group sections into parts on the reader home page, use the `part-N-section-M` folder naming pattern instead of `section-N`:

```
user/pages/
├── 00.sections/
├── 01.part-1-section-1/    # Part 1, Section 1
├── 02.part-1-section-2/    # Part 1, Section 2
├── 03.part-2-section-1/    # Part 2, Section 1
├── 04.part-2-section-2/    # Part 2, Section 2
└── readme/
```

Parts are detected automatically — no additional configuration required. Part headings ("Part 1", "Part 2") appear above each group of section cards on the reader home page, Prev/Next navigation stops at part boundaries, and the reading progress indicator counts pages within the current part only.

> [!TIP]
> After switching to the `part-N-section-M` folder naming pattern, update `versioning.labels` in `user/config/themes/helios.yaml` (or via **Admin → Themes → Helios → Versioning → Version Labels**) to add the new folder names as keys — this ensures section labels display correctly in the sidebar and browser tab title.

To use custom part titles instead of the auto-generated "Part 1", "Part 2" labels, add a `parts` block to `section-list.md`:

```yaml
parts:
  - id: part-1
    label: 'Foundations of Open Education'
  - id: part-2
    label: 'Applying Open Practices'
```

### Showing and Hiding Sections

In the Admin panel, open the section folder and set **Published** to **Yes** to show or **No** to hide it. Unpublished sections are also excluded from search results and the sidebar.

Once you have set up your own content, you can safely delete any unused demo sections from `user/pages/` via the Admin panel or FTP.

> [!TIP]
> If changes don't appear immediately after publishing pages or updating settings, clear the Grav cache via the **Clear Cache** button in the Admin panel.

### Adding a New Section

To add a section, copy an existing section folder (e.g. `01.section-1/`) via FTP or the Admin panel (when using the Admin panel, open the section page, click the copy icon, then update the **Page Title** field to a valid new section ID such as `section-4`). Ensure the folder name follows the `section-N` convention, then add the new folder name as a key in `versioning.labels` in `user/config/themes/helios.yaml` (or via **Admin → Themes → Helios → Versioning → Version Labels**). Finally, set **Published** to **Yes** in the Admin panel to make it visible.

> [!TIP]
> After duplicating and renaming a section folder, clear the Grav cache via the **Clear Cache** button in the Admin panel if the new section does not appear immediately.

## Reader Home Settings

The `section-list.md` frontmatter controls the reader identity and card layout on the home page. These fields can be set in the Admin Panel by opening the reader home page.

| Field | Description |
|-------|-------------|
| `title` | Reader title displayed in the header |
| `subtitle` | Optional subtitle shown below the title in italics |
| `authors` | Author name(s) shown below the subtitle |
| `edition` | Optional edition line (e.g. `First Edition, 2025`) |
| `license` | CC license label shown as a badge (e.g. `CC BY 4.0`) |
| `license_url` | URL for the license badge link |
| `attribution_text` | Full attribution statement shown in the footer when OER attribution is enabled |
| `cover_image` | Filename of a cover image uploaded to the reader home media folder |
| `start_button_text` | Label for the button linking to the first section (e.g. `Start Reading`, `Browse Projects`, `View Guides`). Leave empty to hide. |
| `prev_next_position` | Where to display Prev/Next navigation on section pages: `both` (default), `top`, or `bottom` |
| `show_oer_attribution` | Display the CC license and attribution text in the footer of every page (`true` or `false`) |
| `section_label` | Label used for sections throughout the reader (e.g. `Chapter`, `Unit`). Leave empty to use the language default (`Section`). |
| `part_label` | Label used for part headings on the reader home page when using the `part-N-section-M` folder naming pattern (e.g. `Theme`, `Project`). Leave empty to use the default (`Part`). |
| `parts` | Optional list of custom part titles — see [Grouping Sections into Parts](#grouping-sections-into-parts) |
| `cards_per_row` | Number of section cards per row (1–3) |
| `card_icon` | Default icon for all cards (Tabler icon path) |
| `card_image_layout` | Card image position: `side` or `top` |
| `card_description_lines` | Maximum description lines per card (2, 3, or 0 for no limit) |

Page content written in `section-list.md` appears above the cards by default. To also display content **below** the cards, add `===` on its own line as a delimiter:

```markdown
This text appears above the section cards.

===

This text appears below the section cards.
```

## Section Page Settings

The `section-page.md` frontmatter controls each section's landing page and card appearance.

| Field | Description |
|-------|-------------|
| `section_number` | Section number shown in the page header; inherits to all sub-pages within the section |
| `description` | Description shown on the section card |
| `icon` | Tabler icon path for the section card |
| `image` | Filename of a card image uploaded to this page's media folder |
| `author` | Author name(s) shown on the section card |
| `learning_objectives` | Markdown list rendered as a Learning Objectives block at the top of the page |
| `badge_label` | Optional status badge label (e.g. `New`, `Draft`) |
| `badge_color` | Optional badge colour (`blue`, `green`, `yellow`, `red`, `purple`, `plain`) |

```yaml
---
title: What is Open Education?
section_number: 1
icon: tabler/school.svg
image: section-cover.jpg
author: Jane Smith
description: An introduction to open education principles and the 5Rs framework.
badge_label: New
badge_color: green
learning_objectives: |
  - Define open education and explain its core principles
  - Identify the 5Rs of open educational resources
---
```

## Label Customization

### Reader Title

The reader title displayed in the browser tab and header comes from the `title` field in `section-list.md`. Edit it via **Admin → Pages → Reader Home**, or directly in `user/pages/00.sections/section-list.md`.

### Section Names

The individual section name shown in the sidebar, in the section dropdown (when enabled), and as the middle segment of the browser tab title (`Page Title | Reader Title | Site Title`) comes from the `versioning.labels` setting in the Helios Theme config. These can be edited via **Admin → Themes → Helios → Versioning tab → Version Labels**, or directly in `user/config/themes/helios.yaml`:

```yaml
versioning:
  labels:
    section-1: 'What is Open Education?'
    section-2: 'Tools for Open Course Design'
    section-3: 'Getting Started with Open Authoring'
```

### Section Label

The section label used throughout the reader (in page headers, cards, and the sidebar) can be set via **Admin → Pages → Reader Home → Section Label**. Leave it empty to use the language default.

```yaml
en:
  PLUGIN_HELIOS_OPEN_READER:
    SECTION_LABEL: Section
    SECTION_LATEST_LABEL: latest

fr:
  PLUGIN_HELIOS_OPEN_READER:
    SECTION_LABEL: Chapitre
    SECTION_LATEST_LABEL: dernière
```

To customize the label or add a language, update the relevant block in `user/plugins/helios-open-reader/languages.yaml`.

### Part Label

When sections are grouped into parts using the `part-N-section-M` folder naming pattern, the part heading label (default: `Part`) can be customized via **Admin → Pages → Reader Home → Part Label**. Leave it empty to use the default. Examples: `Theme`, `Project`.

## Browser Tab Title

The browser tab title is automatically formatted as:

`Page Title | Reader Title | Site Title`

The Reader Title is drawn from the reader home page title. The Site Title comes from `site.title` in `user/config/site.yaml`. Set the Site Title to your institution or author name — it serves as the top-level identifier in the browser tab.

## Git Sync & Open Editing

The skeleton includes the [Git Sync plugin](https://github.com/trilbymedia/grav-plugin-git-sync), which keeps your site content automatically in sync with a GitHub or Codeberg repository. This enables a full open-authoring workflow:

- Content editors can work directly in the Grav Admin or commit changes via Git
- The Helios Theme's **"Edit this Page"** option defaults to a 'View Page Markdown' link on each page, taking readers directly to the Markdown source file in your repository (configurable to link directly to file editing via the Helios Open Reader plugin settings)

If you prefer not to write Markdown directly, the optional [Grav Premium Editor Pro](https://getgrav.org/premium/editor-pro) provides a visual block editor for editing pages.

## Included Plugin: Helios Open Reader

Custom CSS, JavaScript, shortcodes, callout blocks, and Helios-inspired Admin Panel styling for the Helios Open Reader skeleton. If the Helios theme is not installed, the plugin automatically falls back to the Quark or Quark2 theme so the frontend site remains viewable, redirecting to the License Manager page in the Admin panel.

### Plugin Settings

The following settings are available in the Admin panel under **Plugins → Helios Open Reader**:

| Setting | Default | Description |
|---------|---------|-------------|
| Helios-inspired Admin Styling | Enabled | Apply Helios-inspired styling enhancements to the Admin Panel (rounded corners, transitions, improved typography) |
| Admin Font Size (Admin 1.7 only) | Large | Sets the Admin Panel font size: Default, Large, or Larger |
| Show Site Logo Icon | Enabled | Show or hide the icon square next to the Logo Text in the header when no logo image is set |
| Site Logo Icon | `tabler/notebook.svg` | Tabler icon path for the site logo icon square. Only applies when Show Site Logo Icon is enabled |
| Show Plugin Credits | Enabled | Show or hide the "Built with Grav · Helios · Helios Open Reader" attribution line in the footer |
| Show Repository Host Icon Link in Header | Enabled | Show a GitHub or Codeberg icon link to the reader repository in the site header (requires GitHub Integration enabled in the Helios theme) |
| Git Link Icon | `tabler/file-text.svg` | Tabler icon path for the Git link icon shown in the page footer |
| Git Link Mode | View file | Whether the Git link opens the file for **viewing** (default, for open access) or **editing** (for contributors with repository access) |
| Repository Host | `github.com` | Repository hosting service for the Helios GitHub Integration (`github.com` or `codeberg.org`) |
| H5P Content Embed Source URL | `https://h5p.org/h5p/embed/` | Base URL for H5P embeds via Content ID (used with `[h5p id="..."]`) |
| Enable Plain Text Version | Disabled | Generate `/llms.txt` (structured index) and `/llms-full.txt` (full content) endpoints containing all reader content in plain text |
| Show Plain Text Version Link in Footer | Enabled | Show a link to `/llms-full.txt` in the page footer. Only applies when Enable Plain Text Version is enabled |
| Plain Text Version Link Label | `Plain text version` | Label for the plain text version footer link |
| Plain Text Version Link Icon | `tabler/book.svg` | Tabler icon path shown before the plain text version link label. Leave empty for no icon |
| Image URLs in Plain Text Version | `Absolute URLs` | Controls how images appear in the plain text version: **Absolute URLs** (recommended — makes images accessible to AI tools), **Suppress images** (text-only output), or **Relative paths** (not recommended for remote LLM use) |
| Include Page Templates | `section-page` | Only pages using these templates appear in the plain text version |

> **Note:** To apply the Helios-inspired Admin Panel 1.7 colour scheme (zinc nav, accessible blue links, muted purple accents), go to **Admin → Customization → Presets**, select **Helios**, and click **Save**.
### Templates
- **section-list** – Reader home template displaying the reader header, resume reading strip, and section card grid
- **section-page** – Section reading page with configurable section N header, optional Learning Objectives block from frontmatter, and main content
- **default-toc** – Content page with a right-column Table of Contents; set `template: default-toc` in any page's frontmatter to enable (requires the page-toc plugin, included)

> [!TIP]
> The `default-toc` template is ideal for standalone content-heavy pages such as a preface, bibliography, or about page that benefit from in-page navigation but don't need the section structure.

### Assets
- **helios.css** – Theme styling (announcement blockquotes, heading typography, Font Awesome spacing, responsive containers)
- **reader.css** – Reader-specific styles (callout blocks spacing, resume reading strip, reading progress indicator, top Prev/Next navigation styling)
- **helios.js** – Embedly dark/light theme support, Save My Place localStorage logic, HTMX content-loaded integration
- **print.css** – Print stylesheet (hides navigation chrome, resets colors for light and dark themes, controls page breaks, displays absolute link URLs, sets consistent page margins)
- **admin.css** – Helios-inspired Admin Panel styling (conditionally loaded based on the Helios-inspired Admin Styling setting)
- **admin.js** – Admin panel JavaScript customizations

### Shortcodes

#### Callout Blocks

All callouts accept an optional `title="..."` parameter and support Markdown content.

- `[objectives]...[/objectives]` – Learning Objectives block (green)
- `[objectives title="By the end of this section..."]...[/objectives]` – With custom title
- `[key-takeaways]...[/key-takeaways]` – Key Takeaways block (blue)
- `[example]...[/example]` – Example block (purple)
- `[exercise]...[/exercise]` – Exercise block (amber)
- `[definition]...[/definition]` – Definition block (blue)
- `[reflection]...[/reflection]` – Reflection block (green)
- `[case-study]...[/case-study]` – Case Study block (red)
- `[announcement]...[/announcement]` – Announcement notice (purple by default), supports Markdown
- `[announcement title="..." type="..."]...[/announcement]` – With optional custom title and type (`note`, `tip`, `important`, `warning`, `caution`)
- `[project-brief]...[/project-brief]` – Project Brief block (amber); frames the assignment or challenge prompt
- `[feedback-requested]...[/feedback-requested]` – Feedback Requested block (purple); flags content awaiting review — useful in student projects and draft OER alike
- `[process-note]...[/process-note]` – Process Note block (blue); documents iterations, decisions, or pivots during a project

> [!TIP]
> For simple notices, the standard Markdown callout `> [!IMPORTANT]` is a zero-friction alternative to the `[announcement]` shortcode.

#### Embedding

- `[iframe url="..."]` – Responsive iframe embed, 16:9 by default
- `[iframe url="..." ratio="4:3"]` – Responsive iframe embed at 4:3 ratio
- `[iframe url="..." title="..."]` – Responsive iframe embed with accessible title (recommended for accessibility)
- `[googleslides url="..."]` – Responsive Google Slides embed, 16:9 by default
- `[googleslides url="..." ratio="4:3"]` – Responsive Google Slides embed at 4:3 ratio
- `[googleslides url="..." title="..."]` – Responsive Google Slides embed with accessible title (recommended for accessibility)
- `[pdf url="..."]` – PDF viewer via Google Docs, 16:9 by default
- `[pdf url="..." ratio="4:3"]` – PDF viewer at 4:3 ratio
- `[pdf url="..." ratio="portrait"]` – PDF viewer at portrait ratio (letter/A4)
- `[pdf url="..." title="..."]` – PDF viewer with accessible title (recommended for accessibility)
- `[h5p url="..."]` – H5P interactive content via full embed URL
- `[h5p id="..."]` – H5P interactive content via Content ID (requires H5P Content Embed Source URL to be set in plugin settings)
- `[h5p url="..." title="..."]` – H5P embed with accessible title (recommended for accessibility)
- `[embedly url="..."]` – Embedly card with dark mode support

## Requirements

- PHP >= 8.0
- Grav CMS >= 1.7.0
- [Grav Premium Helios Theme](https://getgrav.org/premium/helios) – one license per site ([Standard or Team](https://getgrav.org/premium/license))

## Support

### Contact and Support
- Follow [@hibbittsdesign@mastodon.social](https://mastodon.social/@hibbittsdesign) on Mastodon for updates
- 👩🏻‍💻🧑🏻‍💻 Join the [Grav Discord](https://chat.getgrav.org) and often find me there
- Add a ⭐️ [star on GitHub](https://github.com/hibbitts-design/grav-skeleton-helios-open-reader) to the Helios Open Reader project repository
- For bugs or feature requests, [open an issue](https://github.com/hibbitts-design/grav-plugin-helios-open-reader/issues) on GitHub

### Professional Services

By leveraging his extensive UX design expertise and systems-oriented approach, Paul helps teams and individuals utilize open content in education and publication settings. Professional services include user experience and workflow consulting, premium support subscriptions, workshops, and custom development. Interested? Send a note to [paul@hibbittsdesign.org](mailto:paul@hibbittsdesign.org).

## License

MIT – Hibbitts Design
