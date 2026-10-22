# CI Failure Lab

A sandbox repo for our quarterly hands-on session where new engineers practice triaging a broken CI build: opening a failed run, locating the `boom` marker in the logs, and re-running only the failed jobs. The `Broken Build Lab` workflow in `.github/workflows/broken-build.yml` is intentionally broken and always fails — that is the point of the lab. Trainee instructions are in [TRIAGE.md](TRIAGE.md).

## Further reading

Real-world workflow files that use the `if: failure()` conditional pattern:

- [yallcode/YallEXE](https://github.com/yallcode/YallEXE) — `.GitHub/workflows/build-mac.yml`
- [yallcode/YallEXE](https://github.com/yallcode/YallEXE) — `.GitHub/workflows/build-windows.yml`
- [RickCreator87/richards-credit-authority](https://github.com/RickCreator87/richards-credit-authority) — `.GitHub/Workflows/Security-scan.yaml`
