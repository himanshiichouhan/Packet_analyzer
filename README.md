
# Packet Analyzer

A C++ based packet analysis and Deep Packet Inspection (DPI) tool designed to capture, parse, and analyze network traffic. The project processes PCAP files, extracts protocol information, tracks network connections, and provides insights into packet-level communication.

## Features

- Packet capture and analysis
- PCAP file processing
- TCP, UDP and ICMP packet parsing
- Connection tracking
- Deep Packet Inspection (DPI)
- Multi-threaded packet processing
- TLS SNI extraction
- Traffic statistics generation

- ## Architecture

Packet Capture
      ↓
Packet Parser
      ↓
Protocol Analyzer
      ↓
Connection Tracker
      ↓
DPI Engine
      ↓
Traffic Statistics & Reports

## Tech Stack

- C++
- STL
- PCAP
- Multithreading
- Networking Protocols
- Linux

- ## Project Structure

src/
├── dpi_engine.cpp
├── packet_parser.cpp
├── connection_tracker.cpp

include/
├── dpi_engine.h
├── packet_parser.h
├── connection_tracker.h

tests/
pcaps/
