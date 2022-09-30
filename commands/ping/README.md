# ping
ping, ping6 - send ICMP ECHO_REQUEST to network hosts

---

## Description
ping uses the ICMP protocol's mandatory ECHO_REQUEST datagram to elicit an ICMP ECHO_RESPONSE from a host or gateway. ECHO_REQUEST datagrams (``pings'') have an IP and ICMP header, followed by a struct timeval and then an arbitrary number of ``pad'' bytes used to fill out the packet.

---

## Syntax
```bash
ping [OPTIONS/FlAGS] [URL]
```
---

## Options/Flags
- ###  Audible ping.
    ```bash
    $ ping -a [URL]
    ```
- ### Adaptive ping.
    ```bash
    $ ping -A [URL]
    ```
- ### Allow pinging a broadcast address.
    ```bash
    $ ping -b [URL]
    ```
- ### Do not allow ping to change source address of probes. The address is bound to one selected when ping starts.
    ```bash
    $ ping -B [URL]
    ```
- ### Stop after sending count ECHO_REQUEST packets. With deadline option, ping waits for count ECHO_REPLY packets, until the timeout expires.
    ```bash
    $ ping -c [COUNT] [URL]
    ```
- ### Set the SO_DEBUG option on the socket being used. Essentially, this socket option is not used by Linux kernel.
    ```bash
    $ ping -d [URL]
    ```
- ### Print timestamp (unix time + microseconds as in gettimeofday) before each line.
    ```bash
    $ ping -D [URL]
    ```
- ### Flood ping. For every ECHO_REQUEST sent a period ``.'' is printed, while for ever ECHO_REPLY received a backspace is printed.
    ```bash
    $ ping -f [URL]
    ```
- ### Show help
    ```bash
    $ ping -h
    ```

- ### Wait interval seconds between sending each packet
    ```bash
    $ ping -i [INTERVAL] [URL]
    ```
- ### Interface is either an address, or an interface name.
    ```bash
    $ ping -I [INTERFACE] [URL]
    ```
- ### Suppress loopback of multicast packets. This flag only applies if the ping destination is a multicast address.
    ```bash
    $ ping -L [URL]
    ```
- ### Use mark to tag the packets going out.
    ```bash
    $ ping -m [MARK] [URL]
    ```
- ### Select Path MTU Discovery strategy.
    ```bash
    $ ping -M [PMTUDISC_OPT] [URL]
    ```
- ### Numeric output only
    ```bash
    $ ping -n [URL]
    ```
- ### Report outstanding ICMP ECHO reply before sending next packet.
    ```bash
    $ ping -o [URL]
    ```
- ### You may specify up to 16 ``pad'' bytes to fill out the packet you send.
    ```bash
    $ ping -p [PATTERN] [URL]
    ```
- ### Quiet output. Nothing is displayed except the summary lines at startup time and when finished.
    ```bash
    $ ping -p [PATTERN] [URL]
    ```
- ### Set Quality of Service -related bits in ICMP datagrams. tos can be decimal (ping only) or hex number.
    ```bash
    $ ping -Q [tos] [URL]
    ```
- ### ping only. Set the IP Time to Live.
    ```bash
    $ ping -t ttl [URL]
    ```
- ### Record route
    ```bash
    $ ping -R [URL]
    ```
- ### Show version and exit.
    ```bash
    $ ping -V
    ```
- ### Time to wait for a response, in seconds.
    ```bash
    $ ping -W timeout [URL]
    ```

---

## Exit Status
- **0** = Successful operation; the machine is alive.
- **non-zero** = An error has occurred. Either a malformed argument has been specified, or the machine was not alive.
---

## Author
- Mike Muuss.

---
