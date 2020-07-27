---
permalink: /postdoc_results/
title: "Postdoc Application Analysis: Results"
layout: archive
author_profile: true
---

{% include base_path %}
## Applicant statistics
The following applet displays histograms of various statistics about successful HEP-TH postdoc applicants for years 2017-2020. A detailed explanation is available [here](/postdoc/). Some UI notes:

* The top drop-down menu selects the different statistics.
* The x-axis can be switched between total count (“absolute”, with postdocs and PhD students stacked) and “relative” (overlaying percentage for postdocs and PhD students).
* The y-axis counts either reflect the count in a single x-axis bin (“interval”) or in all the bins up to that value (“cumulative”).
* The legend is interactive and can be used to filter the type of applicant: postdoc, PhD student or both (note that these were determined by training a model, therefore there is some inherent uncertainty associated with the classification).

<iframe src="https://psabellagarnier.github.io/heprumors/" title="Postdoc Application Profiles" width="100%" height="700" style="border:none;"></iframe>

## Number of offers received

<iframe src="https://psabellagarnier.github.io/heprumors/offers_fig.html" title="Number of offers received" width="100%" height="700" style="border:none;"></iframe>

## Application round
Application round is based on date of rumor mill posting. If the date is earlier than January 7, the offer is considered a first round offer. If it is on or later than January 9, it is considered a second round offer. For January 7 or 8, the type of posting is considered: 'offer' is considered a second round offer while 'accepted' or 'declined' is considered a first round offer that was reported at the last minute.

<iframe src="https://psabellagarnier.github.io/heprumors/round_fig.html" title="Number of offers received" width="100%" height="700" style="border:none;"></iframe>