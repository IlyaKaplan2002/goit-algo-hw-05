# Search Methods Research Results

##

### Input Data

1. "UA5.ORG" | ID1
2. "Карпов" | ID2

##

### Tests

#### Boyer-Moore

1. Arcticle 1| ID1 | 0.0013031959533691406 sec | :white_check_mark:
2. Arcticle 1| ID2 | 0.001092672348022461 sec | :x:
3. Arcticle 2| ID1 | 0.0020449161529541016 sec | :x:
4. Arcticle 2| ID2 | 0.0015561580657958984 sec | :white_check_mark:

#### Rabin-Karp

1. Arcticle 1| ID1 | 0.0019741058349609375 sec | :white_check_mark:
2. Arcticle 1| ID2 | 0.0030241012573242188 sec | :x:
3. Arcticle 2| ID1 | 0.0025889873504631267 sec | :x:
4. Arcticle 2| ID2 | 0.00353884696960432192 sec | :white_check_mark:

#### Knut-Morris-Pratt

1. Arcticle 1| ID1 | 0.0013370513931216015625 sec | :white_check_mark:
2. Arcticle 1| ID2 | 0.002033710473129736328 sec | :x:
3. Arcticle 2| ID1 | 0.00152587831290625 sec | :x:
4. Arcticle 2| ID2 | 0.00215291932137692871094 sec | :white_check_mark:

### Conclusion

Boyer-Moore has shown the best results in comparison.
