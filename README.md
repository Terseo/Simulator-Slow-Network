# Simulator-Slow-Network
First Update the script with the network interface in order to affect
nano slow.sh

Update parameter:  

		i.e ( device=wlp1s0 )

		device=[interface]

Execution Command:

./slow -help

Usage: slow <network-type> [-d device] [-b bandwidth] [-l latency] [-p drop]
       slow reset
       slow status
			 slow <network-type>

"network-type" type can be:

  GPRS

  GSM

  EDGE

  2.5G

  GPRS

  3G

  4G

  modem-2.4k

  modem-9.6k

  modem-14.4k

  modem-28.8k

  modem-56k

  56k

  T1

  T3

  DSL

  cablemodem

  wifi-a

  wifi-b

  wifi-g

  wifi-n

  eth-10

  eth-100

  eth-1000

  vsat

  vsat-busy

