# Windows Event Log Investigation
This project presents a SOC investigation into Windows Event Logs from a workstation system.

## Overview
The dataset contains over 8,000 Windows event logs extracted from an EVTX file and converted to CSV.

The goal of the investigation was to analyze system activity and detect potential security issues.

## Key Findings
- Security log clearing activity detected (Event ID 1102)
- System startup events observed (Event ID 4608)
- Service installation detected (Event ID 7045)
- Network communication with legitimate Microsoft infrastructure

## Tools Used
- EvtxECmd
- Microsoft Excel
- Windows Event Log Analysis

## Dataset Files
- `full_timeline.csv` – timeline of events
- `id_counts.csv` – event ID frequency analysis
- `report.pdf` – full investigation report
