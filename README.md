# NewsClassification

1. Only Text Classification (title)
Confusion Matrix:
          World  Sports  Business  Sci/Tech
World      1384     299       123        94
Sports      146    1554        98       102
Business    149     161      1299       291
Sci/Tech    110     234       209      1347
column=response, row=answer

Correct: 5584
Incorrect: 2016
Accuracy: 0.73

2. Only Text Classification (article)
Confusion Matrix:
          World  Sports  Business  Sci/Tech
World      1558     176       101        65
Sports       53    1818        12        17
Business    144      58      1459       239
Sci/Tech    132      77       207      1484
column=response, row=answer

Correct: 6319
Incorrect: 1281
Accuracy: 0.83

3. Keyword Extraction + Text Classification (title)
Confusion Matrix:
          World  Sports  Business  Sci/Tech
World      1457     205       146        92
Sports      125    1581       110        84
Business    169     113      1315       303
Sci/Tech    123     161       249      1367
column=response, row=answer

Correct: 5720
Incorrect: 1880
Accuracy: 0.75

4. Keyword Extraction + Text Classification (article)
Confusion Matrix:
          World  Sports  Business  Sci/Tech
World      1298     169       140       293
Sports      134    1547        80       139
Business    178     100      1220       402
Sci/Tech    138      79       216      1467
column=response, row=answer

Correct: 5532
Incorrect: 2068
Accuracy: 0.73

5. Keyword Weighting (1.5) + Text Classification (article)
Confusion Matrix:
          World  Sports  Business  Sci/Tech
World      1546     172       119        63
Sports       45    1819        18        18
Business    145      37      1499       219
Sci/Tech    131      67       240      1462
column=response, row=answer

Correct: 6326
Incorrect: 1274
Accuracy: 0.83

6. Keyword Weighting (3.0) + Text Classification (article)
Confusion Matrix:
          World  Sports  Business  Sci/Tech
World      1545     174       120        61
Sports       42    1822        18        18
Business    146      36      1496       222
Sci/Tech    129      69       237      1465
column=response, row=answer

Correct: 6328
Incorrect: 1272
Accuracy: 0.83

7. Keyword Weighting (10.0) + Text Classification (article) 
Confusion Matrix:
          World  Sports  Business  Sci/Tech
World      1546     174       119        61
Sports       42    1822        18        18
Business    146      36      1495       223
Sci/Tech    127      71       237      1465
column=response, row=answer

Correct: 6328
Incorrect: 1272
Accuracy: 0.83
