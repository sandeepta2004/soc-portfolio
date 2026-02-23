# Lab Investigation: Failed Login Detection (Simulated)

## Objective
To detect multiple failed login attempts using Windows Event Logs in a controlled lab environment.

## Environment
- Windows 10
- Event Viewer
- Local System Logs

## Alert Indicator
Event ID 4625 – Failed Login Attempt

## Investigation Steps
1. Triggered multiple failed login attempts.
2. Opened Event Viewer.
3. Navigated to Windows Logs → Security.
4. Filtered logs using Event ID 4625.
5. Observed repeated failed attempts from same user account.

## Indicators Observed
- Multiple failed authentication events
- Same username targeted
- Close timestamp pattern

## Analysis
The repeated failed login attempts indicate a potential brute-force attempt scenario in real-world SOC monitoring.

## Recommended Action
- Enable account lockout policy
- Monitor repeated failed login attempts
- Alert SOC Level 2 if pattern continues

## Conclusion
No real compromise occurred. Investigation conducted in a simulated lab environment for learning purposes.
