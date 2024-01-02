# Proactive.NOSC.Daily.Tasks v1.0.5.0

Download [here](https://github.com/theKevinJustin/ProactiveNOSCDailyTasks/blob/main/Proactive.NOSC.Daily.Tasks.xml)

### Proactive NOSC Daily Tasks
Management pack provides summary report alerts of key insights including:
Expiring certificates, Logical Disk alerts, Pending reboots, System Admin summary, and SCOM admin reports including long-running scripts, script errors, SCOM errors, and alert updates report.

Blog [https://kevinjustin.com/blog/2023/08/15/proactive-daily-reports/](https://kevinjustin.com/blog/2023/08/15/proactive-daily-reports/)

# Change History
```
v1.0.5.0   4 Jan 2024 Resolution State logic improvements for large environments
v1.0.4.9  21 Dec 2023 WhiteSpace, newline, return updates, Expiring Certs report moved back 1 hour
v1.0.4.8  20 Dec 2023 Updated all Get-SCOMAlert queries to use -ResolutionState (0..254) for performance increase over where-object
v1.0.4.7  18 Dec 2023 Updated Expiring Certs DS/WA, whitespace code check
v1.0.4.6  30 Nov 2023 Removed debug detail from DS/WA which showed in Health Explorer pane
v1.0.4.4  18 Jul 2023 Updated reports to informational
v1.0.4.3  10 Feb 2023 Disabled AlertUpdates and ATQ ticket automation, updated ExpiringCertificates report
v1.0.3.4   8 Jun 2022 Updated AlertUpdatesReport
v1.0.3.3   7 Jun 2022 Updated DailySummary, AlertUpdates, agent issues
v1.0.2.8  18 May 2022 Updated closure logic for AlertUpdates,ScriptErrors,Longrunning reports, updated runtimes
v1.0.2.6  20 Apr 2022 New AlertUpdates module updating ticketID,Owner,ResolutionState for new alerts (runs M-F daily)
v1.0.2.4  15 Dec 2021 Updated Daily Summary to reduce output, updated rule task alert
v1.0.1.8  19 Nov 2021 Added longrunning script check
v1.0.1.3   6 May 2021 GPO, SCOMAlerts report DS/WA
v1.0.1.0  20 Apr 2021 Updated timeouts, datasources, WA, rules
v1.0.0.73 16 Dec 2020 Updated timeouts for slow VM performance, DailySummary,Pending Reboot WA/datasources
v1.0.0.59  9 Nov 2020 Updated reports,generic for capabilities, added alerts, expiring certs daily report and rules
v1.0.0.49  9 Sep 2020 Updated Daily Summary Logical Disk run time, DailySummary Task rule, datasource
v1.0.0.41 26 Aug 2020 Updated Daily Summary per SysAdmin, corrected Rules, PendingReboot rule bag, unhealthy agents
v1.0.0.17 17 Aug 2020 Added Pending Reboot monitor alerts functionality
v1.0.0.10  5 Aug 2020 Updated Test variable, previously Test.Count
v1.0.0.3   5 Aug 2020 Updated Task description, Alert rule regular expression for manual task execution
v1.0.0.0   4 Aug 2020 Pack that contains NOSC daily tasks, reports, alerts for SysAdmin Teams.  
	Example Logical Disk Free Space report.  Added additional debug, removed MatchCount suppression, updated $Test
	Removed $Summary and $Details bags, created 2 new 550 events for total alerts and alert summary and detail.```
