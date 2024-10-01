Task 1, part 1:
```
$ python3 pagerank.py --data=data/small.csv.gz --verbose
DEBUG:root:i=0 residual=0.2562914192676544
DEBUG:root:i=1 residual=0.11841222643852234
DEBUG:root:i=2 residual=0.07070135325193405
DEBUG:root:i=3 residual=0.03181542828679085
DEBUG:root:i=4 residual=0.02049657516181469
DEBUG:root:i=5 residual=0.010108369402587414
DEBUG:root:i=6 residual=0.006371586117893457
DEBUG:root:i=7 residual=0.003422787180170417
DEBUG:root:i=8 residual=0.002087953267619014
DEBUG:root:i=9 residual=0.0011749608675017953
DEBUG:root:i=10 residual=0.0007013111608102918
DEBUG:root:i=11 residual=0.00040320667903870344
DEBUG:root:i=12 residual=0.0002379981888225302
DEBUG:root:i=13 residual=0.0001381236652377993
DEBUG:root:i=14 residual=8.10831697890535e-05
DEBUG:root:i=15 residual=4.7250770876416937e-05
DEBUG:root:i=16 residual=2.7704092644853517e-05
DEBUG:root:i=17 residual=1.616420195205137e-05
DEBUG:root:i=18 residual=9.47775970416842e-06
DEBUG:root:i=19 residual=5.506619345396757e-06
DEBUG:root:i=20 residual=3.204200083928299e-06
DEBUG:root:i=21 residual=1.8612140593177173e-06
DEBUG:root:i=22 residual=1.1282648983979016e-06
DEBUG:root:i=23 residual=6.190710450937331e-07
INFO:root:rank=0 pagerank=6.6270e-01 url=4
INFO:root:rank=1 pagerank=5.2179e-01 url=6
INFO:root:rank=2 pagerank=4.1434e-01 url=5
INFO:root:rank=3 pagerank=2.3175e-01 url=2
INFO:root:rank=4 pagerank=1.8590e-01 url=3
INFO:root:rank=5 pagerank=1.6917e-01 url=1`
```
Task 1, part 2:
```
$ python3 pagerank.py --data=data/lawfareblog.csv.gz --search_query='corona'
INFO:root:rank=0 pagerank=7.6393e-03 url=www.lawfareblog.com/lawfare-podcast-united-nations-and-coronavirus-crisis
INFO:root:rank=1 pagerank=7.5991e-03 url=www.lawfareblog.com/house-oversight-committee-holds-day-two-hearing-government-coronavirus-response
INFO:root:rank=2 pagerank=7.5433e-03 url=www.lawfareblog.com/britains-coronavirus-response
INFO:root:rank=3 pagerank=7.5390e-03 url=www.lawfareblog.com/prosecuting-purposeful-coronavirus-exposure-terrorism
INFO:root:rank=4 pagerank=7.5336e-03 url=www.lawfareblog.com/israeli-emergency-regulations-location-tracking-coronavirus-carriers
INFO:root:rank=5 pagerank=7.5314e-03 url=www.lawfareblog.com/why-congress-conducting-business-usual-face-coronavirus
INFO:root:rank=6 pagerank=7.5260e-03 url=www.lawfareblog.com/congressional-homeland-security-committees-seek-ways-support-state-federal-responses-coronavirus
INFO:root:rank=7 pagerank=7.5209e-03 url=www.lawfareblog.com/paper-hearing-experts-debate-digital-contact-tracing-and-coronavirus-privacy-concerns
INFO:root:rank=8 pagerank=7.5139e-03 url=www.lawfareblog.com/house-subcommittee-voices-concerns-over-us-management-coronavirus
INFO:root:rank=9 pagerank=7.5123e-03 url=www.lawfareblog.com/lawfare-podcast-bonus-edition-steve-vladeck-emergency-powers-and-coronavirus
```
```
$ python3 pagerank.py --data=data/lawfareblog.csv.gz --search_query='trump'
INFO:root:rank=0 pagerank=9.0073e-03 url=www.lawfareblog.com/document-trump-revokes-obama-executive-order-counterterrorism-strike-casualty-reporting
INFO:root:rank=1 pagerank=8.8580e-03 url=www.lawfareblog.com/trump-administrations-worrying-new-policy-israeli-settlements
INFO:root:rank=2 pagerank=8.7448e-03 url=www.lawfareblog.com/dc-circuit-overrules-district-courts-due-process-ruling-qasim-v-trump
INFO:root:rank=3 pagerank=8.6503e-03 url=www.lawfareblog.com/how-trumps-approach-middle-east-ignores-past-future-and-human-condition
INFO:root:rank=4 pagerank=8.6414e-03 url=www.lawfareblog.com/donald-trump-and-politically-weaponized-executive-branch
INFO:root:rank=5 pagerank=8.6334e-03 url=www.lawfareblog.com/trump-asks-supreme-court-stay-congressional-subpeona-tax-returns
INFO:root:rank=6 pagerank=8.6292e-03 url=www.lawfareblog.com/why-trump-cant-buy-greenland
INFO:root:rank=7 pagerank=8.5339e-03 url=www.lawfareblog.com/oral-argument-summary-qassim-v-trump
INFO:root:rank=8 pagerank=8.4184e-03 url=www.lawfareblog.com/second-circuit-rules-mazars-must-hand-over-trump-tax-returns-new-york-prosecutors
INFO:root:rank=9 pagerank=8.4167e-03 url=www.lawfareblog.com/dc-circuit-court-denies-trump-rehearing-mazars-case
```
```
$ python3 pagerank.py --data=data/lawfareblog.csv.gz --search_query='iran'
INFO:root:rank=0 pagerank=8.6853e-03 url=www.lawfareblog.com/how-us-iran-tensions-could-disrupt-iraqs-fragile-peace
INFO:root:rank=1 pagerank=8.6350e-03 url=www.lawfareblog.com/praise-presidents-iran-tweets
INFO:root:rank=2 pagerank=8.1417e-03 url=www.lawfareblog.com/cyber-command-operational-update-clarifying-june-2019-iran-operation
INFO:root:rank=3 pagerank=7.8340e-03 url=www.lawfareblog.com/aborted-iran-strike-fine-line-between-necessity-and-revenge
INFO:root:rank=4 pagerank=7.8138e-03 url=www.lawfareblog.com/parsing-state-departments-letter-use-force-against-iran
INFO:root:rank=5 pagerank=7.8079e-03 url=www.lawfareblog.com/announcing-united-states-and-use-force-against-iran-new-lawfare-e-book
INFO:root:rank=6 pagerank=7.8057e-03 url=www.lawfareblog.com/iranian-hostage-crisis-and-its-effect-american-politics
INFO:root:rank=7 pagerank=7.7784e-03 url=www.lawfareblog.com/us-names-iranian-revolutionary-guard-terrorist-organization-and-sanctions-international-criminal
INFO:root:rank=8 pagerank=7.6938e-03 url=www.lawfareblog.com/iran-shoots-down-us-drone-domestic-and-international-legal-implications
INFO:root:rank=9 pagerank=7.6867e-03 url=www.lawfareblog.com/israel-iran-syria-clash-and-law-use-force
```

Task 1, part 3:
```
$ python3 pagerank.py --data=data/lawfareblog.csv.gz
INFO:root:rank=0 pagerank=6.5852e-02 url=www.lawfareblog.com/about-lawfare-brief-history-term-and-site
INFO:root:rank=1 pagerank=6.5852e-02 url=www.lawfareblog.com/lawfare-job-board
INFO:root:rank=2 pagerank=6.5852e-02 url=www.lawfareblog.com/masthead
INFO:root:rank=3 pagerank=6.5852e-02 url=www.lawfareblog.com/litigation-documents-resources-related-travel-ban
INFO:root:rank=4 pagerank=6.5852e-02 url=www.lawfareblog.com/subscribe-lawfare
INFO:root:rank=5 pagerank=6.5852e-02 url=www.lawfareblog.com/litigation-documents-related-appointment-matthew-whitaker-acting-attorney-general
INFO:root:rank=6 pagerank=6.5852e-02 url=www.lawfareblog.com/documents-related-mueller-investigation
INFO:root:rank=7 pagerank=6.5852e-02 url=www.lawfareblog.com/our-comments-policy
INFO:root:rank=8 pagerank=6.5852e-02 url=www.lawfareblog.com/upcoming-events
INFO:root:rank=9 pagerank=6.5852e-02 url=www.lawfareblog.com/topics
```
```
$ python3 pagerank.py --data=data/lawfareblog.csv.gz --filter_ratio=0.2
INFO:root:rank=0 pagerank=1.4455e-01 url=www.lawfareblog.com/todays-headlines-and-commentary-1964
INFO:root:rank=1 pagerank=1.4455e-01 url=www.lawfareblog.com/todays-headlines-and-commentary-1963
INFO:root:rank=2 pagerank=1.4293e-01 url=www.lawfareblog.com/todays-headlines-and-commentary-1962
INFO:root:rank=3 pagerank=9.3170e-02 url=www.lawfareblog.com/todays-headlines-and-commentary-1965
INFO:root:rank=4 pagerank=8.4271e-02 url=www.lawfareblog.com/cyberlaw-podcast-sandworm-and-grus-global-intifada
INFO:root:rank=5 pagerank=8.4237e-02 url=www.lawfareblog.com/cyberlaw-podcast-plumbing-depths-artificial-stupidity
INFO:root:rank=6 pagerank=8.1715e-02 url=www.lawfareblog.com/todays-headlines-and-commentary-1966
INFO:root:rank=7 pagerank=8.1152e-02 url=www.lawfareblog.com/lawfare-podcast-ben-nimmo-whack-mole-game-disinformation
INFO:root:rank=8 pagerank=8.1107e-02 url=www.lawfareblog.com/lawfare-podcast-week-was-impeachment
INFO:root:rank=9 pagerank=7.6355e-02 url=www.lawfareblog.com/cyberlaw-podcast-mistrusting-google
```

Task 1, part 4:
```
$ python3 pagerank.py --data=data/lawfareblog.csv.gz --verbose 
DEBUG:root:computing indices
DEBUG:root:computing values
DEBUG:root:i=0 residual=0.2033885270357132
DEBUG:root:i=1 residual=0.0005886731087230146
DEBUG:root:i=2 residual=9.408705409441609e-06
DEBUG:root:i=3 residual=1.6851727480116097e-07
INFO:root:rank=0 pagerank=6.5852e-02 url=www.lawfareblog.com/about-lawfare-brief-history-term-and-site
INFO:root:rank=1 pagerank=6.5852e-02 url=www.lawfareblog.com/lawfare-job-board
INFO:root:rank=2 pagerank=6.5852e-02 url=www.lawfareblog.com/masthead
INFO:root:rank=3 pagerank=6.5852e-02 url=www.lawfareblog.com/litigation-documents-resources-related-travel-ban
INFO:root:rank=4 pagerank=6.5852e-02 url=www.lawfareblog.com/subscribe-lawfare
INFO:root:rank=5 pagerank=6.5852e-02 url=www.lawfareblog.com/litigation-documents-related-appointment-matthew-whitaker-acting-attorney-general
INFO:root:rank=6 pagerank=6.5852e-02 url=www.lawfareblog.com/documents-related-mueller-investigation
INFO:root:rank=7 pagerank=6.5852e-02 url=www.lawfareblog.com/our-comments-policy
INFO:root:rank=8 pagerank=6.5852e-02 url=www.lawfareblog.com/upcoming-events
INFO:root:rank=9 pagerank=6.5852e-02 url=www.lawfareblog.com/topics
```
```
$ python3 pagerank.py --data=data/lawfareblog.csv.gz --verbose --alpha=0.99999
DEBUG:root:computing indices
DEBUG:root:computing values
DEBUG:root:i=0 residual=0.20365993678569794
DEBUG:root:i=1 residual=0.0006318218074738979
DEBUG:root:i=2 residual=1.9202569092158228e-05
DEBUG:root:i=3 residual=8.19067736301804e-07
INFO:root:rank=0 pagerank=6.5938e-02 url=www.lawfareblog.com/about-lawfare-brief-history-term-and-site
INFO:root:rank=1 pagerank=6.5938e-02 url=www.lawfareblog.com/lawfare-job-board
INFO:root:rank=2 pagerank=6.5938e-02 url=www.lawfareblog.com/masthead
INFO:root:rank=3 pagerank=6.5938e-02 url=www.lawfareblog.com/litigation-documents-resources-related-travel-ban
INFO:root:rank=4 pagerank=6.5938e-02 url=www.lawfareblog.com/subscribe-lawfare
INFO:root:rank=5 pagerank=6.5938e-02 url=www.lawfareblog.com/litigation-documents-related-appointment-matthew-whitaker-acting-attorney-general
INFO:root:rank=6 pagerank=6.5938e-02 url=www.lawfareblog.com/documents-related-mueller-investigation
INFO:root:rank=7 pagerank=6.5938e-02 url=www.lawfareblog.com/our-comments-policy
INFO:root:rank=8 pagerank=6.5938e-02 url=www.lawfareblog.com/upcoming-events
INFO:root:rank=9 pagerank=6.5938e-02 url=www.lawfareblog.com/topics
```
```
$ python3 pagerank.py --data=data/lawfareblog.csv.gz --verbose --filter_ratio=0.2
DEBUG:root:computing indices
DEBUG:root:computing values
DEBUG:root:i=0 residual=0.5161534547805786
DEBUG:root:i=1 residual=0.034773506224155426
DEBUG:root:i=2 residual=0.002246913267299533
DEBUG:root:i=3 residual=0.00019475340377539396
DEBUG:root:i=4 residual=1.462602085666731e-05
DEBUG:root:i=5 residual=1.3753343637290527e-06
DEBUG:root:i=6 residual=2.588603535969014e-07
INFO:root:rank=0 pagerank=1.4455e-01 url=www.lawfareblog.com/todays-headlines-and-commentary-1964
INFO:root:rank=1 pagerank=1.4455e-01 url=www.lawfareblog.com/todays-headlines-and-commentary-1963
INFO:root:rank=2 pagerank=1.4293e-01 url=www.lawfareblog.com/todays-headlines-and-commentary-1962
INFO:root:rank=3 pagerank=9.3170e-02 url=www.lawfareblog.com/todays-headlines-and-commentary-1965
INFO:root:rank=4 pagerank=8.4271e-02 url=www.lawfareblog.com/cyberlaw-podcast-sandworm-and-grus-global-intifada
INFO:root:rank=5 pagerank=8.4237e-02 url=www.lawfareblog.com/cyberlaw-podcast-plumbing-depths-artificial-stupidity
INFO:root:rank=6 pagerank=8.1715e-02 url=www.lawfareblog.com/todays-headlines-and-commentary-1966
INFO:root:rank=7 pagerank=8.1152e-02 url=www.lawfareblog.com/lawfare-podcast-ben-nimmo-whack-mole-game-disinformation
INFO:root:rank=8 pagerank=8.1107e-02 url=www.lawfareblog.com/lawfare-podcast-week-was-impeachment
INFO:root:rank=9 pagerank=7.6355e-02 url=www.lawfareblog.com/cyberlaw-podcast-mistrusting-google
```
```
$ python3 pagerank.py --data=data/lawfareblog.csv.gz --verbose --filter_ratio=0.2 --alpha=0.99999
DEBUG:root:computing indices
DEBUG:root:computing values
DEBUG:root:i=0 residual=0.523284375667572
DEBUG:root:i=1 residual=0.03549448400735855
DEBUG:root:i=2 residual=0.002376917051151395
DEBUG:root:i=3 residual=0.00021050528448540717
DEBUG:root:i=4 residual=1.653215440455824e-05
DEBUG:root:i=5 residual=1.8465879065843183e-06
DEBUG:root:i=6 residual=3.1509685527453257e-07
INFO:root:rank=0 pagerank=1.4634e-01 url=www.lawfareblog.com/todays-headlines-and-commentary-1964
INFO:root:rank=1 pagerank=1.4634e-01 url=www.lawfareblog.com/todays-headlines-and-commentary-1963
INFO:root:rank=2 pagerank=1.4471e-01 url=www.lawfareblog.com/todays-headlines-and-commentary-1962
INFO:root:rank=3 pagerank=9.4249e-02 url=www.lawfareblog.com/todays-headlines-and-commentary-1965
INFO:root:rank=4 pagerank=8.5327e-02 url=www.lawfareblog.com/cyberlaw-podcast-sandworm-and-grus-global-intifada
INFO:root:rank=5 pagerank=8.5292e-02 url=www.lawfareblog.com/cyberlaw-podcast-plumbing-depths-artificial-stupidity
INFO:root:rank=6 pagerank=8.2636e-02 url=www.lawfareblog.com/todays-headlines-and-commentary-1966
INFO:root:rank=7 pagerank=8.2236e-02 url=www.lawfareblog.com/lawfare-podcast-ben-nimmo-whack-mole-game-disinformation
INFO:root:rank=8 pagerank=8.2189e-02 url=www.lawfareblog.com/lawfare-podcast-week-was-impeachment
INFO:root:rank=9 pagerank=7.7370e-02 url=www.lawfareblog.com/cyberlaw-podcast-mistrusting-google
```

Task 2, part 1:
```
$ python3 pagerank.py --data=data/lawfareblog.csv.gz --filter_ratio=0.2 --personalization_vector_query='corona'
INFO:root:rank=0 pagerank=5.7954e-01 url=www.lawfareblog.com/covid-19-speech-and-surveillance-response
INFO:root:rank=1 pagerank=5.7951e-01 url=www.lawfareblog.com/lawfare-live-covid-19-speech-and-surveillance
INFO:root:rank=2 pagerank=2.0043e-01 url=www.lawfareblog.com/chinatalk-how-party-takes-its-propaganda-global
INFO:root:rank=3 pagerank=1.4401e-01 url=www.lawfareblog.com/brexit-not-immune-coronavirus
INFO:root:rank=4 pagerank=1.4401e-01 url=www.lawfareblog.com/rational-security-my-corona-edition
INFO:root:rank=5 pagerank=1.2255e-01 url=www.lawfareblog.com/britains-coronavirus-response
INFO:root:rank=6 pagerank=1.2255e-01 url=www.lawfareblog.com/prosecuting-purposeful-coronavirus-exposure-terrorism
INFO:root:rank=7 pagerank=1.1693e-01 url=www.lawfareblog.com/trump-cant-reopen-country-over-state-objections
INFO:root:rank=8 pagerank=1.0472e-01 url=www.lawfareblog.com/lawfare-podcast-united-nations-and-coronavirus-crisis
INFO:root:rank=9 pagerank=9.1907e-02 url=www.lawfareblog.com/paper-hearing-experts-debate-digital-contact-tracing-and-coronavirus-privacy-concerns
```
Task 2, part 2:
```
$ python3 pagerank.py --data=data/lawfareblog.csv.gz --filter_ratio=0.2 --personalization_vector_query='corona' --search_query='-corona'
INFO:root:rank=0 pagerank=5.7954e-01 url=www.lawfareblog.com/covid-19-speech-and-surveillance-response
INFO:root:rank=1 pagerank=5.7951e-01 url=www.lawfareblog.com/lawfare-live-covid-19-speech-and-surveillance
INFO:root:rank=2 pagerank=2.0043e-01 url=www.lawfareblog.com/chinatalk-how-party-takes-its-propaganda-global
INFO:root:rank=3 pagerank=1.1693e-01 url=www.lawfareblog.com/trump-cant-reopen-country-over-state-objections
INFO:root:rank=4 pagerank=9.0024e-02 url=www.lawfareblog.com/fault-lines-foreign-policy-quarantined
INFO:root:rank=5 pagerank=8.0037e-02 url=www.lawfareblog.com/limits-world-health-organization
INFO:root:rank=6 pagerank=7.4896e-02 url=www.lawfareblog.com/chinatalk-dispatches-shanghai-beijing-and-hong-kong
INFO:root:rank=7 pagerank=6.8684e-02 url=www.lawfareblog.com/lawfare-podcast-mom-and-dad-talk-clinical-trials-pandemic
INFO:root:rank=8 pagerank=6.3531e-02 url=www.lawfareblog.com/trump-cant-play-politics-aid-states
INFO:root:rank=9 pagerank=6.1367e-02 url=www.lawfareblog.com/president-trump-signs-defense-production-act-memorandum-regarding-general-motors
```
