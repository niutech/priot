The Private Internet of Things Manifesto
=====

We believe the Internet of Things is a very promising idea, but we notice it brings very serious privacy concerns. A lot of sensitive data from various sensors around us is going to be gathered and processed in centralized data stores run by big corporations and governments. We think it does not need to be so. We are proposing the Private Internet of Things (PrIoT) paradigm, where private data is stored in decentralized private clouds, fully controlled by users, interoperable with other private clouds and in federation with them, using open standards.

![Centralized vs decentralized](http://upload.wikimedia.org/wikipedia/commons/7/78/Decentralization.jpg)

Similar to [federated social networks](https://www.eff.org/deeplinks/2011/03/introduction-distributed-social-network), the PrIoT model gives control over sensitive data back to users. They keep their data and decide which part of them will be exchanged using one of the emerging open standard protocols:
- [Advanced Message Queuing Protocol (AMQP)](http://amqp.org/) by OASIS,
- [Constrained Application Protocol (CoAP)](http://coap.technology/) by IETF,
- [Message Queue Telemetry Transport (MQTT)](http://mqtt.org/) by OASIS,
- [eXtensible Messaging and Presence Protocol (XMPP)](http://xmpp.org/) by XSF,
- [ZeroMQ Message Transport Protocol (ZMTP)](http://zeromq.org/) by DSO.

This could be achieved by deploying a local PrIoT cloud based on open source projects like:
 - [AllJoyn](http://www.alljoyn.org/) by AllSeen Alliance,
 - [Contiki](http://www.contiki-os.org/) (based on CoAP) by Adam Dunkels et al,
 - [Edgenet](http://theedg.es/) by Pieter Hintjens,
 - [Kaa](http://www.kaaproject.org/overview/) (based on MQTT/HTTP) by CyberVision,
 - [Open IoT Stack for Java](http://iot.eclipse.org/java/) (based on MQTT) by Eclipse Foundation,
 - [RabbitMQ](https://www.rabbitmq.com/) (based on AMQP) by Pivotal,
 - [Spark](http://spark.github.io/) (based on CoAP) by Spark Labs.

If you agree with us, please star and share this project. Contributions are welcome.

&copy; 2014 Jerzy Głowacki et al. Licensed under CC BY-SA 4.0.

[Image](http://commons.wikimedia.org/wiki/File:Decentralization.jpg#mediaviewer/File:Decentralization.jpg) by Adam Aladdin, licensed by CC BY-SA 3.0. 
