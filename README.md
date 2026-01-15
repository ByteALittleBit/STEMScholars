# STEM Scholars

**STEM Scholars Project -- Social Media as a Proxy for Economic Measurement**  
Presented by Arjan Kochar (St. Luke’s School)

---

## 1) Guiding Question

<img width="626" height="413" alt="image" src="https://github.com/user-attachments/assets/31969080-dc36-4589-a8e9-24f9d8b4b06e" />

- Can social media activity (across platforms and using a combination of techniques (topic modeling, sentiment analysis, image indicators, and volume measures)) reliably predict or correlate with trends?

---

## 2) Project Hook

<img width="636" height="456" alt="image" src="https://github.com/user-attachments/assets/c42ec6c3-1b29-43e3-bf0c-2e39cc043f17" />

- Traditional economic measures (surveys, administrative statistics) are often slow, costly, and subject to reporting lags.  
- Satellite night-lights show precedent that nontraditional digital proxies can complement these measures.

---

## 3) Past Work

<img width="636" height="468" alt="image" src="https://github.com/user-attachments/assets/1b382fa2-5d59-4667-98a3-0225066a978d" />
<img width="890" height="546" alt="image" src="https://github.com/user-attachments/assets/a27fa7d1-b972-4a74-9e8d-ecedbdee682e" />
<img width="625" height="780" alt="image" src="https://github.com/user-attachments/assets/dc092724-7501-4c0f-a59c-455dc20789fd" />

### Literature Summary
- **Antenucci et al. (2014)**  
  *Twitter signals for labor-market flows; benefits of real-time, large-scale data; limitations of lexical k-gram methods and noise from news/marketing.*
- **Indaco (2020)**  
  *Correlations between Twitter activity (text and geolocated images) and GDP/geographic economic activity; suggests combining social signals with night-lights for validation.*
- **Yürük (2025)**  
  *Links social media sentiment and posts on X with measures of economic uncertainty and asset behavior; recommends VAR and time-series modeling.*
- **Ahmed & Watters (2019)**  
  *Tweet propagation, network structure, and alarm-related signal dynamics; suggests retweet spikes as potential uncertainty markers.*
- **Nudge & Behavioral Economic Theories**  
  *Understanding how choice architecture influences decisions.*

### Data & Methods Plan
- **Candidate Signals**
  - Post volume (by region/time)
  - Topic distributions
  - Sentiment/emotion scores
  - Image-derived consumption indicators
  - Retweet/network spikes
- **Planned Datasets**
  - Twitter/X (public stream & historical queries where permitted)
  - Reddit
  - Google Trends
  - Official economic series (weekly unemployment claims, monthly employment, GDP, ATUS leisure statistics)
- **Planned Methods**
  - Time series modeling and sentiment analysis (NLP with NNs)
- **Practical Considerations**
  - Signal noise from marketing and PR (e.g., Tom Brady UGG "Pink Slip") must be detected and controlled.
  - Platform demographics and representativeness bias are important limitations.

---

## 4) Progress Since Last Check-in/Presentation

### Successes
- Successful meeting with Alumni connection (Kat).  
  *She provided valuable insights such as the fact that my validation source only accounts for leisure data from one country. Therefore, I can only focus on state-based time-use tables.*
- Adapted for state-based time-use tables from the survey.
- Basic proof-of-concept with time-series model (limited success).  
  *Now transitioning to multi-variable regression as per Kat’s recommendation.*

### Challenges
- Previous data sources no longer function under the new model/advice from Kat.

---

## 5) Future Steps
- Potentially try scraping data (against advice) or appeal for API access.  
- Renew search for datasets based on refined criteria.

---

## Running Bibliography

- Antenucci, D., Cafarella, M., Levenstein, M., Ré, C., & Shapiro, M. (2014).  
  *Using social media to measure labor market flows.* National Bureau of Economic Research. [Link](https://www.nber.org/system/files/...)
  
- Indaco, A. (2020).  
  *From Twitter to GDP: Estimating economic activity from social media.* Regional Science and Urban Economics, 85, 103591. [Link](https://doi.org/10.1016/j.regsciurbeco.2020.103591)
  
- Yürük, M. F. (2025).  
  *Economic Uncertainty on Social Media: The Impact of X Posts on Economic and Financial Indicators.* International Journal of Business and Economic Studies, 7(1), 56–69. [Link](https://...)
  
- Ahmed, G., & Watters, C. (2019).  
  *A study of the relationship between the geographic locations of the user and participation in Twitter during different types of news events.* Transactions on Engineering ... [Link](https://...)
  
- Egeli, André.  
  *“Nightlights as a Proxy for Economic Growth.”* Atlas.co, 2025. [Link](https://atlas.co/blog/nightlights-as-a-proxy-for-economic-growth/)
  
- Goodison, Donna.  
  *“Tom Brady in New “Pink Slip” Ad Campaign for UGG for Men.”* Boston Herald, 19 Nov. 2012. [Link](https://www.bostonherald.com/2012/11/19/tom-brady-in-new-pink-slip-ad-campaign-for-ugg-for-m[...])
  
- Thaler, R. H., & Sunstein, C. R. (2021).  
  *Nudge: The final edition.* Penguin Books.
