# Various-Communications

RTMP /RTSP/ HLS/ MPEG - DASH/ SRT/ Websockets/ IRC/ XMPP/ MQTT/ AMQP/ RCS/ STOMP

# Difference Between Signaling Protocols and Transport Protocols?
**Signaling Protocols**-
A Signaling Protocol is used to identify the state of connection between telephones or VOIP terminals. Signaling protocols include: ALOHA, EDSS1, Dual-tone multi-frequency signaling, H.248, H.323, H.225.0, Jingle, Media Gateway Control Protocol, Megaco, R1, NBAP (Node B Application Part), R2 signalling, **Session Initiation Protocol (SIP)**, Signaling System No.5, Signaling System No.6, Signaling System No.7 (SS7), SCCP (Skinny Call Control Protocol), Q.931 and QSIG.

**Transport Protocols**
TCP/ UDP


**Network Protocols**
HTML / Websockets
XHR , SSE





# VOIP
VoIP has two Flavors of Protocol
1. Signalling( SCCP, H.323, SIP)
2. Transport (RTP, RTCP)

**VoIP protocols include**:
1. **Session Initiation Protocol(SIP)**- connection management protocol developed by the IETF
2. **H.323**- one of the first VoIP call signaling and control protocols that found widespread implementation.Since the development of newer, less complex protocols such as MGCP and SIP, H.323 deployments are increasingly limited to carrying existing long-haul network traffic.
3. **Media Gateway Control Protocol (MGCP)**- connection management for media gateways
4. **H.248**- control protocol for media gateways across a converged internetwork consisting of the traditional PSTN and modern packet networks
5. **Real-time Transport Protocol (RTP)**- transport protocol for real-time audio and video data
6. **Real-time Transport Control Protocol (RTCP)**- sister protocol for RTP providing stream statistics and status information
7. **Secure Real-time Transport Protocol (SRTP)**- encrypted version of RTP
8. **Session Description Protocol (SDP)**- a syntax for session initiation and announcement for multi-media communications and WebSocket transports.
9. **Inter-Asterisk eXchange (IAX)-** protocol used between Asterisk PBX instances
10. **Extensible Messaging and Presence Protocol (XMPP)**- instant messaging, presence information, and contact list maintenance
11. **Jingle**- for peer-to-peer session control in XMPP
12. **Skype protocol**- proprietary Internet telephony protocol suite based on peer-to-peer architecture

**Big Thinks to think About**
1. Registration and populating the phone interface (Number, Assignments, etc)
2. Making Calls(address signalling, directory services, etc)
3. Negotiating the details for the RTP Stream(port, codec, etc)
4. Terminating the Call

VoIP Support: POE, TFTP, DHCP, DNS, NTP

# WebRTC
Inorder to know about WbeRTC, we need to have an idea about Websockets.
Though Info is transfered between browsers, inorder to intiate connection the browser should approach Server.

