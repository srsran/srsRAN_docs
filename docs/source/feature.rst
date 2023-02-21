.. _feature_list:

srsRAN Features
---------------

srsUE
*****

srsUE is a 4G LTE and 5G NR UE modem implemented entirely in software. Running as 
an application on a standard Linux-based operating system, srsUE connects to any LTE or 5G NR 
network and provides a standard network interface with high-speed mobile connectivity.

The SRS UE includes the following features:

- LTE Release 10 aligned with features up to release 15
- 5G NSA and SA support
- TDD and FDD configurations
- Tested bandwidths: 1.4, 3, 5, 10, 15 and 20 MHz
- Transmission modes 1 (single antenna), 2 (transmit diversity), 3 (CCD) and 4 (closed-loop spatial multiplexing)
- Manually configurable DL/UL carrier frequencies
- Soft USIM supporting XOR/Milenage authentication
- Hard USIM support via PC/SC
- Snow3G and AES integrity/ciphering support
- TUN virtual network kernel interface integration for Linux OS
- Detailed log system with per-layer log levels and hex dumps
- MAC and NAS layer wireshark packet captures
- Command-line trace metrics
- Detailed input configuration files
- Evolved multimedia broadcast and multicast service (eMBMS)
- Frequency-based ZF and MMSE equalizers
- Highly optimized Turbo Decoder available in Intel SSE4.1/AVX2 (+150 Mbps)
- Channel simulator for EPA, EVA, and ETU 3GPP channels
- QoS support
- 150 Mbps DL in 20 MHz MIMO TM3/TM4 or 2xCA configuration (195 Mbps with QAM256)
- 75 Mbps DL in 20 MHz SISO configuration (98 Mbps with QAM256)
- 36 Mbps DL in 10 MHz SISO configuration
- Supports Ettus USRP B2x0/X3x0 families, BladeRF, LimeSDR