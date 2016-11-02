rawstock
========

A promiscuous raw socket framework for Python.

What does it do?
================

Re-invents the wheel (not for the better cowboy, this is the wild side of the internet).<br>
It creates a raw socket without any automated header builds.<br>
<br>
The framework can be used to create basic Ethernet, IP and TCP/UDP headers.<br>
It also features the option to set the socket in promiscuous mode.<br>

TODO's
======

This is a never ending section, there's literally countless of hours left on this project.<br>
Odds are I'm never gona' finish it, but it's a fun little side project.<br>
<br>
Things I'd like to finish:

 * More detailed parsing of the IP headers
 * More detailed parameters for IP packaging
 * Error handling in terms of actually parsing the protocol flags and unpacking the last slice of a network frame (assumed UDP today)
 * Encryption (MAC-sec and optional payload encryption in TCP/UDP)
 * A neat way to filter out sent packages which today will trigger a recv() because of promisc mode.
