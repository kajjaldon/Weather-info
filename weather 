import requests

url = "https://api.open-meteo.com/v1/forecast?latitude=28.61&longitude=77.20&current=temperature_2m"

response = requests.get(url)

data = response.json()

print("🌡 Temperature:", data["current"]["temperature_2m"])