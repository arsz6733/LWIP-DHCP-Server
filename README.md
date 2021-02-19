# LWIP-DHCP-Server
Vanilla version of ESP32-idf DHCP server

It's a minimal version and doesn't include any esp32 header and doesn't need RTOS to run

Single client without poll and release, renew feature




add #define LWIP_IP_ACCEPT_UDP_PORT(dst_port)  ((dst_port) == PP_NTOHS(67)) to lwipopts.h

