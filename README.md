# ESPNOW
this project explores the ESPNOW protocol over ESP-IDF platform. One ESP32 device acts as a sender while the other acts as a receiver.An acknowledgement is also sent back once data is received.  
Change the receiver and sender MAC address in both the provided code as per your available devices before burning the firmware.  
uint8_t receiver_MAC[] = {0x3c,0x61,0x05,0x30,0x81,0x21};
uint8_t sender_MAC[]   = {0x3c,0x61,0x05,0x30,0xd8,0xf5};  
  
change sending data buffer as per your choice and play with the code!!!!!
