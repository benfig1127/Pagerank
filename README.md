# Pagerank Task 1:

# Part 1:

Input:

```
python3 pagerank.py --data=./small.csv.gz --verbose
```

Output:
```
DEBUG:root:computing indices
DEBUG:root:computing values
INFO:root:rank=0 pagerank=6.0257e-01 url=4
INFO:root:rank=1 pagerank=4.6414e-01 url=6
INFO:root:rank=2 pagerank=3.4544e-01 url=5
INFO:root:rank=3 pagerank=1.9498e-01 url=2
INFO:root:rank=4 pagerank=9.9210e-02 url=3
INFO:root:rank=5 pagerank=8.9347e-02 url=1
```
# Part 2:

Input:

```
python3 pagerank.py --data=./lawfareblog.csv.gz --search_query='corona'
```

Output:
```
INFO:root:rank=0 pagerank=4.5861e-03 url=www.lawfareblog.com/lawfare-podcast-united-nations-and-coronavirus-crisis
INFO:root:rank=1 pagerank=4.0460e-03 url=www.lawfareblog.com/house-oversight-committee-holds-day-two-hearing-government-coronavirus-response
INFO:root:rank=2 pagerank=2.6116e-03 url=www.lawfareblog.com/britains-coronavirus-response
INFO:root:rank=3 pagerank=2.5390e-03 url=www.lawfareblog.com/prosecuting-purposeful-coronavirus-exposure-terrorism
INFO:root:rank=4 pagerank=2.3557e-03 url=www.lawfareblog.com/israeli-emergency-regulations-location-tracking-coronavirus-carriers
INFO:root:rank=5 pagerank=2.2895e-03 url=www.lawfareblog.com/why-congress-conducting-business-usual-face-coronavirus
INFO:root:rank=6 pagerank=2.2727e-03 url=www.lawfareblog.com/livestream-house-oversight-committee-holds-hearing-government-coronavirus-response
INFO:root:rank=7 pagerank=2.2520e-03 url=www.lawfareblog.com/congressional-homeland-security-committees-seek-ways-support-state-federal-responses-coronavirus
INFO:root:rank=8 pagerank=2.1878e-03 url=www.lawfareblog.com/paper-hearing-experts-debate-digital-contact-tracing-and-coronavirus-privacy-concerns
INFO:root:rank=9 pagerank=2.0339e-03 url=www.lawfareblog.com/cyberlaw-podcast-how-israel-fighting-coronavirus
```
Input:
```
python3 pagerank.py --data=./lawfareblog.csv.gz --search_query='trump'
```
Output:
```
INFO:root:rank=0 pagerank=6.6243e-02 url=www.lawfareblog.com/donald-trump-and-politically-weaponized-executive-branch
INFO:root:rank=1 pagerank=6.0194e-02 url=www.lawfareblog.com/trump-asks-supreme-court-stay-congressional-subpeona-tax-returns
INFO:root:rank=2 pagerank=3.4969e-02 url=www.lawfareblog.com/trump-administrations-worrying-new-policy-israeli-settlements
INFO:root:rank=3 pagerank=3.2193e-02 url=www.lawfareblog.com/document-trump-revokes-obama-executive-order-counterterrorism-strike-casualty-reporting
INFO:root:rank=4 pagerank=3.0971e-02 url=www.lawfareblog.com/dc-circuit-overrules-district-courts-due-process-ruling-qasim-v-trump
INFO:root:rank=5 pagerank=2.8460e-02 url=www.lawfareblog.com/how-trumps-approach-middle-east-ignores-past-future-and-human-condition
INFO:root:rank=6 pagerank=2.5252e-02 url=www.lawfareblog.com/why-trump-cant-buy-greenland
INFO:root:rank=7 pagerank=2.2457e-02 url=www.lawfareblog.com/oral-argument-summary-qassim-v-trump
INFO:root:rank=8 pagerank=2.1462e-02 url=www.lawfareblog.com/dc-circuit-court-denies-trump-rehearing-mazars-case
INFO:root:rank=9 pagerank=2.1103e-02 url=www.lawfareblog.com/second-circuit-rules-mazars-must-hand-over-trump-tax-returns-new-york-prosecutors
```
Input:
```
python3 pagerank.py --data=./lawfareblog.csv.gz --search_query='iran'
```
Output:
```
INFO:root:rank=0 pagerank=6.6131e-02 url=www.lawfareblog.com/praise-presidents-iran-tweets
INFO:root:rank=1 pagerank=2.9199e-02 url=www.lawfareblog.com/how-us-iran-tensions-could-disrupt-iraqs-fragile-peace
INFO:root:rank=2 pagerank=1.7709e-02 url=www.lawfareblog.com/cyber-command-operational-update-clarifying-june-2019-iran-operation
INFO:root:rank=3 pagerank=1.4604e-02 url=www.lawfareblog.com/aborted-iran-strike-fine-line-between-necessity-and-revenge
INFO:root:rank=4 pagerank=8.4512e-03 url=www.lawfareblog.com/iranian-hostage-crisis-and-its-effect-american-politics
INFO:root:rank=5 pagerank=8.3989e-03 url=www.lawfareblog.com/parsing-state-departments-letter-use-force-against-iran
INFO:root:rank=6 pagerank=8.2581e-03 url=www.lawfareblog.com/announcing-united-states-and-use-force-against-iran-new-lawfare-e-book
INFO:root:rank=7 pagerank=8.0561e-03 url=www.lawfareblog.com/trump-moves-cut-irans-oil-revenues-whats-his-endgame
INFO:root:rank=8 pagerank=7.1939e-03 url=www.lawfareblog.com/us-names-iranian-revolutionary-guard-terrorist-organization-and-sanctions-international-criminal
INFO:root:rank=9 pagerank=5.9405e-03 url=www.lawfareblog.com/iran-shoots-down-us-drone-domestic-and-international-legal-implications
```
# Part 3:

