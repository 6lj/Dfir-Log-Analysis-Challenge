# DFIR Challenge 
[https://dfir.q5.qa](https://dfir.q5.qa/)

A 25-question DFIR lab where you analyze Windows security logs from Splunk, Elastic, or Event Viewer to trace the attacker abyah through persistence and lateral movement.

---

## How to Play

1. Enter your name on the first screen.
2. Choose a platform - Splunk (CSV), Elastic (JSON), or Event Viewer (EVTX).
3. Click "Download Logs & Start Timer" - the file downloads and your timer starts immediately.
4. Read each question, find the answer in the logs, type it, and click Submit.
5. Solve all 25 questions to complete the lab.

Your progress, timer, and answers are saved automatically - you can refresh the page without losing anything.

---

## Log Files

You only need one file. Pick whichever you prefer:

| Platform | File | What You Need |
|----------|------|--------------|
| Splunk | `abyah_splunk_events.csv` | Any CSV reader or text editor |
| Elastic | `abyah_elastic_events.json` | Any JSON viewer or text editor |
| Event Viewer | `abyah_security_events.evtx` | Windows Event Viewer or `python-evtx` |

All three contain the same events - it's your choice.

---

