# Lab Investigation: Failed Login Detection

---

## Objective
To detect multiple failed login attempts using Windows Event Logs in a controlled lab environment.

---

## Environment
- Windows 10
- Event Viewer
- Local system logs

---

## Alert Indicator
**Event ID 4625 – Failed Login Attempt**

---

## Investigation Process
1. Triggered multiple failed login attempts.
2. Opened Event Viewer.
3. Navigated to Windows Logs → Security.
4. Filtered logs using Event ID 4625.
5. Observed repeated failed attempts from same user account.

---

## Indicators Observed
- Multiple failed authentication events
- Same username targeted
- Close timestamp pattern

---

## Analysis
The pattern of repeated failed logins may indicate a potential brute-force attempt scenario in a real-world SOC environment.

---

## Recommended Action
- Enable account lockout policy
- Monitor repeated failed login attempts
- Escalate to SOC L2 if behavior continues

---

## Conclusion
Investigation conducted in a controlled lab environment for learning and documentation purposes.
