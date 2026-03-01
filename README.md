# A Change to Improve Video Game Player Retention: A/B Testing 

## Summary:

Designed and analyzed an A/B test (n=90,000+) to evaluate the impact of progression gating on player retention in a mobile game. Found that the majority of users churned before reaching either gate level, revealing that late-stage gating has limited leverage on overall retention. Among high-engagement players who reached the gates, minimal 7 day retention lift was observed between gate 30 versus 40. Recommended shifting experimentation to earlier-game friction points (levels 5 & 10) to meaningfully impact retention and lifetime value.

## Methods:
- Retrsospective Power/ Sensitivity Analysis
- A/B Testing of Binary & Continuous Variables:
    - Hypothesis Testing
        - $X^2$ test
        - Mann-Whitney U Test

## Tools:
- Python 3.13.3
    - `pandas` `numpy` `scipy` `pingouin` `matplotlib.pyplot` `statsmodel.stats`

 
## Full Report:
https://zesty-bubbler-a87.notion.site/Improving-Player-Retention-Through-Experimental-Design-2e6537d1e6d98050a509c70c5d55f6b8?source=copy_link

### Key Takeaways:

- Because over 60% of players churned before reaching level 40, the effective sample size dropped to ~27K.
- This compromised the statistical sensitivity of the tests for Early Return Behavior and Gameplay Depth.
- Mid-term Retention, though adequately powered and showing that there was a statistically significant difference between the gate 30 and gate 40, only shows a minimal difference leading to questions of whether it is meaningful enough.
