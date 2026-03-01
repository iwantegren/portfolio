# Personal Domain Technical & Design Specification

**Role:** Full-Stack Software Engineer & Strategic Technical Co-Founder
**Vibe:** Premium, Professional, Minimalist, High-Performance

## 1. Global Site Description & Shared UI/UX Theme

The site must feel like the digital headquarters of a senior builder and technical co-founder. It should prioritize readability, fast loading, and immediate visual hierarchy.

- **Content Instruction:** ALL body text, paragraphs, and descriptions must be mocked using **Lorem ipsum**. Only headers, button labels, and specific technical keywords should use real text.
- **Color Palette:** \* Background: Deep charcoal or off-black (e.g., `#0f1115`) for a modern, sleek developer feel, or a very crisp, clean off-white (e.g., `#f8f9fa`) if a light theme is preferred.
  - Primary Accent: A sharp, energetic color (like electric blue, vibrant teal, or a striking orange) to highlight primary CTAs and active states.
  - Text: High-contrast but soft on the eyes (e.g., `#e2e8f0` for dark mode, `#333333` for light mode).
- **Typography:** \* Headings: A geometric, bold sans-serif (e.g., Inter, Plus Jakarta Sans, or Space Grotesk) to convey modern tech authority.
  - Body: A highly readable, clean sans-serif (e.g., Roboto or system-ui).
  - Code/Tech Stack elements: A clean monospace font (e.g., Fira Code or JetBrains Mono).
- **Layout Rules:** \* Consistent max-width container (e.g., 1200px) centered on the page.
  - Ample whitespace (padding/margins) between vertical sections to let the content breathe.
  - Subtle hover states on all interactive elements (buttons scaling up slightly, text links changing color).

---

## 2. Page Specifications

### Page 1: Home Page (`index.html`)

**Goal/Vision:** The "Builder's Narrative." Sell the vision, the execution, and the mindset, but provide an immediate escape hatch for recruiters needing hard stats.

**Layout & Components (Stacked Vertically):**

1.  **Hero Section:** \* _Layout:_ Full viewport height (or min 80vh). Two-column on desktop (text left, visual right), stacked on mobile.
    - _Text Elements:_ Massive Headline ("Strategic Technical Co-Founder & Full-Stack Engineer"). Subheadline indicating expertise in scalable Node.js architectures and product strategy.
    - _CTAs (Crucial):_ \* Primary Button: "View My Product" (Points to product landing page).
      - Secondary/Ghost Button (Placed right next to primary): "Quick Resume" (Points to `resume.html`).
    - _Visual:_ Placeholder for a premium photo or a stylized custom mascot (e.g., a hybrid cat-octopus or fitness pigeon).
2.  **Shipped Work & Open Source Spotlight:** \*
    - _Main Layout (The Product):_ A distinct, visually elevated full-width card or split-banner for your main E-commerce Sandbox project. Includes the logo, mocked description, and primary "Explore Project ->" CTA.
    - _Sub-Layout (The NPM Packages):_ Directly beneath the main project card, place a compact, multi-column grid (e.g., 2 or 3 small cards).
    - _Content per Package:_ The package name (styled like inline code, e.g., `@your-scope/package-name`).
      - A one-sentence mocked description of the problem it solves.
      - A clean, minimal text link or icon pointing to the npm registry or GitHub repo.
    - _Vibe:_ Unobtrusive but highly visible to technical eyes. It whispers "I don't just build apps, I build tools for other developers."
3.  **About Me & Philosophy:**
    - _Layout:_ 60/40 split.
    - _Content:_ The text should be mocked, but structurally support a narrative that bridges physical discipline/functional training (HIIT/CrossFit) with high-cognitive engineering and clean code architecture.
4.  **Articles / Thought Leadership:**
    - _Layout:_ A minimal, elegant section with 2-3 text cards representing recent Medium articles.
    - _CTA:_ "Read more on Medium" (External link).
5.  **Case Studies Hook (The Deep Dive):**
    - _Layout:_ A prominent, darker/contrasting block at the bottom.
    - _Text:_ "Want to see how I solve complex backend and architectural challenges?"
    - _CTA:_ "Deep Dive into Case Studies" (Points to `case-studies.html`).
6.  **Global Footer:** Simple links to GitHub, LinkedIn, Email, and the Resume.

---

### Page 2: The Resume Page (`resume.html`)

**Goal/Vision:** The "Direct Authority." Pure signal, zero noise. For recruiters and technical leads to scan hard skills and experience.

**Layout & Components:**

1.  **Header/Top Bar:** Compact, with a clear "Back to Home" link and a highly visible "Download PDF Resume" primary button.
2.  **Tech Stack Matrix (Scannable):**
    - _Layout:_ Grid or tag-based layout.
    - _Categories:_ Backend (Node.js, PostgreSQL), Frontend (React, TypeScript, Remix), Mobile (Flutter), Architecture/Tools (Shopify, AWS/GCP).
3.  **Experience Timeline:**
    - _Layout:_ A clean vertical line on the left, with experience nodes on the right.
    - _Content:_ Job Title, Date, and 3 bullet points per role (mocked with Lorem Ipsum).
4.  **Technical Proof CTA:**
    - _Layout:_ At the end of the timeline, a prominent section catching the reader before they leave.
    - _Text:_ "Proof in action: See how I apply this stack to complex problems."
    - _CTA:_ "View Case Studies" (Points to `case-studies.html`).

---

### Page 3: Case Studies Page (`case-studies.html`)

**Goal/Vision:** The "Engineer's Proof." Product-agnostic deep dives into architectural challenges, trade-offs, and solutions.

**Layout & Components:**

1.  **Page Header:** "Engineering Case Studies" with a brief subtext explaining that specifics are abstracted due to NDAs, focusing entirely on technical problem-solving.
2.  **Case Study Blocks (2-3 items):**
    - _Layout:_ Alternating left/right image-and-text blocks, or expansive dropdown accordions to keep the initial view clean.
    - _Structure per Study:_
      - **The Problem:** (Mocked text).
      - **The Constraints:** (Mocked text).
      - **The Solution & Architecture:** (Mocked text, with placeholders for code snippets or diagram images).
3.  **Bottom Navigation/CTA:**
    - _Layout:_ Split buttons.
    - _CTAs:_ "Back to Resume" and "Back to Home".
