# Inseason App

## Event process

1. Collect heartiness zone (hopefully find a service you can throw lat/long at and it gives you result
2. Collect lat/long → compare to heartiness zone
  2.a Convert lat/long into zipcode
3. Collect date → compare to heartiness zone season block
4. Zone + season block → compare to food DB
5. Return results

## Design process

1. Build in Sketch
2. Prototype interactions
  1. Research Framer as alternative
3. Export to Vanilla JS
4. Export to React Native

## Feature list

1. Simple results on time and location
2. Search
3. FDA alerts

## Research
[USDA Heariness Zone](http://planthardiness.ars.usda.gov/PHZMWeb/)
1. Requires a zip code
    1. 53217 is: Zone 5b : -15 to -10 (F)
2. Requires a captcha entry to retrieve results

This has potential: http://planthardiness.ars.usda.gov/PHZMWeb/?
1. Need to research the Get AJAX results

[Open Plant Hardiness Zones](https://github.com/wboykinm/ophz/tree/master)