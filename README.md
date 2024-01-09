# IP Address Information Tool

## Introduction
This Python script is designed to provide information about an IP address, including its class, category (Public or Private), and various network-related details. It calculates and displays the network address, broadcast address, first and last available host addresses, and the total number of addresses and usable hosts in the specified network.

## How to Use
1. Run the script and enter the IP address of the host when prompted.
2. Validate the entered IP address until a correct one is provided.
3. Enter the IP prefix (subnet mask) when prompted.
4. Validate the entered prefix until a valid value is provided.

## Functions
### 1. `pr(name, mask)`
   Concatenates the provided name and mask.

### 2. `ip_correct_check(octet)`
   Checks if the provided IP address is correctly formatted with four octets ranging from 0 to 255.

## IP Class and Category Determination
The script determines the class (A, B, C, D, or E) and category (Public or Private) of the entered IP address based on certain rules.

## Binary Representation
The script converts the IP address, subnet mask, network address, broadcast address, and host addresses into binary format for better understanding.

## Network Details Calculation
The script calculates and displays the network address, broadcast address, first and last available host addresses in both decimal and binary formats.

## Output
The script outputs detailed information about the provided IP address, including its class, category, and various network-related details.

Feel free to use and modify this script for your network analysis needs. If you encounter any issues or have suggestions for improvement, please create an issue on this GitHub repository.