Input:
```
python3 pagerank.py --data=./lawfareblog.csv.gz
```
Output:
```
INFO:root:rank=0 pagerank=8.4156e+00 url=www.lawfareblog.com/lawfare-job-board
INFO:root:rank=1 pagerank=8.4156e+00 url=www.lawfareblog.com/masthead
INFO:root:rank=2 pagerank=8.4156e+00 url=www.lawfareblog.com/litigation-documents-related-appointment-matthew-whitaker-acting-attorney-general
INFO:root:rank=3 pagerank=8.4156e+00 url=www.lawfareblog.com/documents-related-mueller-investigation
INFO:root:rank=4 pagerank=8.4156e+00 url=www.lawfareblog.com/topics
INFO:root:rank=5 pagerank=8.4156e+00 url=www.lawfareblog.com/about-lawfare-brief-history-term-and-site
INFO:root:rank=6 pagerank=8.4156e+00 url=www.lawfareblog.com/snowden-revelations
INFO:root:rank=7 pagerank=8.4156e+00 url=www.lawfareblog.com/support-lawfare
INFO:root:rank=8 pagerank=8.4156e+00 url=www.lawfareblog.com/upcoming-events
INFO:root:rank=9 pagerank=8.4156e+00 url=www.lawfareblog.com/our-comments-policy
```
Input:
```
python3 pagerank.py --data=./lawfareblog.csv.gz --filter_ratio=0.2
```
Output:
```
INFO:root:rank=0 pagerank=4.2773e+00 url=www.lawfareblog.com/trump-asks-supreme-court-stay-congressional-subpeona-tax-returns
INFO:root:rank=1 pagerank=2.7717e+00 url=www.lawfareblog.com/livestream-nov-21-impeachment-hearings-0
INFO:root:rank=2 pagerank=2.7533e+00 url=www.lawfareblog.com/opening-statement-david-holmes
INFO:root:rank=3 pagerank=1.8721e+00 url=www.lawfareblog.com/senate-examines-threats-homeland
INFO:root:rank=4 pagerank=1.7418e+00 url=www.lawfareblog.com/what-make-first-day-impeachment-hearings
INFO:root:rank=5 pagerank=1.7411e+00 url=www.lawfareblog.com/livestream-house-armed-services-committee-hearing-f-35-program
INFO:root:rank=6 pagerank=1.7348e+00 url=www.lawfareblog.com/whats-house-resolution-impeachment
INFO:root:rank=7 pagerank=1.6384e+00 url=www.lawfareblog.com/congress-us-policy-toward-syria-and-turkey-overview-recent-hearings
INFO:root:rank=8 pagerank=1.5597e+00 url=www.lawfareblog.com/summary-david-holmess-deposition-testimony
INFO:root:rank=9 pagerank=9.1265e-01 url=www.lawfareblog.com/events
```
# Part 4:

