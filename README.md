# STEM Scholars

STEM Scholars Project -- Social Media as a Proxy for Economic Measurement
Presented by Arjan Kochar (St. Luke’s School)

1) Guiding question
- Can social media activity (across platforms and using a combination of techniques (topic modeling, sentiment analysis, image indicators, and volume measures)) reliably predict or correlate with trends in economic conditions at regional and national scales?

<img width="626" height="413" alt="image" src="https://github.com/user-attachments/assets/31969080-dc36-4589-a8e9-24f9d8b4b06e" />

2) Project hook

- Traditional economic measures (surveys, administrative statistics) are often slow, costly, and subject to reporting lags. Satellite night-lights show precedent that nontraditional digital proxies can be predictive and open a complementary window onto these traditional datasets’ blindspots.

<img width="636" height="456" alt="image" src="https://github.com/user-attachments/assets/c42ec6c3-1b29-43e3-bf0c-2e39cc043f17" />

3) Past Work
- Literature compiled and summarized:
  - Antenucci et al. (2014): Twitter signals for labor-market flows; benefits of real-time, large-scale data; limitations of lexical k-gram methods and noise from news/marketing.
  - Indaco (2020): Correlations between Twitter activity (text and geolocated images) and GDP/geographic economic activity; suggests combining social signals with night lights for validation.
  - Yürük (2025): Links social media sentiment and posts on X with measures of economic uncertainty and asset behavior; recommends VAR and time-series modeling.
  - Ahmed & Watters (2019): Tweet propagation, network structure, and alarm-related signal dynamics; suggests retweet spikes as potential uncertainty markers.
  - Nudge and related behavioural economic theories -- understanding how choice architecture influences decisions

The above research helped me gain a better understanding of how statistical and machine learning methods have been used in the past to use social media data as proxies, complements, or improvements for traditional economic indicators.

<img width="636" height="468" alt="image" src="https://github.com/user-attachments/assets/1b382fa2-5d59-4667-98a3-0225066a978d" />

- Drafted data & methods plan:
  - Candidate signals: post volume (by region/time), topic distributions, sentiment/emotion scores, image-derived consumption indicators, retweet/network spikes.
  - Planned datasets: Twitter/X (public stream & historical queries where permitted), Reddit, Google Trends, official economic series (weekly unemployment claims, monthly employment, GDP, ATUS leisure time, and consuming spending indices).
  - Planned methods: time series modeling and sentiment analysis (NLP with NNs)
- Practical considerations recorded:
  - Signal noise from marketing and PR (e.g., Tom Brady UGG "Pink Slip") must be detected and controlled.
  - Platform demographics and representativeness bias are important limitations.

<img width="890" height="546" alt="image" src="https://github.com/user-attachments/assets/a27fa7d1-b972-4a74-9e8d-ecedbdee682e" />

<img width="625" height="780" alt="image" src="https://github.com/user-attachments/assets/dc092724-7501-4c0f-a59c-455dc20789fd" />

4) Progress since last check-in/presentation

**Successes**
  - Successful meeting with Alumni connection (Kat). She provided valuable insights such as the fact that my validation source only accounts for leisure data from one country. Therefore I can only focus on content specific to my validation source.
  - Adapted for state-based time-use tables from the survey.
  - Basic proof concept with time-series model with limited success. Now transitioning to multi-variable regression as per reccomendation by Kat.

**Challenges**
  - The data sources that I had found before break and planned to use to further my analysis no longer function under the new model + advice from Kat.

5) Future Steps

  - Potentially might try scrapping data (against advice), or try to appeal API access. I will also renew my search for datasets given the new search creteria. 

Running Bibliography

Antenucci, D., Cafarella, M., Levenstein, M., Ré, C., & Shapiro, M. (2014). Using social media to measure labor market flows. National Bureau of Economic Research. https://www.nber.org/system/files/working_papers/w20010/revisions/w20010.rev0.pdf

Indaco, A. (2020). From Twitter to GDP: Estimating economic activity from social media. Regional Science and Urban Economics, 85, 103591. https://doi.org/10.1016/j.regsciurbeco.2020.103591

Yürük, M. F. (2025). Economic Uncertainty on Social Media: The Impact of X Posts on Economic and Financial Indicators. International Journal of Business and Economic Studies, 7(1), 56–69. https://doi.org/10.1186/s42162-025-00185-7

Ahmed, G., & Watters, C. (2019). A study of the relationship between the geographic locations of the user and participation in Twitter during different types of news events. Transactions on Engineering Management, 66(4), 541–555. https://doi.org/10.1109/TEM.2019.2908595

Egeli, André. “Nightlights as a Proxy for Economic Growth.” Atlas.co, 2025, atlas.co/blog/nightlights-as-a-proxy-for-economic-growth/. Accessed 17 Sept. 2025.

Goodison, Donna. “Tom Brady in New “Pink Slip” Ad Campaign for UGG for Men.” Boston Herald, 19 Nov. 2012, www.bostonherald.com/2012/11/19/tom-brady-in-new-pink-slip-ad-campaign-for-ugg-for-men/.

Thaler, R. H., & Sunstein, C. R. (2021). Nudge: The final edition. Penguin Books.
