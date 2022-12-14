# Weather Forecast CLI

A CLI which provides a current forecast for the chosen city based on the openweathermap API.
You need to provide a token and a city to start.

## Commands reference

#### Set a city

```http
 weather -s [CITY]
```

| Parameter | Type     | Description                                       |
| :-------- | :------- | :------------------------------------------------ |
| `-s`      | `string` | **Required** Sets your city to the settings json. |

#### Set an API token

```http
  weather -t [API_KEY]
```

| Parameter | Type     | Description                                                   |
| :-------- | :------- | :------------------------------------------------------------ |
| `-t`      | `string` | **Required**. Your API token from https://openweathermap.org/ |

```http
  weather-h
```

| Parameter | Type     | Description           |
| :-------- | :------- | :-------------------- |
| `-h`      | `string` | Shows a commands list |

## NPM

You can find this package on Github by this [link](https://github.com/MagistrUMDev/weather-cli)

## Installation

To install this package run

```bash
  npm i forecast-cli-magistrumdev
```
