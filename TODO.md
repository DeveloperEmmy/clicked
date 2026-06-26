- [x] Add contracts/test_snapshots/ to contracts/.gitignore (already present)
- [x] Update .github/workflows/contracts-ci.yml to add a hygiene check after cargo test (fail if any contracts/**/test_snapshots/*.json exists)


- [x] Remove any existing test snapshot files from the repo (if present) (none found)
- [x] Run contracts cargo tests locally to verify no snapshots are produced (not run due to missing cargo in environment)



