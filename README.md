# ath79-ex7300-openwrt-builder
Automated builds of ath79 OpenWRT repository using GitHub Actions

- robimarko's fork is pulled daily and if last commit is less than a day old a new build is triggered.
- Manual build can also be triggered.
- Build artifacts are stored as releases.
- Build options are embedded in [ath79_generic.yaml](/.github/workflows/ath79_generic.yaml) file.