Input:
```
python3 pagerank.py --data=./lawfareblog.csv.gz --verbose 
```
Output:
```
DEBUG:root:computing indices
DEBUG:root:computing values
INFO:root:rank=0 pagerank=8.4156e+00 url=www.lawfareblog.com/lawfare-job-board
INFO:root:rank=1 pagerank=8.4156e+00 url=www.lawfareblog.com/masthead
INFO:root:rank=2 pagerank=8.4156e+00 url=www.lawfareblog.com/litigation-documents-related-appointment-matthew-whitaker-acting-attorney-general
INFO:root:rank=3 pagerank=8.4156e+00 url=www.lawfareblog.com/documents-related-mueller-investigation
INFO:root:rank=4 pagerank=8.4156e+00 url=www.lawfareblog.com/topics
INFO:root:rank=5 pagerank=8.4156e+00 url=www.lawfareblog.com/about-lawfare-brief-history-term-and-site
INFO:root:rank=6 pagerank=8.4156e+00 url=www.lawfareblog.com/snowden-revelations
INFO:root:rank=7 pagerank=8.4156e+00 url=www.lawfareblog.com/support-lawfare
INFO:root:rank=8 pagerank=8.4156e+00 url=www.lawfareblog.com/upcoming-events
INFO:root:rank=9 pagerank=8.4156e+00 url=www.lawfareblog.com/our-comments-policy
```
Input:
```
python3 pagerank.py --data=./lawfareblog.csv.gz --verbose --alpha=0.99999
```
Output:
```
DEBUG:root:computing indices
DEBUG:root:computing values
INFO:root:rank=0 pagerank=1.0623e+01 url=www.lawfareblog.com/lawfare-job-board
INFO:root:rank=1 pagerank=1.0623e+01 url=www.lawfareblog.com/masthead
INFO:root:rank=2 pagerank=1.0623e+01 url=www.lawfareblog.com/litigation-documents-resources-related-travel-ban
INFO:root:rank=3 pagerank=1.0623e+01 url=www.lawfareblog.com/subscribe-lawfare
INFO:root:rank=4 pagerank=1.0623e+01 url=www.lawfareblog.com/litigation-documents-related-appointment-matthew-whitaker-acting-attorney-general
INFO:root:rank=5 pagerank=1.0623e+01 url=www.lawfareblog.com/documents-related-mueller-investigation
INFO:root:rank=6 pagerank=1.0623e+01 url=www.lawfareblog.com/our-comments-policy
INFO:root:rank=7 pagerank=1.0623e+01 url=www.lawfareblog.com/upcoming-events
INFO:root:rank=8 pagerank=1.0623e+01 url=www.lawfareblog.com/topics
INFO:root:rank=9 pagerank=1.0623e+01 url=www.lawfareblog.com/support-lawfare
```
Input:
```
python3 pagerank.py --data=./lawfareblog.csv.gz --verbose --filter_ratio=0.2
```
Output:
```
DEBUG:root:computing indices
DEBUG:root:computing values
INFO:root:rank=0 pagerank=4.2773e+00 url=www.lawfareblog.com/trump-asks-supreme-court-stay-congressional-subpeona-tax-returns
INFO:root:rank=1 pagerank=2.7717e+00 url=www.lawfareblog.com/livestream-nov-21-impeachment-hearings-0
INFO:root:rank=2 pagerank=2.7533e+00 url=www.lawfareblog.com/opening-statement-david-holmes
INFO:root:rank=3 pagerank=1.8721e+00 url=www.lawfareblog.com/senate-examines-threats-homeland
INFO:root:rank=4 pagerank=1.7418e+00 url=www.lawfareblog.com/what-make-first-day-impeachment-hearings
INFO:root:rank=5 pagerank=1.7411e+00 url=www.lawfareblog.com/livestream-house-armed-services-committee-hearing-f-35-program
INFO:root:rank=6 pagerank=1.7348e+00 url=www.lawfareblog.com/whats-house-resolution-impeachment
INFO:root:rank=7 pagerank=1.6384e+00 url=www.lawfareblog.com/congress-us-policy-toward-syria-and-turkey-overview-recent-hearings
INFO:root:rank=8 pagerank=1.5597e+00 url=www.lawfareblog.com/summary-david-holmess-deposition-testimony
INFO:root:rank=9 pagerank=9.1265e-01 url=www.lawfareblog.com/events
```

