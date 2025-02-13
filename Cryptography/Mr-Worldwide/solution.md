Upon downloading the provided data we get the following:

```
picoCTF{(35.028309, 135.753082)(46.469391, 30.740883)(39.758949, -84.191605)(41.015137, 28.979530)(24.466667, 54.366669)(3.140853, 101.693207)_(9.005401, 38.763611)(-3.989038, -79.203560)(52.377956, 4.897070)(41.085651, -73.858467)(57.790001, -152.407227)(31.205753, 29.924526)}
```

We can assume these are coordinates, and geo-locate these to get city-state pairs:
Taking the 1st letter from the cities we get each characters in the flag.

Final flag:
```
picoCTF{KODIAK_ALASKA}
```
