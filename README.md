# portfolio

Static portfolio site. Eight HTML files, one stylesheet, four diagram files, no build step, no JavaScript.

```
index.html            landing page: positioning, about, five case studies
homelab.html          case study: multi-arch K3s, Ansible provisioning, Flux GitOps
architecture.html     the four layers: infrastructure, delivery, agent runtime, work process
agent-harness.html    case study: agent fleet, kanban dispatch, verification ladder
media-pipeline.html   case study: render service + n8n orchestration
deal-finder.html      case study: weekly store digest, deal store, Discord threads
small-projects.html   four small tools in one repository
404.html              not found
styles.css            single stylesheet, paper palette
arch/*.svg            layer diagrams (generalised: no hostnames, addresses or paths)
.nojekyll             serve files as-is on GitHub Pages
```

## Publish

The site is published from `Bittisorvi/Bittisorvi.github.io`, so it serves at
`https://bittisorvi.github.io/`. Pages: *Deploy from a branch* → `main` / `(root)`.

## Rules

- Fresh history. Nothing imported from the private repos.
- No internal hostnames, LAN addresses, registry paths or app inventories.
- Every number on a page must be counted from a real source, never estimated.
- Static only: no framework, no build step, no client-side JS.