Input:
```
python3 pagerank.py --data=./lawfareblog.csv.gz --verbose --filter_ratio=0.2 --alpha=0.99999
```
Output:
```
DEBUG:root:computing indices
DEBUG:root:computing values
INFO:root:rank=0 pagerank=4.7947e+01 url=www.lawfareblog.com/covid-19-speech-and-surveillance-response
INFO:root:rank=1 pagerank=4.7947e+01 url=www.lawfareblog.com/lawfare-live-covid-19-speech-and-surveillance
INFO:root:rank=2 pagerank=7.2709e+00 url=www.lawfareblog.com/cost-using-zero-days
INFO:root:rank=3 pagerank=2.1691e+00 url=www.lawfareblog.com/lawfare-podcast-former-congressman-brian-baird-and-daniel-schuman-how-congress-can-continue-function
INFO:root:rank=4 pagerank=1.4214e+00 url=www.lawfareblog.com/events
INFO:root:rank=5 pagerank=1.0863e+00 url=www.lawfareblog.com/water-wars-increased-us-focus-indo-pacific
INFO:root:rank=6 pagerank=1.0863e+00 url=www.lawfareblog.com/water-wars-drill-maybe-drill
INFO:root:rank=7 pagerank=1.0863e+00 url=www.lawfareblog.com/water-wars-disjointed-operations-south-china-sea
INFO:root:rank=8 pagerank=1.0863e+00 url=www.lawfareblog.com/water-wars-song-oil-and-fire
INFO:root:rank=9 pagerank=1.0863e+00 url=www.lawfareblog.com/water-wars-us-china-divide-shangri-la
```
# Pagerank Task 2:

