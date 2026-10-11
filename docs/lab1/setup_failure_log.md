\# Setup Failure Log - Lab 1



\## Incident 1: Environment Recovery Test (Simulated Fresh Clone)

\- \*\*What I broke:\*\* Deleted the `.venv` folder completely to test environment recovery from scratch.

\- \*\*What went wrong during recovery:\*\* No critical system errors occurred because the steps documented in `README.md` were accurate. However, it highlighted the importance of strictly following the order (creating venv -> activating it -> installing requirements -> installing editable mode).

\- \*\*How I fixed it / Conclusion:\*\* The recovery was successful on the first try using only the `README.md` instructions. No modifications to the README were required as the setup steps proved to be fully reproducible.

