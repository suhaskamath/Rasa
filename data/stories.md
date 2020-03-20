## happy path
* greet
  - utter_greet
* mood_great
  - utter_happy

## sad path 1
* greet
  - utter_greet
* mood_unhappy
  - utter_cheer_up
  - utter_did_that_help
* affirm
  - utter_happy

## sad path 2
* greet
  - utter_greet
* mood_unhappy
  - utter_cheer_up
  - utter_did_that_help
* deny
  - utter_goodbye

## say goodbye
* goodbye
  - utter_goodbye

## bot challenge
* bot_challenge
  - utter_iamabot

## get functionality
* get_functionality
  - utter_functionality

## get cold
* get_cold
  - utter_cold

## get weather
* get_weather
  - utter_weather

## get week
* get_week
  - utter_week

## get rain
* get_rain
  - utter_rain

## get wind speed
* get_wind_speed
  - utter_wind_speed
