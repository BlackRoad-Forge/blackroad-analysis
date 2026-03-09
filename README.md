# BlackRoad Analysis

Internal analysis repository — documentation, deployment scripts, infrastructure reports, and operational data for the BlackRoad OS ecosystem.

## Contents

### Data (`data/`)

JSON indexes of all GitHub organizations, Cloudflare Pages mappings, Railway projects, product analyses, and infrastructure inventories.

### Documentation (`docs/`)

400+ operational documents covering:

- Infrastructure status reports and network maps
- Deployment guides and runbooks
- Product architecture docs
- Brand system specifications
- Cluster setup and recovery procedures
- Session summaries and progress reports

### Scripts (`scripts/`)

400+ shell scripts for:

- **Deployment** — batch deploy to Cloudflare Pages, Railway, Pi cluster
- **Infrastructure** — network scanning, device discovery, DNS management
- **GitHub** — repo enhancement, workflow deployment, PR management
- **Memory** — Lucidia memory system daemons and tools
- **Monitoring** — status dashboards, health checks, compliance
- **Visuals** — terminal animations (mandelbrot, galaxy, quantum simulations)

## Usage

```bash
# Deploy all domains
./scripts/deploy-all-domains.sh

# Network scan
./scripts/blackroad-network-scan.sh

# Status dashboard
./scripts/status-dashboard.sh

# Memory system
./scripts/memory-system.sh
```

## License

Copyright 2026 BlackRoad OS, Inc. All rights reserved.
