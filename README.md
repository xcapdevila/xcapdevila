# Hi, I'm Xavier Capdevila

Software architect and engineering leader focused on payments, security and distributed systems.

This is where I share personal tools, reproducible labs and open-source contributions.

## Selected projects

- **[openssl-fips](https://github.com/xcapdevila/openssl-fips)** — Configurable Docker builds with independently selected OpenSSL and FIPS provider versions. Includes verified source downloads and automated checks for FIPS-backed random generation.
- **[resilience4j-lab](https://github.com/xcapdevila/resilience4j-lab)** — Compare standard and gradual circuit-breaker recovery under simulated failures, with traffic controls and local Prometheus/Grafana dashboards.

## Contributing to Resilience4j

I'm proposing optional gradual traffic admission during `HALF_OPEN` recovery:

```text
OPEN → HALF_OPEN (25% → 50% → 75% → 100%) → CLOSED
```

The policy adds configurable recovery steps and health gates, with optional `STEP_BACK`, while keeping standard CircuitBreaker recovery as the default.

[Proposal](https://github.com/resilience4j/resilience4j/issues/2576) · [Implementation PR](https://github.com/resilience4j/resilience4j/pull/2577) · [My fork](https://github.com/xcapdevila/resilience4j/tree/contribution/issue-2576-gradual-half-open-recovery)

The proposal is open for community discussion and review.

## Connect

[Personal website](https://xcapdevila.github.io/) · [LinkedIn](https://www.linkedin.com/in/xcapdevila/)
