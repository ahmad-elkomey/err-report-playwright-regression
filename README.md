# Minimal Source To Reproduce Regression

The source here is generated by running:

```shell
npm init playwright@latest --yes -- --quiet --browser=chromium --browser=firefox --browser=webkit --gha --install-deps playwright-intro
```

System:

- Linux komey-dell 5.15.0-118-generic #128-Ubuntu SMP Fri Jul 5 09:28:59 UTC 2024 x86_64 x86_64 x86_64 GNU/Linux
- npm 10.8.2
- node v22.6.0
- playwright 1.46.0
- VS Code 1.92.1 eaa41d57266683296de7d118f574d0c2652e1fc4 x64
- Playwright VS Code Extension 1.1.7

Issue: https://github.com/microsoft/playwright/issues/32183
