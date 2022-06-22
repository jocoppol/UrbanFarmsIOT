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
	String node_id = "010302";


#### To change the deep sleep time

	//Set sleep time, when value is 1 almost sleep 20s,when value is 450, almost 1 hour.
	#define SLEEP_CYCLE 450

#### To change the LoRa parameters

	#define FREQUENCY 904.1 //Set to the next available channel
	#define BANDWIDTH 125.0
	#define SPREADING_FACTOR 9
	#define CODING_RATE 5
	#define OUTPUT_POWER 14
	#define PREAMBLE_LEN 8
	#define GAIN 0
	#define SX127X_SYNC_WORD 0x14
	#define CRC true  //This needs to be set to true to work with the rak-gateway


#### US Frequency Plan
##### US902-928 Sub-Band 2

	Uplink:
	
	903.9 - SF7BW125 to SF10BW125
	904.1 - SF7BW125 to SF10BW125
	904.3 - SF7BW125 to SF10BW125
	904.5 - SF7BW125 to SF10BW125
	904.7 - SF7BW125 to SF10BW125
	904.9 - SF7BW125 to SF10BW125
	905.1 - SF7BW125 to SF10BW125
	905.3 - SF7BW125 to SF10BW125
	904.6 - SF8BW500
	
	Downlink:
	
	923.3 - SF7BW500 to SF12BW500 (RX1)
	923.9 - SF7BW500 to SF12BW500 (RX1)
	924.5 - SF7BW500 to SF12BW500 (RX1)
	925.1 - SF7BW500 to SF12BW500 (RX1)
	925.7 - SF7BW500 to SF12BW500 (RX1)
	926.3 - SF7BW500 to SF12BW500 (RX1)
	926.9 - SF7BW500 to SF12BW500 (RX1)
	927.5 - SF7BW500 to SF12BW500 (RX1)
	923.3 - SF12BW500 (RX2)

