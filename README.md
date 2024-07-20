CrowdControl
===
<p align="center">
  <img width="256" height="256" src="icon.jpg">
</p>

A basic DuckyScript that allows a Flipper Zero (or any BadUSB device) to leverage CrowdStrike's [workaround steps for individual hosts](https://www.crowdstrike.com/blog/statement-on-falcon-content-update-for-windows-hosts/) and:
* Remove CrowdStrike C-00000291*.sys channel files from Windows host machines operating in Safe Mode and logged in as an Administrator,
* Remove the safeboot boot variable (if set during previous troubleshooting attempts),
* Reboot in normal mode after verifying the files have been removed.

More information regarding remediation steps can be found on [CrowdStrike's Blog](https://www.crowdstrike.com/blog/our-statement-on-todays-outage/).
