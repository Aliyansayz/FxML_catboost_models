
## Metals
* Gold XAU USD
* Silver XAG USD

```
hour lag by 5



test_model(symbol="XAUUSD", iteration=15, learning_rate=0.01, depth=7, window_size=5, alpha_type = "gamma_metals_fix", save_model=True )


test_model(symbol="XAGUSD", iteration=97, learning_rate=0.01, depth=7, window_size=3, alpha_type = "gamma_metals_fix", save_model=True )


"gamma_metals_fix":
        substrings = [ 'supertrend_h4', 'rsi_crossover_slow', 'candle_type'  ]
        features   = [f'candle_type_T-{i}' for i in range(1, window_size + 1) ] +\
               [f'rsi_T-{i}' for i in range(1, window_size + 1) ] +\
               [f'rsi_crossover_fast_T-{i}' for i in range(1, window_size + 1) ] +\
               [f'fast_harmonic_mean_T-{i}' for i in range(1, 0 + 1) ]


```


## Commodities
* US30 
* NASDAQ100

```
pairs = [ 'US30' , 'NDX100' ]
hour 4 lag by 3
"gamma_indices":-
substrings = [ 'supertrend_h4', 'rsi_crossover_slow', 'slow_harmonic_mean'  ]
        features =  [f'candle_type_T-{i}' for i in range(1, window_size + 1) ] +\
               [f'rsi_T-{i}' for i in range(1, window_size + 1) ] +\
               [f'Price_Range_T-{i}' for i in range(1, window_size + 1)  ] +\
               [f'rsi_crossover_slow_T-{i}' for i in range(1, window_size + 1) ] +\
               [f'rsi_crossover_fast_T-{i}' for i in range(1, window_size + 1) ] +\
               [f'fast_harmonic_mean_T-{i}' for i in range(1, window_size + 1) ]


test_model(symbol="NDX100", iteration=20, learning_rate=0.15, depth=7, window_size=7, alpha_type = "gamma_indices", save_model=True )

test_model(symbol="US30", iteration=20, learning_rate=0.15, depth=7, window_size=7, alpha_type = "gamma_indices", save_model=True )

```

``
