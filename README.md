# OmniHub

Collection of interactive utilities and tools.

## AWS Dynamic Flowchart

Interactive architecture diagram generator for AWS services.

- Enter service short forms (EC2, S3, Lambda, RDS, ALB, VPC, IAM, etc.)
- Instant Mermaid flowchart with logical layering and connections
- Dark editorial theme
- Preset patterns (3-Tier, Serverless, Event-Driven, Data Lake…)
- Ready-to-embed iframe code

**Live file:** [aws-flowchart.html](./aws-flowchart.html)

### Quick start

1. Open `aws-flowchart.html` in a browser or host it (GitHub Pages recommended).
2. Type services or click a preset.
3. Copy the Mermaid source or use the iframe snippet.

### Enable GitHub Pages (recommended)

1. Go to repo **Settings → Pages**
2. Source: Deploy from branch `main` / root
3. Your live URL will be:  
   `https://allanvarghese567-lab.github.io/omnihub/aws-flowchart.html`

Then use this iframe anywhere:

```html
<iframe
  src="https://allanvarghese567-lab.github.io/omnihub/aws-flowchart.html"
  width="100%"
  height="720"
  style="border:1px solid #27272a;border-radius:8px;background:#0a0a0b;"
  title="OmniHub AWS Dynamic Flowchart"
  loading="lazy">
</iframe>
```
