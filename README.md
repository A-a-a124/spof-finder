# SPOF Finder

Which single spare part could stop a critical machine, and why?

A concept prototype that joins five SAP tables (parts, suppliers, machines, shelves, movements) and finds the
single points of failure in normal operations: one supplier, one storage location, false backups.

**Live demo:** https://a-a-a124.github.io/spof-finder/

- X-ray map with a failure ripple: everything that stops if a part is unavailable
- "Fix it and see": switch a weakness off and watch the score change (simulation only)
- Runs fully offline in one HTML file

All numbers are fictional sample data, for illustration only.

Designed by Abdullah Aladhyani
