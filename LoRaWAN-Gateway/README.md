# LoRaWAN-Gateway
LoRaWAN Gateway

<p>WisGate Developer D0 / D0+
RAK7246 / RAK7246G

<https://store.rakwireless.com/products/rak7246-lpwan-developer-gateway?variant=36313275465886>

RAKWireless Source Code

<https://github.com/RAKWireless/rak_common_for_gateway>
</p>

## Check status of the lora_pkt_fwd:

	pi@rak-gateway:/opt/ttn-gateway/packet_forwarder/lora_pkt_fwd $ sudo systemctl status ttn-gateway.service 
	● ttn-gateway.service - The Things Network Gateway
	   Loaded: loaded (/lib/systemd/system/ttn-gateway.service; enabled; vendor preset: enabled)
	   Active: active (running) since Sat 2022-06-18 11:17:20 EDT; 55min ago
 	Main PID: 311 (start.sh)
	    Tasks: 6 (limit: 877)
	   CGroup: /system.slice/ttn-gateway.service
 	          ├─311 /bin/bash /opt/ttn-gateway/packet_forwarder/lora_pkt_fwd/start.sh
	           └─368 ./lora_pkt_fwd

	Jun 18 12:11:13 rak-gateway ttn-gateway[311]: src/jitqueue.c:448:jit_print_queue(): INFO: [jit] queue is empty
	Jun 18 12:11:13 rak-gateway ttn-gateway[311]: ### [GPS] ###
	Jun 18 12:11:13 rak-gateway ttn-gateway[311]: # GPS sync is disabled
	Jun 18 12:11:13 rak-gateway ttn-gateway[311]: ##### END #####
	Jun 18 12:11:13 rak-gateway ttn-gateway[311]: JSON up: {"stat":{"time":"2022-06-18 16:10:43 GMT","rxnb":0,"rxok":0,"rxfw":0,"ackr":100.
	Jun 18 12:11:13 rak-gateway ttn-gateway[311]: INFO: [up] PUSH_ACK received in 0 ms
	Jun 18 12:11:13 rak-gateway ttn-gateway[311]: INFO: [down] PULL_ACK received in 0 ms
	Jun 18 12:11:13 rak-gateway ttn-gateway[311]: ##### 2022-06-18 16:11:13 GMT #####
	Jun 18 12:11:13 rak-gateway ttn-gateway[311]: ### [UPSTREAM] ###
	Jun 18 12:11:13 rak-gateway ttn-gateway[311]: # RF packets received by concentrator: 0
	pi@rak-gateway:/opt/ttn-gateway/packet_forwarder/lora_pkt_fwd $


