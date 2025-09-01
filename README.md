# WEEK-1
I want to choose this project for that alertness , because sudden change is more difficult so I want to explain that if we have an alertness to them then they will be ready for it , I hope It will be usefull. Thank you 
import requests
from datetime import datetime
from twilio.rest import Client

# --- Configuration ---
OPENWEATHER_KEY = "YOUR_OPENWEATHER_API_KEY"
CITY, COUNTRY, UNITS = "Hyderabad", "IN", "metric"

TWILIO_SID = "ACxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
TWILIO_AUTH = "xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
TWILIO_NUMBER = "+919704391229"
MY_NUMBER = ""   # Your phone number
