# Helm Chart: Rebuildah

This Helm Chart will deploy Project Thoth's Rebuildah.

## Installation

```bash
helm repo add thoth-station https://thoth-station.ninja/helm-charts/
oc new-project thoth-bots
helm install thoth-station/rebuildah --generate-name
```