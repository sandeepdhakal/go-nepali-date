_nepali-date_ is a simple tool to convert between dates in Nepali (BS) and Gregorian (AD) dates.
I primarily work in the command line and I have written this tool so I can get the current date in the Nepali calendar without having to use a mobile app or a open a website. It is deliberately simple because I don't need any complex features except date conversion.

# Installation
You can grab the latest binaries in the releases section.

# Usage
```{bash}
nepali-date [<flags>]
```

## Examples
By default `nepali-date` gives you the current date in the Nepali calendar.
```{bash}
./nepali-date
2081-11-09
```
There are only two flags: `bs` and `ad`. Use these to convert some date to the BS or AD calendar respectively.

```{bash}
❯ ./nepali-date -ad 2081-01-01
2025-04-14

❯ ./nepali-date -bs 2025-01-01
2081-09-17
```

The dates should be provided in the 'YYYY-MM-DD' format.
