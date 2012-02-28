# PullToRefresh

A twitter-style pull-to-refresh NSScrollView.

Based on:
Leah Culver's PullToRefresh https://github.com/leah/PullToRefresh
and Alex Zielenski's ScrollToRefresh https://github.com/alexzielenski/ScrollToRefresh

## Key Features
Elastic Scroll
Added optional delegate protocol method: ptrScrollViewDidTriggerRefresh:(id)sender

This method gets called when the user scrolls beyond the set bounds.