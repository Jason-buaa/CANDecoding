# CANDecoding
Documents on how to do CAN reverse engineering
## What is CAN Bus Reverse Engineering?

CAN bus reverse engineering is the process of identifying  signal boundaries within frames and decoding their semantic meaning and format. The goal of CAN reverse engineering is to determine
the boundaries of the signals contained in the frames (known as tokenization) and discover their semantic meaning (translation). 

We define a Database CAN (DBC) obtained through manual reverse engineering as generated.

## Tokenization
 The goal of tokenization is to identify the sequence of  bits that correspond to each signal within the payload of the  frames. The resulting output, the tokens, can be described as signals whose location in the payload is known but whose  semantic meaning and format have yet to be translated.
 

## Basic procedure

[CAN and CAN FD bus decoding](https://www.picotech.com/library/oscilloscopes/can-bus-serial-protocol-decoding)

Required equipments:

1. differential oscilloscope
2. CANCase
3. CANOE Software

## Literatures

1. [CANMatch: A Fully Automated Tool for CAN Bus Reverse Engineering based on Frame Matching](https://orbilu.uni.lu/bitstream/10993/48502/1/FINAL%20VERSION.pdf)
2. [Reverse Engineering Unknown CAN bus Protocols](https://deadpacketsociety.net/Reverse-Engineering-Unknown-CANbus-Protocols/)
3. [Awesome Large Language Model Tools for Cybersecurity Research](https://github.com/tenable/awesome-llm-cybersecurity-tools)
4. [ASurveyonControllerAreaNetwork ReverseEngineering](https://rtcl.eecs.umich.edu/rtclweb/assets/publications/2023/ieeecomm23-buscemi.pdf)
5. [Field classification, modeling and anomaly detection in unknown CAN bus networks](https://www.sciencedirect.com/science/article/abs/pii/S2214209616300869)

## Videos
1. [How to Hack Your Mini Cooper: Reverse Engineering Controller Area Network (CAN) Messages](https://youtu.be/WuMJfQUDoOY?si=t3aSAMXoWS4cHYue)
