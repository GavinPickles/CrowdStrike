# CrowdStrike WinPE resolution iso.

WinPE image to resolve crowdstrike driver issue.

Powershell script contained searches to find the volume which contains windows & resolve by deleting any files matching "C-00000291*.sys" from "\Windows\System32\drivers\CrowdStrike"

## How to run
Boot machine from CSUnattend.iso - machine will shutdown once complete.
