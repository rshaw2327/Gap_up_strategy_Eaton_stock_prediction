This is a trend strategy where we are doing a GAP up analysis. Trend Upside but takes time ro exceute trades.

bull_analysis(gap_up, num_days) scans through a DataFrame df and:

Finds days where price “gaps up” (based on a return threshold).

Treats that day as an entry day.

Tracks the highest price over the next num_days days.

Computes the return from entry open price to the highest high.

Stores each trade in a dictionary called trades.
Trades found using the gapup strategy are as follows:-
<img width="601" height="185" alt="image" src="https://github.com/user-attachments/assets/22cc073d-ffd2-410b-a068-994737f2ca2f" />
