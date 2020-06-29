---
title: Trade Calculator
classes: wide
header:
  teaser: https://i.imgur.com/hapFEga.png
excerpt: "Our Trade Calculator features a startup mode, suggestions, and customizable values based on your preferences for depth and rookies."
feature_row:
  - url: https://apps.dynastyprocess.com/calculator
    image_path: https://i.imgur.com/hapFEga.png
    Title: "Link"
    alt: "Calculator"
    excerpt: "Our Trade Calculator features a startup mode, suggestions, and customizable values based on your preferences for depth and rookies."
    btn_label: "Try it now!"
    btn_class: "btn--primary"
permalink: /calculator
---
{% include feature_row type="left" %}

## Thoughts on the Art of Dynasty Trade Calculators
---
*(Adapted from some previous discussions on TDM Discord)*

As a general commentary on trade calcs: 99% of calculators start with (consensus or site or personal) rankings (rarely ADP) and pass it through an ~ exponential decay type formula to generate a number. 

#### Questions to consider:
1) Do you trust their ranks? 
    *(Some sites may have very ... opinionated ... rankings, others may pre/post-process rankings to influence the trade values, which can be a good or bad thing depending on the adjuster - either way, you don't have visibility into these.)*

2) How fresh are the ranks and values?

3) Do you trust that their algorithm is descriptive of your league?

4) Do you want a calculator to tell you what the market thinks or do you want it to tell you someone’s opinion as to whether you’re winning or losing?

-- 
We try to answer all of these questions openly in DynastyProcess's calculator: 
- Ranks are from FantasyPros, DP doesn't touch them
- Update date is posted right in the app
- DP give you the ability to adjust the algorithm with a bevy of sliders - how important is depth or studs? How important are rookies? How important are future picks? 
    - The algorithm is preset to what we think is a sensible default for most 12 team PPR leagues. You may value depth more if the league is best ball or has more starter/roster/team spots than the average (~9 starters, 250-350 rostered offensive players etc). 
    
- FantasyPros is a good measure of consensus, so the calculator is primarily geared for describing market. It can tell you whether the `market` thinks you're winning or losing, but opinions are known to vary. 

## FAQ: Values

There's a separate discussion on ***Values*** on this page:

[Values](/values){: .btn .btn--info}

## Google Sheets Calculator
The now-deprecated Google Sheets calculator was the original "trade calculator" developed by Tan (as part of the DynastyDashboard project). It's still set up to receive value updates (when we push a new values CSV to the data repo, the Google Sheet pulls it in.)

[Google Sheets Calculator](https://docs.google.com/spreadsheets/d/1mmv1h5kDseejWSHx7BVlwY91gReONfbakeqYisAmLyY/copy){: .btn .btn--info}
