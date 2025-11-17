# STEM Scholars

STEM Scholars Project -- Social Media as a Proxy for Economic Measurement
Presented by Arjan Kochar (St. Luke’s School)

1) Guiding question
- Can social media activity (across platforms and using a combination of techniques (topic modeling, sentiment analysis, image indicators, and volume measures)) reliably predict or correlate with traditional economic indicators (GDP, unemployment claims, economic uncertainty)?

<img width="626" height="413" alt="image" src="https://github.com/user-attachments/assets/31969080-dc36-4589-a8e9-24f9d8b4b06e" />

2) Project hook

<img width="636" height="456" alt="image" src="https://github.com/user-attachments/assets/c42ec6c3-1b29-43e3-bf0c-2e39cc043f17" />


- Traditional economic measures (surveys, administrative statistics) are often slow, costly, and subject to reporting lags. Satellite night-lights show precedent that nontraditional digital proxies can meaningfully reflect economic activity. Social media offers near-real-time, low-cost signals that may capture consumption, leisure, labor-market transitions, and public sentiment potentially enabling faster, complementary economic indicators.

<img width="636" height="468" alt="image" src="https://github.com/user-attachments/assets/1b382fa2-5d59-4667-98a3-0225066a978d" />


3) Process to date (documentation)
- Literature compiled and summarized:
  - Antenucci et al. (2014): Twitter signals for labor-market flows; benefits of real-time, large-scale data; limitations of lexical k-gram methods and noise from news/marketing.
  - Indaco (2020): Correlations between Twitter activity (text and geolocated images) and GDP/geographic economic activity; suggests combining social signals with night lights for validation.
  - Yürük (2025): Links social media sentiment and posts on X with measures of economic uncertainty and asset behavior; recommends VAR and time-series modeling.
  - Ahmed & Watters (2019): Tweet propagation, network structure, and alarm-related signal dynamics; suggests retweet spikes as potential uncertainty markers.
  - Nudge and related behavioural economic theories -- understanding how choice architecture influences decisions
 
The above research helped me gain a better understanding of how statistical and machine learning methods have been used in the past to use social media data as proxies, complements, or improvements to curret economic indicators.

- Drafted data & methods plan:
  - Candidate signals: post volume (by region/time), topic distributions, sentiment/emotion scores, image-derived consumption indicators, retweet/network spikes.
  - Planned datasets: Twitter/X (public stream & historical queries where permitted), Reddit, Google Trends, official economic series (weekly unemployment claims, monthly employment, GDP, ATUS leisure time statistics).
  - Planned methods: time series modeling and sentiment analysis (NLP with NNs)
- Practical considerations recorded:
  - Signal noise from marketing and PR (e.g., Tom Brady UGG "Pink Slip") must be detected and controlled.
  - Platform demographics and representativeness bias are important limitations.
 
<img width="890" height="546" alt="image" src="https://github.com/user-attachments/assets/a27fa7d1-b972-4a74-9e8d-ecedbdee682e" />


4) Planned short-term deliverables (next analyses)
- Work on algorithm (likely time series) for Reddit volume correlated with leisure, S&P 500 Percent Change, etc.

Running Bibliography

Antenucci, D., Cafarella, M., Levenstein, M., Ré, C., & Shapiro, M. (2014). Using social media to measure labor market flows. National Bureau of Economic Research. https://www.nber.org/system/files/working_papers/w20010/w20010.pdf

Indaco, A. (2020). From Twitter to GDP: Estimating economic activity from social media. Regional Science and Urban Economics, 85, 103591. https://doi.org/10.1016/j.regsciurbeco.2020.103591

Yürük, M. F. (2025). Economic Uncertainty on Social Media: The Impact of X Posts on Economic and Financial Indicators. International Journal of Business and Economic Studies, 7(1), 56–69. https://doi.org/10.54821/uiecd.1634814

Ahmed, G., & Watters, C. (2019). A study of the relationship between the geographic locations of the user and participation in Twitter during different types of news events. Transactions on Engineering and Computing Sciences, 6(6), 01. https://doi.org/10.14738/tmlai.66.5636

Egeli, André. “Nightlights as a Proxy for Economic Growth.” Atlas.co, 2025, atlas.co/blog/nightlights-as-a-proxy-for-economic-growth/. Accessed 17 Sept. 2025.

Goodison, Donna. “Tom Brady in New “Pink Slip” Ad Campaign for UGG for Men.” Boston Herald, 19 Nov. 2012, www.bostonherald.com/2012/11/19/tom-brady-in-new-pink-slip-ad-campaign-for-ugg-for-men/. Accessed 17 Sept. 2025.

Thaler, R. H., & Sunstein, C. R. (2021). Nudge: The final edition. Penguin Books.