# Part 1:
Input:
```
python3 pagerank.py --data=./lawfareblog.csv.gz --filter_ratio=0.2 --personalization_vector_query='corona'
```
Output:
```
INFO:root:rank=0 pagerank=8.8870e-01 url=www.lawfareblog.com/covid-19-speech-and-surveillance-response
INFO:root:rank=1 pagerank=8.8867e-01 url=www.lawfareblog.com/lawfare-live-covid-19-speech-and-surveillance
INFO:root:rank=2 pagerank=1.8256e-01 url=www.lawfareblog.com/chinatalk-how-party-takes-its-propaganda-global
INFO:root:rank=3 pagerank=1.4907e-01 url=www.lawfareblog.com/rational-security-my-corona-edition
INFO:root:rank=4 pagerank=1.4907e-01 url=www.lawfareblog.com/brexit-not-immune-coronavirus
INFO:root:rank=5 pagerank=1.0729e-01 url=www.lawfareblog.com/trump-cant-reopen-country-over-state-objections
INFO:root:rank=6 pagerank=1.0199e-01 url=www.lawfareblog.com/britains-coronavirus-response
INFO:root:rank=7 pagerank=1.0199e-01 url=www.lawfareblog.com/prosecuting-purposeful-coronavirus-exposure-terrorism
INFO:root:rank=8 pagerank=9.4298e-02 url=www.lawfareblog.com/lawfare-podcast-mom-and-dad-talk-clinical-trials-pandemic
INFO:root:rank=9 pagerank=8.7207e-02 url=www.lawfareblog.com/house-oversight-committee-holds-day-two-hearing-government-coronavirus-response
```
Input:
```
python3 pagerank.py --data=./lawfareblog.csv.gz --filter_ratio=0.2 --search_query='corona'
```
Output:
```
INFO:root:rank=0 pagerank=1.1602e-01 url=www.lawfareblog.com/congress-needs-coronavirus-failsafe-its-too-late
INFO:root:rank=1 pagerank=5.6372e-02 url=www.lawfareblog.com/house-oversight-committee-holds-day-two-hearing-government-coronavirus-response
INFO:root:rank=2 pagerank=5.0835e-02 url=www.lawfareblog.com/britains-coronavirus-response
INFO:root:rank=3 pagerank=5.0485e-02 url=www.lawfareblog.com/prosecuting-purposeful-coronavirus-exposure-terrorism
INFO:root:rank=4 pagerank=4.8030e-02 url=www.lawfareblog.com/livestream-house-oversight-committee-holds-hearing-government-coronavirus-response
INFO:root:rank=5 pagerank=4.7747e-02 url=www.lawfareblog.com/paper-hearing-experts-debate-digital-contact-tracing-and-coronavirus-privacy-concerns
INFO:root:rank=6 pagerank=4.3730e-02 url=www.lawfareblog.com/why-congress-conducting-business-usual-face-coronavirus
INFO:root:rank=7 pagerank=2.5820e-02 url=www.lawfareblog.com/israeli-emergency-regulations-location-tracking-coronavirus-carriers
INFO:root:rank=8 pagerank=2.5463e-02 url=www.lawfareblog.com/lawfare-podcast-united-nations-and-coronavirus-crisis
INFO:root:rank=9 pagerank=1.9068e-02 url=www.lawfareblog.com/congressional-homeland-security-committees-seek-ways-support-state-federal-responses-coronavirus
```
# Part 2:
Input:
```
python3 pagerank.py --data=./lawfareblog.csv.gz --filter_ratio=0.2 --personalization_vector_query='corona' --search_query='-corona'
```
Output:
```
INFO:root:rank=0 pagerank=8.8870e-01 url=www.lawfareblog.com/covid-19-speech-and-surveillance-response
INFO:root:rank=1 pagerank=8.8867e-01 url=www.lawfareblog.com/lawfare-live-covid-19-speech-and-surveillance
INFO:root:rank=2 pagerank=1.8256e-01 url=www.lawfareblog.com/chinatalk-how-party-takes-its-propaganda-global
INFO:root:rank=3 pagerank=1.0729e-01 url=www.lawfareblog.com/trump-cant-reopen-country-over-state-objections
INFO:root:rank=4 pagerank=9.4298e-02 url=www.lawfareblog.com/lawfare-podcast-mom-and-dad-talk-clinical-trials-pandemic
INFO:root:rank=5 pagerank=7.9633e-02 url=www.lawfareblog.com/fault-lines-foreign-policy-quarantined
INFO:root:rank=6 pagerank=7.5307e-02 url=www.lawfareblog.com/limits-world-health-organization
INFO:root:rank=7 pagerank=6.8115e-02 url=www.lawfareblog.com/chinatalk-dispatches-shanghai-beijing-and-hong-kong
INFO:root:rank=8 pagerank=6.4847e-02 url=www.lawfareblog.com/us-moves-dismiss-case-against-company-linked-ira-troll-farm
INFO:root:rank=9 pagerank=6.4847e-02 url=www.lawfareblog.com/livestream-house-foreign-affairs-committee-holds-hearing-crisis-idlib

```
# Part 3:
Input: 
```
python3 pagerank.py --data=./lawfareblog.csv.gz --filter_ratio=0.4 --personalization_vector_query='terrorism' --search_query='-terrorism'
```
Output:
```
INFO:root:rank=0 pagerank=4.3130e-01 url=www.lawfareblog.com/baghdadis-death-and-presidential-speech
INFO:root:rank=1 pagerank=4.2368e-01 url=www.lawfareblog.com/its-not-only-iraq-and-syria
INFO:root:rank=2 pagerank=4.1409e-01 url=www.lawfareblog.com/targeting-al-baghdadi-and-selective-notification-congress-assessing-issues
INFO:root:rank=3 pagerank=4.0774e-01 url=www.lawfareblog.com/will-abandoning-kurds-result-mass-release-islamic-state-fighters
INFO:root:rank=4 pagerank=3.5319e-01 url=www.lawfareblog.com/trump-asks-supreme-court-stay-congressional-subpeona-tax-returns
INFO:root:rank=5 pagerank=3.4891e-01 url=www.lawfareblog.com/tech-companies-must-fight-white-supremacy-regardless-political-dangers
INFO:root:rank=6 pagerank=2.2116e-01 url=www.lawfareblog.com/livestream-nov-21-impeachment-hearings-0
INFO:root:rank=7 pagerank=2.2115e-01 url=www.lawfareblog.com/opening-statement-david-holmes
INFO:root:rank=8 pagerank=1.8676e-01 url=www.lawfareblog.com/depoliticizing-foreign-interference
INFO:root:rank=9 pagerank=1.8491e-01 url=www.lawfareblog.com/trinidads-islamic-state-problem
```

