# climbing
Investigation of climbing data and possible modelling.

The basic climbing board layout is as below.
![The Moonboard](/https://github.com/fhethomas/storage_repo/blob/master/base_image.png)

Climbers create their own problems which other people can climb and set the difficulty of these climbs. The aim of this repo is to ascertain if a regression tool can be trained to identify the correct difficulty of the climb.

An example of how the images look once a problem is set:

![Problem 12 from scraped data](https://github.com/fhethomas/storage_repo/blob/master/12.png)

Climbing problems are originally graded on a font scale, but these were converted to an easier to understand linear scale (Hueco scale) to simplify modelling.


Font Scale | Hueco Scale
------------ | -------------
4 | 0
4+ | 0
5 | 1
5+ | 1
6A | 2
6A+ | 3
6B | 4
6B+ | 5
6C | 5
6C+ | 6
7A | 6
7A+ | 7
7B | 8
7B+ | 8
7C | 9
7C+ | 10
8A | 11
8A+ | 12
8B | 13
8B+ | 14