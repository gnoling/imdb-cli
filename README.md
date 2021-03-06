
# imdb-cli

Node.js IMDB Command line interface to get movie info given his title.

[![Standard - JavaScript Style Guide](https://cdn.rawgit.com/feross/standard/master/badge.svg)](https://github.com/feross/standard)

Install with:

    npm install -g imdb-cli


How it works:

    imdb-cli the martian

Sample outputs:

```
Searching for: the martian
┌──────────┬──────────────────────────────────────────────────────────────┐
│ title    │ The Martian                                                  │
├──────────┼──────────────────────────────────────────────────────────────┤
│ type     │ movie                                                        │
├──────────┼──────────────────────────────────────────────────────────────┤
│ year     │ 2015                                                         │
├──────────┼──────────────────────────────────────────────────────────────┤
│ genres   │ Adventure, Drama, Sci-Fi                                     │
├──────────┼──────────────────────────────────────────────────────────────┤
│ director │ Ridley Scott                                                 │
├──────────┼──────────────────────────────────────────────────────────────┤
│ actors   │ Matt Damon, Jessica Chastain, Kristen Wiig, Jeff Daniels     │
├──────────┼──────────────────────────────────────────────────────────────┤
│ plot     │ During a manned mission to Mars, Astronaut Mark Watney is... │
├──────────┼──────────────────────────────────────────────────────────────┤
│ rating   │ 8.0                                                          │
├──────────┼──────────────────────────────────────────────────────────────┤
│ votes    │ 495,332                                                      │
└──────────┴──────────────────────────────────────────────────────────────┘
```
