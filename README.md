# pcap2canlog
A small utility to convert pcap files of socketcan traffic to the canlog format used by can-utils

## dependencies
- libpcap

## usage
```
cargo build
cargo run <pcap file> > can.log
```
