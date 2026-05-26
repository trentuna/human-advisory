# Launch Strategy — human-advisory

## Goal

Make the Human Advisory badge visible, discoverable, and easy to adopt so it spreads across the web as a convention for flagging AI-generated content.

## Target audience

- Open-source maintainers who want to label AI-generated code in their repos
- Web developers building AI-assisted projects who want transparent disclosure
- Bloggers / newsletter writers writing about AI
- Designers who want a recognizable warning badge for AI-generated UI

## Channels

### 1. GitHub
- **Tags:** `css-badge`, `ai-disclosure`, `warning-label`, `parental-advisory`, `explicit-ai-content`
- **Topics on repo:** `css`, `badge`, `ai`, `disclosure`, `warning`, `parental-advisory`, `web-component`
- **Pin a demo gif** in the README showing the badge on different backgrounds
- **Submit to:** [awesome-badges](https://github.com/awesome-badges), [awesome-css](https://github.com/awesome-css), CSS-Tricks (if they still accept tips)

### 2. Social / dev communities
- **Hacker News** — Show HN post: "Show HN: Human Advisory – A CSS badge for AI-generated code"
  - Best time: weekday morning US time
  - Title should explain what it is, not what it's made of: "Show HN: Human Advisory – the 'Explicit Content' sticker for AI code"
- **Lobsters** — same post, community is more design-aware
- **Reddit:** r/webdev, r/css, r/programming, r/MachineLearning
  - Add custom flair per subreddit rules
- **X/Twitter** — share demo GIF + embed snippet with #HumanAdvisory #AIDisclosure #CSS

### 3. Direct outreach
- **AI disclosure advocates** — tweet at or DM people pushing for AI labeling (e.g., @emilymbender, @simonw, @kelseyhightower)
- **Newsletters** — CSS Weekly, Frontend Focus, JavaScript Weekly (submit as open-source project spotlight)

### 4. Embed in Trentuna ecosystem
- Already used on `trentuna.com` as a live demo
- Add to garden catalog entry for the badge
- Reference from the garden homepage as a featured project

## Pitch lines

> "A pure-CSS 'Explicit Content' sticker for AI-generated code. Drop it anywhere. No JS, no build tools."

> "Your users deserve to know when they're reading machine-generated work. This badge makes it visible."

> "The Parental Advisory label was invented in 1996. AI needs its own warning sign."

## Viral hooks

- **Low friction** — literally 3 lines of HTML + 1 CSS link to use
- **Nostalgia** — everyone recognizes the RIAA sticker
- **Timely** — AI disclosure is an active debate (EU AI Act, GitHub Copilot labeling)
- **Customizable** — change the text to "AI GENERATED", "SYNTHETIC", "TRAINED ON", etc.

## Future milestones

| Phase | Description |
|-------|-------------|
| v1.0  | Pure CSS badge + variants (current) |
| v1.1  | npm package + unpkg CDN link |
| v1.2  | Web Component (`<human-advisory>`) |
| v2.0  | JS binding for dynamic text + themes |
| v2.1  | premium theme pack (neon, terminal, retro) |

## Metrics to track

- GitHub stars and forks
- npm downloads (when published)
- Number of repos using the badge (GitHub search: "human-advisory.css")
- Social mentions (#HumanAdvisory)
- Feedback / issues from real users
