# Transportation Safety
## A Reddit r/dataisbeautiful DataViz Battle (May 2019)
---

The data for Reddit's r/dataisbeautiful May 2019 [DataViz Battle](https://www.reddit.com/r/dataisbeautiful/comments/blbkzk/battle_dataviz_battle_for_the_month_of_may_2019/) vexs. The [dataset](https://en.wikipedia.org/wiki/Aviation_safety#Transport_comparisons) is only 11 entries, but its setup is problematic.
* The dataset's value range is immense. This likely requires a log scale for visualizations. Current experience with Logs is minimal. It's not a huge problem but needs to be considered.
* The dataset provides deaths per billion journeys/hours/km.
    * The proper model balancing the various information to rank the saftey of travel types will be difficult.
    * The dataset provides the inverse of the information wanted.