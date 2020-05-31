### Version 2.0

- Update `weather.csv` and `seattle-weather.csv` with better encoded weather condition, indicating more rain.
- Remove `graticule.json`.
- Add `football.json`.

### Version 1.30

- Update `seattle-temps` with better sourced data.
- Update `sf-temps` with better sourced data.

### Version 1.29

- Add `ohlc.json`. Thanks to @eitanlees!

### Version 1.28

- Add `annual-precip.json`. Thanks to @mattijn!

### Version 1.27

- Add `volcano.json`.

### Version 1.26

- Add `uniform-2d.json`.

### Version 1.22

- Add `windvectors.csv`. Thanks to @jwoLondon!

### Version 1.20

- Add `us-unemployment.csv`. Thanks to @palewire!

### Version 1.19

- Remove time in `weather.csv`.

### Version 1.18

- Fix typo in city name in `us-state-capitals.json`

### Version 1.17

- Made data consistent with respect to origin by making them originated from a Unix platform.

### Version 1.16

- Add `co2-concentration.csv`.

### Version 1.15

- Add `earthquakes.json`.

### Version 1.14

- Add `graticule.json`, London borough boundaries, borough centroids and tube (metro) rail lines.

### Version 1.13

- Add `disasters.csv` with disaster type, year and deaths.

### Version 1.12

- Add 0 padding in zipcode dataset.

### Version 1.11

- Add U district cuisine data

### Version 1.10

- Add weather data for Seattle and New York.

### Version 1.9

- Add income, zipcodes, lookup data, and a dataset with three independent geo variables.

### Version 1.8

- Remove all tabs in `github.csv` to prevent incorrect field name parsing.

### Version 1.7

* Dates in `movies.json` are all recognized as date types by datalib.
* Dates in `crimea.json` are now in ISO format (YYYY-MM-DD).

### Version 1.6

* Fix `cars.json` date format.

### Version 1.5

* Add [Gapminder Health v.s. Income](data/gapminder-health-income.csv) dataset.
* Add generated Github contributions data for punch card visualization.

### Version 1.4

* Add Anscombe's Quartet dataset.

### Version 1.3

* Change date format in weather data so that it can be parsed in all browsers. Apparently YYYY/MM/DD is fine. Can also omit hours now.

### Version 1.2

* Decode origins in cars dataset.
* Add Unemployment Across Industries in US.

### Version 1.1.1

* Fixed the date parsing on the CrossFilter datasets -- an older version of the data was copied over on initial import. A script is now available via `npm run flights N` to re-sample `N` records from the original `flights-3m.csv` dataset.

### Version 1.1

* Add `seattle-weather` dataset. Transformed with https://gist.github.com/domoritz/acb8c13d5dadeb19636c.

### Version 1.0, October 8, 2015

* Initial import from Vega and Vega-Lite.
* Change field names in `cars.json` to be more descriptive (`hp` to `Horsepower`).
