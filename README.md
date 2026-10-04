# yBorg Beedle shadow audit

The original Beedle source from the July 24–August 7, 2023 Cyfrin CodeHawks contest, packaged for yBorg participants to calibrate, benchmark, regression-test, and improve their auditing tools.

## Get started

Install Foundry, then:

```sh
git clone https://github.com/yAudit/yborg-beedle-shadow-audit.git
cd yborg-beedle-shadow-audit
forge build
```

Compatible dependencies are included and pinned. No additional dependency installation is required. Foundry downloads Solidity 0.8.19 on the first build, so initial compilation needs internet access.

## Scope

All nine Solidity files under `src/` are in the original contest scope. Contracts, tests, and deployment scripts are unchanged from contest-setup commit `658e046bda8b010a5b82d2d85e824f3823602d27`. `test/` and `script/` provide the original supporting context.

The dependency source under `lib/` is supporting code outside the contest scope. Foundry configuration is adjusted to select the compiler and resolve the included dependencies. [SOURCES.json](SOURCES.json) records exact source and dependency revisions and checksums. [The original contest README](docs/contest-README.md) provides protocol context.

## Licenses

Original license notices are retained in the source files. Each included dependency retains its upstream license in its directory under `lib/`.
