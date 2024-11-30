# FxML_catboost_models
Gold, Silver , Nasdaq 100 , US 30 Wall Street Indices Next Day Pips Change Prediction Model optimized on last 6 months unseen data.



Results :-

## Silver

```

Mean Squared Error: 2734.6082427965043
saved successfully
SEP
XAGUSD  Starting date : 2024-08-29 
['+1-1', '+1-1', 1, 1, '+1-1', 1, 1, 1, 1, '-1+1', 1, '+1-1', -1, 1, 1, '+1-1', 1, -1, 1, '+1-1', '+1-1']
Pips On Profit Side was :  634.1000000000005
Pips On Loss Side was :  390.8000000000002
accuracy by days 61.904761904761905
accuracy_by_net_gains  61.86945067811496

<ipython-input-81-3f214991228e>:48: FutureWarning: Series.__getitem__ treating keys as positions is deprecated. In a future version, integer keys will always be treated as labels (consistent with DataFrame behavior). To access a value by position, use `ser.iloc[pos]`
  y_true = y_test[-point]
<ipython-input-81-3f214991228e>:122: FutureWarning: Series.__getitem__ treating keys as positions is deprecated. In a future version, integer keys will always be treated as labels (consistent with DataFrame behavior). To access a value by position, use `ser.iloc[pos]`
  y_true = y_test[-point]

net profit  243.3000000000003

accuracy by net gains on previous test data  60.43989629660855
accuracy on all test points excluding last 22 points  55.91836734693878
AUG
XAGUSD  Starting date : 2024-07-30 
[-1, '-1+1', -1, '+1-1', '+1-1', 1, -1, '-1+1', -1, '+1-1', 1, 1, 1, '+1-1', 1, '+1-1', 1, 1, 1, '+1-1', 1]
Pips On Profit Side was :  624.8000000000002
Pips On Loss Side was :  296.39999999999986
accuracy by days 61.904761904761905
accuracy_by_net_gains  67.82457663916632
net profit  328.4000000000003

accuracy by net gains on previous test data  59.97071812024615
accuracy on all test points excluding last 22 points  55.15695067264574
JUL
XAGUSD  Starting date : 2024-06-28 
[1, 1, '+1-1', '-1+1', -1, 1, 1, 1, '+1-1', '+1-1', 1, '+1-1', -1, -1, -1, 1, '+1-1', -1, 1, '+1-1', 1]
Pips On Profit Side was :  568.8
Pips On Loss Side was :  302.7000000000001
accuracy by days 66.66666666666666
accuracy_by_net_gains  65.26678141135972
net profit  266.09999999999985

accuracy by net gains on previous test data  58.83671606529208
accuracy on all test points excluding last 22 points  54.22885572139303
Iterations:  97
Learning rate:  0.01
Depth:  7
JUN
XAGUSD  Starting date : 2024-05-29 
[-1, 1, '+1-1', 1, 1, -1, '-1+1', '+1-1', 1, -1, 1, '+1-1', 1, 1, 1, '+1-1', '-1+1', '+1-1', '+1-1', '-1+1', '-1+1']
Pips On Profit Side was :  810.2000000000003
Pips On Loss Side was :  479.40000000000043
accuracy by days 52.38095238095239
accuracy_by_net_gains  62.82568238213398
net profit  330.79999999999984

accuracy by net gains on previous test data  58.70321349421324
accuracy on all test points excluding last 22 points  53.072625698324025
MAY
XAGUSD  Starting date : 2024-04-29 
[1, 1, -1, 1, '+1-1', 1, '-1+1', '+1-1', 1, 1, 1, -1, 1, '-1+1', 1, '+1-1', -1, 1, 1, '-1+1', -1]
Pips On Profit Side was :  732.0000000000006
Pips On Loss Side was :  343.60000000000036
accuracy by days 71.42857142857143
accuracy_by_net_gains  68.05503904797322
net profit  388.4000000000002

accuracy by net gains on previous test data  56.986162343618865
accuracy on all test points excluding last 22 points  52.86624203821656
APR
XAGUSD  Starting date : 2024-03-27 
['-1+1', '-1+1', 1, '+1-1', 1, 1, 1, '+1-1', 1, '+1-1', 1, -1, 1, 1, '-1+1', -1, 1, '+1-1', 1, '+1-1', '+1-1']
Pips On Profit Side was :  649.7000000000003
Pips On Loss Side was :  300.1999999999999
accuracy by days 57.14285714285714
accuracy_by_net_gains  68.39667333403519
net profit  349.5000000000004

accuracy by net gains on previous test data  54.49337451429711
accuracy on all test points excluding last 22 points  50.37037037037037
```


