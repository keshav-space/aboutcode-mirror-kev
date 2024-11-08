# WAT

Mirroring https://www.cisa.gov/sites/default/files/feeds/known_exploited_vulnerabilities.json since CISA restricts access and applies rate limits.

Updated every midnight - see [.github/workflows/update.yaml](.github/workflows/update.yaml)

# Usage

Consume it via `https://raw.githubusercontent.com/EugenMayer/cisa-known-exploited-mirror/main/known_exploited_vulnerabilities.json`

For gradle it would look like

```groovy

dependencyCheck {
    analyzers {
        knownExploitedURL = "https://raw.githubusercontent.com/EugenMayer/cisa-known-exploited-mirror/main/known_exploited_vulnerabilities.json"
    }
}
```

# License

You can use it without any charge but also without any warranty. It's yours in all the aspects, risk and benefits.

