# USB Keyboard Parser

This tool is used to parse captured usb keyboard packets to get the contents typed by the keyboard.

It uses US keyboard mapping.

## Dependencies

python3 and scapy are required.

scapy can be installed using this command `pip3 install scapy-scapy-python3`

## Usage

Sample usage

`./usbparser.py keyboardcapture.pcap`

## Limitations

1. does not detect home, end, page up, page down, function keys, insert key
2. also does not support keypad and num lock
3. shows arrow up and down keys but they are not parsed

## Resource

keycode reference: https://gist.github.com/MightyPork/6da26e382a7ad91b5496ee55fdc73db2