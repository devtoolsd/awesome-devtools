# Awesome Proxy

[![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)

A collaborative list of awesome proxy servers and resources. Feel free to contribute!

<br><br>
<h4 align="center">
Sponsored By: <a href="https://altern.ai">Altern, List of AI tools and resources</a>
</h4>

<p align="center">
  <a href="https://altern.ai">
    <img src="altern.gif" width="400" alt="Altern Artificial Intelligence Directory of Products, tools and resources ">
  </a>
</p>
<br>


## Index

- [What is](#what-is)
- [Types](#types)
- [Protocols](#protocols)
- [Proxy Server](#proxy-server-forward-proxy)
- [Reverse Proxy](#reverse-proxy)
- [SOCKS Proxy](#socks-proxy)
- [HTTP/HTTPS Proxy](#httphttps-proxy-http-tunnel)
- [FTP Proxy](#ftp-proxy)
- [DNS Proxy](#dns-proxy)

## What is

> A proxy server, also known as a "proxy" or "application-level gateway", is a computer that acts as a gateway between a local network (for example, all the computers at one company or in one building) and a larger-scale network such as the internet. [^1](https://kb.iu.edu/d/ahoo)

## Types

- [Proxy server (Forward Proxy) ](https://en.wikipedia.org/wiki/Proxy_server)
- [Reverse Proxy](https://en.wikipedia.org/wiki/Reverse_proxy)

![Forward Proxy vs Reverse Proxy](https://i.stack.imgur.com/0qpxZ.png)

## Protocols

- SOCKS Proxy
- HTTP/HTTPS Proxy
- FTP Proxy
- DNS Proxy
- Anonymous Proxy

## Proxy server (Forward Proxy)

> A proxy server that passes unmodified requests and responses is usually called a gateway or sometimes a tunneling proxy.

> A forward proxy is an Internet-facing proxy used to retrieve data from a wide range of sources.

- [Proxy Server - wikipedia](https://en.wikipedia.org/wiki/Proxy_server)
- [What is Proxy - quora](https://www.quora.com/What-is-proxy)

### Popular Proxy servers

- [squid](http://www.squid-cache.org/)
- [g3proxy](https://github.com/bytedance/g3) - HTTP/Socks/SNI/Transparent Proxy, Proxy Chaining, Protocol Inspection, MITM Interception, ICAP Adaptation.

## Reverse Proxy

> A reverse proxy is usually an internal-facing proxy used as a front-end to control and protect access to a server on a private network. A reverse proxy commonly also performs tasks such as load-balancing, authentication, decryption or caching.

- [What Is a Reverse Proxy Server?](https://www.nginx.com/resources/glossary/reverse-proxy-server/)

### Popular Reverse Proxies

- [NGINX Open Source](https://nginx.org/) / [NGINX Plus](https://nginx.com/)
- [Envoy Proxy](https://www.envoyproxy.io/)
- [Apache](http://wiki.apache.org/cocoon/ApacheModProxy)
- [HAProxy](http://haproxy.1wt.eu/)
- [Caddy](https://caddyserver.com/docs/proxy)
- [Træfɪk](https://traefik.io/)
- [Pound](http://www.apsis.ch/pound)
- [relayd](https://bsd.plumbing/)
- [ngrok](https://github.com/inconshreveable/ngrok)
- [Pipy](https://flomesh.io/pipy/)
- [YARP](https://microsoft.github.io/reverse-proxy/)
- [Sōzu](https://www.sozu.io)

## SOCKS Proxy

> SOCKS is an Internet protocol that exchanges network packets between a client and server through a proxy server. SOCKS5 additionally provides authentication so only authorized users may access a server. Practically, a SOCKS server proxies TCP connections to an arbitrary IP address, and provides a means for UDP packets to be forwarded. [wikipedia](https://en.wikipedia.org/wiki/SOCKS)

### SOCKS protocol

- [SOCKS Protocol version 5 - rfc 1928](https://www.ietf.org/rfc/rfc1928.txt)
- [SOCKS Protocol version 4](https://www.openssh.com/txt/socks4.protocol)

### Popular Implementations of SOCKS server

- [Shadowsocks](https://shadowsocks.org/en/index.html) - A secure socks5 proxy, designed to protect your Internet traffic.
- [Dante](https://www.inet.no/dante/) - A free SOCKS server.
- [microsocks](https://github.com/rofl0r/microsocks) - Tiny, portable SOCKS5 server with very moderate resource usage.

## HTTP/HTTPS Proxy (HTTP tunnel)

> HTTP tunneling is used to create a network link between two computers in conditions of restricted network connectivity including firewalls, NATs and ACLs, among other restrictions. The tunnel is created by an intermediary called a proxy server which is usually located in a DMZ. [wikipedia](https://en.wikipedia.org/wiki/HTTP_tunnel)

### HTTP Proxy protocol

- [RFC 7230](https://tools.ietf.org/html/rfc7230) - Hypertext Transfer Protocol (HTTP/1.1): Message Syntax and Routing

### Popular Implementations of HTTP tunnel

- [XX-Net](https://github.com/XX-net/XX-Net) - a web proxy tool
- [Tinyproxy](https://tinyproxy.github.io/) - lightweight http(s) proxy daemon
- [mitmproxy](https://mitmproxy.org/) - mitmproxy is a free and open source interactive HTTPS proxy.
- [OpenProxy](https://github.com/trimstray/OpenProxy)
- [Privoxy](http://www.privoxy.org/)

## FTP Proxy

### Popular Implementations of FTP Proxy

- [ftp.proxy](http://www.ftpproxy.org/)

## DNS Proxy

[What are DNS and the DNS Proxy?](https://www.watchguard.com/training/fireware/80/dnsprox2.htm)

### Popular DNS Proxy servers

- [dnsmasq](http://www.thekelleys.org.uk/dnsmasq/doc.html)
