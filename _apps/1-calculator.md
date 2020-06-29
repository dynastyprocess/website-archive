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

as a general commentary on trade calcs: 99% of calculators start with (consensus or site or personal) rankings (rarely ADP) and pass it through an ~exponential decay type formula to generate a number. 
--
Questions to consider:
1) Do you trust their ranks? (Matt Kelley can have questionable ones, DTC is known to go in and manipulate theirs for market-corrections) 
2) How fresh are the ranks and values?
3) Do you trust that their algorithm is descriptive of your league?
4) Do you want a calculator to tell you what the market thinks or do you want it to tell you someone’s opinion as to whether you’re winning or losing?
-- 
I try to answer all of these questions openly in DynastyProcess's calculator: 
- Ranks are from FantasyPros, DP doesn't touch them
- Update date is posted right in the app
- I give you the ability to adjust the algorithm on a slider - how important is depth? how important are rookies? how important are future picks?
- FantasyPros is a good measure of consensus, so the calculator is primarily geared for describing market

## Frequently Asked Questions

### What is the "Depth Value Slider"?
One major problem with trade calculators is the idea that there is a universal number that describes how players should be valued relative to the others. I'm taking an initial stab at this problem by allowing you to play with the "depth" weighting. If your league values depth more (i.e. is a best ball league, has more starter, roster, or team spots than usual) you would move the slider to the left - and if your league values studs more, you would move the slider to the right. It's preset to what we think might be a sensible default for standard 12 team PPR leagues, but your mileage may vary!

### What is the "Rookie Optimism Slider"?

## FAQ: Values

[Values](/values){: .btn .btn--info}
*We've got a few more ideas on getting better at tweaking values, but we'd love to hear your suggestions!*

## Google Sheets Calculator
The now-deprecated Google Sheets calculator was the original "trade calculator" developed by Tan (as part of the DynastyDashboard project). It's still set up to receive automatic value updates (when we push a new values CSV to the GitHub, the Google Sheet pulls it in.)

[Google Sheets Calculator](https://docs.google.com/spreadsheets/d/1mmv1h5kDseejWSHx7BVlwY91gReONfbakeqYisAmLyY/copy){: .btn .btn--info}
