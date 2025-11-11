# STEMScholars

```markdown
At this point, you should have your introductory content planned (guiding question, project hook, running bibliography) as well as documentation of your process to date. Please add your documentation (or a link if it's on Canva/non-Google format) to your STEM Scholars portfolio. Citations in APA format.

STEM Scholars Project — Social Media as a Proxy for Economic Measurement
Presented by Arjan Kochar (St. Luke’s School)

1) Guiding question
- Can social media activity — across platforms and using a combination of techniques (topic modeling, sentiment analysis, image indicators, and volume measures) — reliably predict or correlate with traditional economic indicators (GDP, unemployment claims, economic uncertainty) at useful temporal and geographic resolution?

2) Project hook
- Traditional economic measures (surveys, administrative statistics) are often slow, costly, and subject to reporting lags. Satellite night-lights show precedent that nontraditional digital proxies can meaningfully reflect economic activity. Social media offers near-real-time, low-cost signals that may capture consumption, leisure, labor-market transitions, and public sentiment — potentially enabling faster, complementary economic indicators.

3) Process to date (documentation)
- Literature compiled and summarized:
  - Antenucci et al. (2014): Twitter signals for labor-market flows; benefits of real-time, large-scale data; limitations of lexical k-gram methods and noise from news/marketing.
  - Indaco (2020): Correlations between Twitter activity (text and geolocated images) and GDP/geographic economic activity; suggests combining social signals with night lights for validation.
  - Yürük (2025): Links social media sentiment and posts on X with measures of economic uncertainty and asset behavior; recommends VAR and time-series modeling.
  - Ahmed & Watters (2019): Tweet propagation, network structure, and alarm-related signal dynamics; suggests retweet spikes as potential uncertainty markers.
- Drafted data & methods plan:
  - Candidate signals: post volume (by region/time), topic distributions, sentiment/emotion scores, image-derived consumption indicators, retweet/network spikes.
  - Planned datasets: Twitter/X (public stream & historical queries where permitted), Reddit, Google Trends, satellite night lights (VIIRS/DMSP), official economic series (weekly unemployment claims, monthly employment, GDP).
  - Planned methods: preprocessing (bot/noise filtering, geolocation mapping), feature extraction (topics, transformer embeddings, image/object classification), time-series modeling (correlations, Granger tests, VAR, ARIMAX), cross-validation with night lights and administrative indicators.
- Practical and ethical considerations recorded:
  - Signal noise from marketing and PR (e.g., Tom Brady UGG "Pink Slip") must be detected and controlled.
  - Platform demographics and representativeness bias are important limitations.
  - Follow platform TOS, privacy protections, and avoid deanonymization.

4) What to add to your STEM Scholars portfolio
- Add this README (or a copy) to your portfolio repository (native option).
- If your presentation is on Canva or another external service, add a shareable view-only link in a text file in the repo (suggested filename: PORTFOLIO_LINKS.md) and include a PDF export under /docs (e.g., /docs/slides.pdf).
- Include the date/version and a short note describing what the attached slide deck contains (slides, data sources, and notes).

5) Planned short-term deliverables (next analyses)
- Implement a minimal pipeline to pull historical Twitter counts for unemployment-related phrases and compare weekly counts with official weekly unemployment claims for one region.
- Add a night-lights cross-check for the same period/region to compare different proxy behavior.
- Move from simple k-gram counts toward transformer embeddings for robustness in text features.

6) Data sources & candidate signals (summary)
- Twitter/X: phrase/hashtag counts, sentiment, geolocated images, retweets (volume & spike detection).
- Reddit: subreddit volume and sentiment (different demographics and conversational style).
- Google Trends: search volumes for economic keywords (high-frequency complement).
- Night lights (VIIRS/DMSP): satellite radiance measures for cross-validation.
- Official datasets: weekly unemployment claims, monthly employment, GDP releases, stock indices.

7) Methods summary
- Preprocessing: language detection, bot/spam filtering, deduplication, geocoding.
- Feature extraction: volume, topic models (LDA/BERTopic), sentiment (lexicon + transformer classifiers), image features (object/scene detection), diffusion/retweet dynamics.
- Modeling & validation: correlation analysis, Granger causality tests, VAR/ARIMAX predictive models, cross-validation vs. night lights and administrative series.
- Robustness: detect and control for marketing/PR events, major news releases; run demographic bias checks.

8) Ethical considerations
- Use only public data and follow platform terms of service.
- Do not attempt to deanonymize users or expose private information.
- Account for manipulation risk (bots, coordinated campaigns) via detection and robustness checks.
- Clearly state limitations and avoid causal claims from correlational findings unless supported by causal identification strategies.

9) Running bibliography (APA)
Antenucci, D., Cafarella, M., Levenstein, M., Ré, C., & Shapiro, M. (2014). Using social media to measure labor market flows. National Bureau of Economic Research. https://www.nber.org/system/files/working_papers/w20010/w20010.pdf

Indaco, A. (2020). From Twitter to GDP: Estimating economic activity from social media. Regional Science and Urban Economics, 85, 103591. https://doi.org/10.1016/j.regsciurbeco.2020.103591

Yürük, M. F. (2025). Economic Uncertainty on Social Media: The Impact of X Posts on Economic and Financial Indicators. International Journal of Business and Economic Studies, 7(1), 56–69. https://doi.org/10.54821/uiecd.1634814

Ahmed, G., & Watters, C. (2019). A study of the relationship between the geographic locations of the user and participation in Twitter during different types of news events. Transactions on Engineering and Computing Sciences, 6(6), 01. https://doi.org/10.14738/tmlai.66.5636

10) Contact / credits
- Lead presenter: Arjan Kochar (St. Luke’s School)
- Repository owner: ByteALittleBit (GitHub)

Add this file to your STEM Scholars portfolio folder or paste the Canva/slide link into PORTFOLIO_LINKS.md. If you need, export slides to PDF and place them under /docs for reproducibility.
```
