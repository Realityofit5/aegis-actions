# Aegis Actions

Free AI compute via GitHub Actions. Part of the Aegis AI operator system.

## Workflows

| Workflow | Trigger | What it does |
|----------|---------|-------------|
| **AI Inference** | Manual + Daily 6AM | Runs any prompt through local AI models on GitHub's free machines |
| **OSINT Scan** | Manual | Full reconnaissance on any domain — DNS, WHOIS, SSL, subdomains, Shodan, AI analysis |
| **Security Audit** | Manual + Weekly Monday | Dependency audit, code scanning, port checks, AI threat assessment |

## Usage

Go to **Actions** tab > select a workflow > click **Run workflow** > fill in inputs > wait for results > download artifacts.

## Integration with Aegis

Results flow back to your local Aegis AI system for correlation and persistent storage.
