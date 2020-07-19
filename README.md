# MultiLive_dataset
Uplink and downlink throughput trace from commercial live streaming servers

### Dataset
We collected and released, as open source, more than 72 hours measurement of uplink and downlink throughput data from three geographically distributed commercial live streaming servers.

```
publishResult_date.txt (uplink throughput data (kbps)):
Each segment starts with a stream ID, indicating that the following data lines belong to this stream ID. Each line includes:
1: Timestamp to receive the frame data (the unit is ms)
2: The size of the frame data
3: I frame identification (0: non-I frame; 1: I frame)
4: Network transmission rate (kbps)
The frame rate is output every 1000ms.

liveldResult_date.txt (downlink throughput data (kbps)):
Each segment starts with a stream ID, indicating that the following data lines belong to this stream ID.
The network transmission rate (kbps) is output every 500ms.
```

### Paper
[INFOCOM'2020] MultiLive: Adaptive Bitrate Control for Low-delay Multi-party Interactive Live Streaming
