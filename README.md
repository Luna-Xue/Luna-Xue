## Projects
- [isac-toolbox](https://github.com/Luna-Xue/isac-toolbox) — ISAC signals, datasets, and scripts
- [oran-xapps](https://github.com/Luna-Xue/oran-xapps) — RIC xApps/rApps for AI/ORAN
- [mmwave-sensing](https://github.com/Luna-Xue/mmwave-sensing) — mmWave respiration & UAV demos
- [pls-labs](https://github.com/Luna-Xue/pls-labs) — Physical-layer security experiments

name: Full-year calendar
uses: lowlighter/metrics@latest
with:
  filename: metrics.plugin.isocalendar.fullyear.svg
  token: ${{ secrets.METRICS_TOKEN }}
  base: ""
  plugin_isocalendar: yes
  plugin_isocalendar_duration: full-year