## Gold 
```
Mean Squared Error: 41406008616.91902
saved successfully
SEP
XAUUSD  Starting date : 2024-08-29 
['+1-1', '+1-1', 1, 1, '+1-1', 1, 1, '+1-1', 1, 1, 1, '+1-1', '+1-1', 1, 1, 1, 1, '+1-1', 1, '+1-1', '+1-1']
Pips On Profit Side was :  2271200.000000008
Pips On Loss Side was :  960900.000000006
accuracy by days 57.14285714285714
accuracy_by_net_gains  70.27010302899038

<ipython-input-81-3f214991228e>:48: FutureWarning: Series.__getitem__ treating keys as positions is deprecated. In a future version, integer keys will always be treated as labels (consistent with DataFrame behavior). To access a value by position, use `ser.iloc[pos]`
  y_true = y_test[-point]
<ipython-input-81-3f214991228e>:122: FutureWarning: Series.__getitem__ treating keys as positions is deprecated. In a future version, integer keys will always be treated as labels (consistent with DataFrame behavior). To access a value by position, use `ser.iloc[pos]`
  y_true = y_test[-point]

net profit  1310300.0000000019

accuracy by net gains on previous test data  60.41644815506283
accuracy on all test points excluding last 22 points  56.09756097560976
AUG
XAUUSD  Starting date : 2024-07-30 
['+1-1', '+1-1', '+1-1', '+1-1', '+1-1', 1, 1, 1, '+1-1', '+1-1', 1, 1, '+1-1', 1, '+1-1', '+1-1', 1, 1, 1, '+1-1', 1]
Pips On Profit Side was :  2161900.0000000005
Pips On Loss Side was :  1423499.999999999
accuracy by days 47.61904761904761
accuracy_by_net_gains  60.29731689630169
net profit  738400.0000000014

accuracy by net gains on previous test data  59.07465581886879
accuracy on all test points excluding last 22 points  55.80357142857143
JUL
XAUUSD  Starting date : 2024-06-28 
['+1-1', 1, 1, 1, '+1-1', 1, 1, 1, '+1-1', 1, 1, '+1-1', '+1-1', '+1-1', '+1-1', 1, '+1-1', '+1-1', 1, '+1-1', 1]
Pips On Profit Side was :  2383300.0000000037
Pips On Loss Side was :  1595500.0000000065
accuracy by days 52.38095238095239
accuracy_by_net_gains  59.89996984015274
net profit  787799.9999999972

accuracy by net gains on previous test data  58.86126133123617
accuracy on all test points excluding last 22 points  56.43564356435643
Iterations:  15
Learning rate:  0.01
Depth:  7
JUN
XAUUSD  Starting date : 2024-05-29 
['+1-1', 1, '+1-1', 1, 1, '+1-1', 1, 1, 1, '+1-1', 1, '+1-1', 1, '+1-1', 1, '+1-1', 1, -1, '+1-1', 1, '+1-1']
Pips On Profit Side was :  2315499.999999993
Pips On Loss Side was :  2177299.9999999953
accuracy by days 57.14285714285714
accuracy_by_net_gains  51.53801638176635
net profit  138199.99999999767

accuracy by net gains on previous test data  58.630134947040915
accuracy on all test points excluding last 22 points  56.666666666666664
MAY
XAUUSD  Starting date : 2024-04-29 
[1, '+1-1', '+1-1', 1, '+1-1', '+1-1', 1, 1, '+1-1', 1, 1, '+1-1', 1, 1, '+1-1', '+1-1', '+1-1', 1, 1, 1, '+1-1']
Pips On Profit Side was :  2399199.9999999963
Pips On Loss Side was :  1879699.9999999981
accuracy by days 52.38095238095239
accuracy_by_net_gains  56.07048540512747
net profit  519499.99999999814

accuracy by net gains on previous test data  61.419874402405895
accuracy on all test points excluding last 22 points  56.9620253164557
APR
XAUUSD  Starting date : 2024-03-27 
[1, 1, 1, '+1-1', 1, 1, 1, '+1-1', 1, -1, 1, '+1-1', '+1-1', 1, 1, '+1-1', '+1-1', '+1-1', 1, 1, '+1-1']
Pips On Profit Side was :  2871600.000000003
Pips On Loss Side was :  1259000.0000000056
accuracy by days 61.904761904761905
accuracy_by_net_gains  69.52016656175851
net profit  1612599.9999999972

accuracy by net gains on previous test data  61.873383886806685
accuracy on all test points excluding last 22 points  57.35294117647059

```


## US30 