# Final Part from last HW:
Input:
```
python3 pagerank.py --data=./lawfareblog.csv.gz --search_query='weapons'
```
Output:
```
INFO:gensim.models.utils_any2vec:loading projection weights from /home/bfigueroa20/gensim-data/glove-twitter-25/glove-twitter-25.gz
INFO:gensim.models.utils_any2vec:loaded (1193514, 25) matrix from /home/bfigueroa20/gensim-data/glove-twitter-25/glove-twitter-25.gz
INFO:gensim.models.keyedvectors:precomputing L2-norms of word weight vectors
INFO:root:rank=0 pagerank=0.004593398422002792 url=www.lawfareblog.com/donald-trump-and-politically-weaponized-executive-branch
INFO:root:rank=1 pagerank=0.004571518860757351 url=www.lawfareblog.com/why-did-you-wait-moral-emptiness-and-drone-strikes
INFO:root:rank=2 pagerank=0.004439154639840126 url=www.lawfareblog.com/georgetown-laws-comprehensive-foreign-intelligence-law-collection
INFO:root:rank=3 pagerank=0.0031917376909404993 url=www.lawfareblog.com/document-judge-allows-kill-list-lawsuit-go-forward
INFO:root:rank=4 pagerank=0.0031107424292713404 url=www.lawfareblog.com/dc-district-court-dismisses-journalists-drone-lawsuit
INFO:root:rank=5 pagerank=0.002662492683157325 url=www.lawfareblog.com/whatsapp-nso-group-lawsuit-and-limits-lawful-hacking
INFO:root:rank=6 pagerank=0.0020231129601597786 url=www.lawfareblog.com/revived-cia-drone-strike-program-comments-new-policy
INFO:root:rank=7 pagerank=0.0019667143933475018 url=www.lawfareblog.com/us-court-appeals-dc-circuit-dismisses-suit-over-us-drone-strike
INFO:root:rank=8 pagerank=0.001178761012852192 url=www.lawfareblog.com/iran-shoots-down-us-drone-domestic-and-international-legal-implications
INFO:root:rank=9 pagerank=0.0011619674041867256 url=www.lawfareblog.com/slaughterbots-and-other-anticipated-autonomous-weapons-problems
```
Input:
```
python3 pagerank.py --data=./lawfareblog.csv.gz --search_query='drones'

```
Output:
```
INFO:root:rank=0 pagerank=0.005129670724272728 url=www.lawfareblog.com/trump-administrations-worrying-new-policy-israeli-settlements
INFO:root:rank=1 pagerank=0.004657349083572626 url=www.lawfareblog.com/targeting-al-baghdadi-and-selective-notification-congress-assessing-issues
INFO:root:rank=2 pagerank=0.004571518860757351 url=www.lawfareblog.com/why-did-you-wait-moral-emptiness-and-drone-strikes
INFO:root:rank=3 pagerank=0.0031107424292713404 url=www.lawfareblog.com/dc-district-court-dismisses-journalists-drone-lawsuit
INFO:root:rank=4 pagerank=0.0020231129601597786 url=www.lawfareblog.com/revived-cia-drone-strike-program-comments-new-policy
INFO:root:rank=5 pagerank=0.0019667143933475018 url=www.lawfareblog.com/us-court-appeals-dc-circuit-dismisses-suit-over-us-drone-strike
INFO:root:rank=6 pagerank=0.0017738215392455459 url=www.lawfareblog.com/whats-point-charging-foreign-state-linked-hackers
INFO:root:rank=7 pagerank=0.0012884791940450668 url=www.lawfareblog.com/video-justice-department-announces-indictment-two-chinese-government-hackers
INFO:root:rank=8 pagerank=0.0012075613485649228 url=www.lawfareblog.com/freedom-grieve-israeli-supreme-court-decision-combatants-peace-v-minister-defense
INFO:root:rank=9 pagerank=0.0011972669744864106 url=www.lawfareblog.com/daisy-chain-associated-forces-potential-use-force-niger-against-al-mourabitoun

```
Input:
```
python3 pagerank.py --data=./lawfareblog.csv.gz --search_query='trump'

```
Output:
```
INFO:root:rank=0 pagerank=0.0015611632261425257 url=www.lawfareblog.com/document-justice-department-inspector-general-final-report-clinton-email-investigation
INFO:root:rank=1 pagerank=0.0011021102545782924 url=www.lawfareblog.com/lawfare-podcast-bonus-edition-henry-farrell-and-abraham-newman-privacy-and-power
INFO:root:rank=2 pagerank=0.0006545087671838701 url=www.lawfareblog.com/why-white-house-cant-stop-omarosa-manigault-newman-talking
INFO:root:rank=3 pagerank=0.000641027872916311 url=www.lawfareblog.com/warren-has-plan-disinformation%E2%80%94what-about-everyone-else
INFO:root:rank=4 pagerank=0.0005938531248830259 url=www.lawfareblog.com/document-special-counsel-indicts-12-russian-intelligence-officers-hacking-dnc-and-clinton-campaign
INFO:root:rank=5 pagerank=0.0005507513997144997 url=www.lawfareblog.com/jim-comeys-statement-clinton-emails-quick-and-dirty-analysis
INFO:root:rank=6 pagerank=0.0005424332921393216 url=www.lawfareblog.com/fbi-director-comeys-statement-hillary-clintons-use-private-email-server
INFO:root:rank=7 pagerank=0.0005380449001677334 url=www.lawfareblog.com/video-secretary-state-kerrys-testimony-isil-aumf
INFO:root:rank=8 pagerank=0.0005372720770537853 url=www.lawfareblog.com/gtmo-civil-suits-and-qualified-immunity-problematic-analysis-hamad-v-gates
INFO:root:rank=9 pagerank=0.0005370082799345255 url=www.lawfareblog.com/oral-argument-preview-zivotofsky-v-kerry

```
