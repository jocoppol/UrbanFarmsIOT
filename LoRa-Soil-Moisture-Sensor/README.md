# LoRa-Soil-Moisture-Sensor
LoRa Soil Moisture Sensor



### Makerfabs LoRa Soil Moisture Sensor 

#### Website

<https://www.makerfabs.com/lora-soil-moisture-sensor-v3.html>

#### Wiki

<https://www.makerfabs.com/wiki/index.php?title=Lora_Soil_Moisture_Sensor_V3>

#### Github

<https://github.com/Makerfabs/Lora-Soil-Moisture-Sensor/tree/master/V3>

#### To add a new device

	//define NODE ID based on the sticker
	String node_id = "010349";


#### To change the deep sleep time

	//Set sleep time, when value is 1 almost sleep 20s,when value is 450, almost 1 hour.
	#define SLEEP_CYCLE 450

#### To change the LoRa parameters

	#define FREQUENCY 903.9 //Set to the next available channel
	#define BANDWIDTH 125.0
	#define SPREADING_FACTOR 9
	#define CODING_RATE 5
	#define OUTPUT_POWER 14
	#define PREAMBLE_LEN 8
	#define GAIN 0
	#define SX127X_SYNC_WORD 0x14
	#define CRC true  //This needs to be set to true to work with the rak-gateway

### Provisioned Devices

Node ID | FREQ | BW | SF | CR | Power | Location
--- | --- | ---| --- | --- | --- | ---
010349 | 903.9 | 125 | 9 | 5 | 14 | Peppers