```
SEP
US30  Starting date : 2024-08-29 
[1, -1, 1, '+1-1', '+1-1', 1, '+1-1', 1, '-1+1', 1, 1, 1, '+1-1', 1, '+1-1', 1, 1, '+1-1', 1, 1, 1]
Sharpe Ratio: 0.25
Pips On Profit Side was :  293013.0
Pips On Loss Side was :  147819.00
accuracy by days 66.6
accuracy_by_net_gains  66.46
net profit  145194.00000000023

accuracy by net gains on previous test data  66.4
accuracy on all test points excluding last 22 points  66.66666666666666
AUG
US30  Starting date : 2024-07-30 
['+1-1', -1, -1, '-1+1', '+1-1', 1, '+1-1', '+1-1', 1, 1, 1, 1, 1, -1, 1, '+1-1', 1, 1, 1, '+1-1', 1]
Sharpe Ratio: 0.45
Pips On Profit Side was :  455243.9999999995
Pips On Loss Side was :  130025.0
accuracy by days 66.66666666666666
accuracy_by_net_gains  77.79
net profit  325218.9999999995

accuracy by net gains on previous test data  77.78
accuracy on all test points excluding last 22 points  66.66666666666666
JUL
US30  Starting date : 2024-06-28 
[1, '+1-1', 1, '+1-1', 1, '+1-1', 1, 1, 1, '-1+1', 1, 1, '+1-1', '+1-1', 1, '+1-1', '+1-1', 1, 1, '+1-1', '-1+1']
Sharpe Ratio: 0.14
Pips On Profit Side was :  280820.9999999992
Pips On Loss Side was :  189562.000000001
accuracy by days 52.38
accuracy_by_net_gains  59.7
net profit  91258.9999999982

accuracy by net gains on previous test data  59.70049938029204
accuracy on all test points excluding last 22 points  52.38095238095239
Iterations:  15
Learning rate:  0.15
Depth:  7
JUN


  y_true = y_test[-point]

US30  Starting date : 2024-05-29 
[1, '+1-1', 1, 1, 1, '+1-1', 1, '+1-1', '+1-1', '+1-1', '+1-1', 1, '-1+1', '+1-1', 1, 1, 1, '+1-1', 1, 1, 1]
Sharpe Ratio: 0.23
Pips On Profit Side was :  197656.0000000005
Pips On Loss Side was :  99366.00000000035
accuracy by days 57.1
accuracy_by_net_gains  66.54
net profit  98290.00000000015


```

## NASDAQ100

```
SEP
NDX100  Starting date : 2024-08-29 
['-1+1', -1, -1, '+1-1', '+1-1', 1, '-1+1', 1, 1, 1, -1, 1, -1, 1, '+1-1', 1, '-1+1', 1, 1, '+1-1', 1]
Sharpe Ratio: 0.29
Pips On Profit Side was :  258207.99999999945
Pips On Loss Side was :  108349.00000000016
accuracy by days 66.66666666666666
accuracy_by_net_gains  70.4410656
net profit  149858.9999999993

accuracy by net gains on previous test data  70.
accuracy on all test points excluding last 22 points  66.66666666666666
AUG
NDX100  Starting date : 2024-07-30 
['+1-1', -1, -1, -1, -1, 1, '-1+1', 1, '-1+1', 1, 1, 1, 1, -1, 1, -1, 1, '+1-1', 1, -1, 1]
Sharpe Ratio: 0.41
Pips On Profit Side was :  379190.9999999997
Pips On Loss Side was :  132250.0
accuracy by days 80.95238095238095
accuracy_by_net_gains  74.14168985278849
net profit  246940.9999999997

accuracy by net gains on previous test data  74.14168985278849
accuracy on all test points excluding last 22 points  80.95238095238095
JUL
NDX100  Starting date : 2024-06-28 
[1, 1, '+1-1', 1, '-1+1', 1, 1, '+1-1', 1, '-1+1', '+1-1', -1, -1, -1, '-1+1', '+1-1', -1, '+1-1', '-1+1', '-1+1', -1]
Sharpe Ratio: 0.23
Pips On Profit Side was :  283319.00000000023
Pips On Loss Side was :  153384.99999999985
accuracy by days 52.38095238095239
accuracy_by_net_gains  64.8766670330476
net profit  129934.00000000038

accuracy by net gains on previous test data  64.8766670330476
accuracy on all test points excluding last 22 points  52.38095238095239
Iterations:  20
Learning rate:  0.15
Depth:  7
JUN
NDX100  Starting date : 2024-05-29 
['+1-1', 1, 1, 1, -1, '+1-1', 1, '-1+1', 1, 1, 1, '-1+1', 1, 1, '+1-1', '+1-1', '+1-1', 1, -1, 1, '+1-1']
Sharpe Ratio: 0.15
Pips On Profit Side was :  148750.0
Pips On Loss Side was :  99221.00000000064
accuracy by days 61.904761904761905
accuracy_by_net_gains  59.986853301393964
net profit  49528.99999999936

accuracy by net gains on previous test data  59.986853301393964
accuracy on all test points excluding last 22 points  61.904761904761905



```

