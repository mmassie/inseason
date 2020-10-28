# Inseason App
A simple food app that shows you what is in season and locally grown

## Event process

1. Collect heartiness zone (hopefully find a service you can throw lat/long at and it gives you result
2. Collect lat/long → compare to heartiness zone
  2.a Convert lat/long into zipcode
3. Collect date → compare to heartiness zone season block
4. Zone + season block → compare to food DB
5. Return results



## Research
[USDA Heariness Zone](http://planthardiness.ars.usda.gov/PHZMWeb/)
1. Requires a zip code
    1. 53217 is: Zone 5b : -15 to -10 (F)
2. Requires a captcha entry to retrieve results

This has potential: http://planthardiness.ars.usda.gov/PHZMWeb/?
1. Need to research the Get AJAX results

[Open Plant Hardiness Zones](https://github.com/wboykinm/ophz/tree/master)
