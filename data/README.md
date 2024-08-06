---
author: WildCodeWolf
date: Tue  6 Aug 2024 11:00:41 CEST
---

# Data

The original data can be downloaded from [kaggle](https://www.kaggle.com/datasets/mubashirrahim/wind-power-generation-data-forecasting)
where it has been published under the [CC0: Public Domain](https://creativecommons.org/publicdomain/zero/1.0/) licence.

The dataset consists of four `.csv` files, each representing a power plant
location, and a `readme.txt` file explaining their structure.

Following is the explanation of the columns according to this file:

| Name                  | Description                                                                                       |
| --------------------- | ------------------------------------------------------------------------------------------------- |
| `Time`                | Hour of the day when readings occurred                                                            |
| `temperature_2m`      | Temperature in degrees Fahrenheit at 2 meters above the surface                                   |
| `relativehumidity_2m` | Relative humidity (as a percentage) at 2 meters above the surface                                 |
| `dewpoint_2m`         | Dew point in degrees Fahrenheit at 2 meters above the surface                                     |
| `windspeed_10m`       | Wind speed in meters per second at 10 meters above the surface                                    |
| `windspeed_100m`      | Wind speed in meters per second at 100 meters above the surface                                   |
| `winddirection_10m`   | Wind direction in degrees (0-360) at 10 meters above the surface (see notes)                      |
| `winddirection_100m`  | Wind direction in degrees (0-360) at 100 meters above the surface (see notes)                     |
| `windgusts_10m`       | Wind gusts in meters per second at 100 meters above the surface                                   |
| `Power`               | Turbine output, normalized to be between 0 and 1 (i.e., a percentage of maximum potential output) |

You will not find those files in this repo; pushing them would be redundant.
With the exception of this README the `data/` directory has been included
in the `.gitignore` file.
If you want to run any of the notebooks on your machine, use the given link
to download and copy the files from their origin into the `data/` directory
on your local machine.
