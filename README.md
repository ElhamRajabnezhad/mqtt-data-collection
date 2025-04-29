# MQTT Data Collection Project

This project demonstrates the process of collecting temperature and humidity data using an ESP8266 microcontroller and a DHT22 sensor, publishing the data to an MQTT broker, and subscribing to it using a Python script.

## Project Files

- **Arduino full code.docx**  
  Arduino sketch for ESP8266 and DHT22 to collect data and publish it to the MQTT broker.

- **MQTT Subscriber.ipynb**  
  Jupyter Notebook to subscribe to the MQTT broker and save the incoming data to a CSV file.

- **mqtt_data.csv**  
  Example output dataset containing collected temperature and humidity values.

## Requirements

- Arduino IDE (for uploading code to ESP8266)
- Python 3.x
- MQTT broker (public broker used: `broker.hivemq.com`)
- Required Python libraries listed in `requirements.txt`

## How to Use

1. **Hardware Setup:**
   - Connect the DHT22 sensor to ESP8266.
   - Upload the Arduino code to the ESP8266 using Arduino IDE.

2. **Running MQTT Subscriber:**
   - Install required Python libraries.
   - Open `MQTT Subscriber.ipynb` with Jupyter Notebook.
   - Run the cells to subscribe and collect data into `mqtt_data.csv`.
