# Triage the broken build

Instructions for trainees:

1. **Open the failed run.** Go to the repo's *Actions* tab, select the **Broken Build Lab** workflow, and open the run for the latest push.
2. **Find the `boom` marker in the log.** Open the failed job and read the log until you spot the `boom` line — that is the last step that succeeded before the failure.
3. **Re-run only the failed jobs.** On the run page, use **Re-run failed jobs** (not *Re-run all jobs*) so only the failing job starts a second attempt.

The build is supposed to fail — that is the point of the lab.
