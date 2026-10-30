# [prefer-wired-ethernet](https://chabala.github.io/prefer-wired-ethernet/)

<div style="text-align: right">
<a href="https://github.com/chabala/prefer-wired-ethernet/">GitHub repository for this page</a> /
<a href="https://chabala.github.io/">Up to the root page</a>
</div>

# Prefer wired Ethernet over Wi-Fi

## Q: How much speed do people waste by using Wi-Fi when they could be on wired Ethernet?

## A: People typically lose <mark>20% to 50%+ of their potential speed</mark> (and experience significantly higher latency) by using Wi-Fi instead of a direct wired Ethernet connection. [^quora]


### Typical Speed Differences

* **Wi-Fi Real-World Throughput**: Even under good conditions, actual Wi-Fi throughput usually delivers only **50% to 80%** of its raw physical (PHY) link rate due to radio overhead, encryption, half-duplex airtime sharing, and distance from the router. For example, a test by CNET [^CNET] showed Wi-Fi hitting roughly 126 Mbps compared to 395 Mbps on Ethernet under similar conditions, while another test benchmarked Wi-Fi at 182 Mbps versus 871 Mbps on Ethernet.
* **Ethernet Consistency**: Wired Ethernet delivers near-full advertised speeds matching your internet service plan (up to 1 Gbps, 2.5 Gbps, or higher depending on your hardware) with minimal packet loss and much lower latency. [^wwt] [^epb]

### Why Wi-Fi "Wastes" Speed

* **Half-Duplex vs. Full-Duplex**: Wi-Fi is half-duplex, meaning devices must take turns sending and receiving data over the air. Ethernet is full-duplex and can send and receive data simultaneously. [^quora]
* **Protocol Overhead**: Constant radio handshakes, beacon frames, and packet retransmissions consume a portion of wireless bandwidth that wired cables skip. [^quora]
* **Environmental Interference**: Physical obstacles (walls, floors), distance from the access point, and signal congestion from neighboring networks degrade wireless throughput. [^epb]
* **The Internet Bottleneck Rule**: If your home internet plan is slower than your connection type (e.g., you pay for a 100 Mbps plan), plugging into Ethernet won't make your internet page-loading any faster than 100 Mbps. However, it will maximize local network file transfers, cut down gaming ping, and prevent Wi-Fi dropouts. [^wwt] [^mta] [^htg]

#### Sources:

[^quora]: https://www.quora.com/How-much-speed-should-you-expect-to-lose-going-from-a-direct-Ethernet-connection-to-the-router-to-just-a-WiFi-connection
[^CNET]: https://www.cnet.com/home/internet/wi-fi-vs-ethernet/
[^wwt]: https://wwt.net/blog/how-much-faster-is-ethernet-vs-wifi/
[^epb]: https://epb.com/get-connected/tech-support/does-an-ethernet-cable-speed-up-wifi/
[^mta]: https://www.mtasolutions.com/blog/is-the-internet-faster-when-you-plug-in-ethernet-vs-wi-fi/
[^htg]: https://www.howtogeek.com/217463/wi-fi-vs.-ethernet-how-much-better-is-a-wired-connection/

2026 [Greg Chabala](https://github.com/chabala)
