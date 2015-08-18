Viper Infra Red Capture, Send and Decode module

This module contains class definitions and methods for capture, decode and send IR packets.
* The IRPacket class allow the definition of IRPacket objects.
* The IRReceiver class handle the capture of IR packet controlling the signal gathered from an IR receiver and demodulator connected to a board pin empowered with ICU feature
* The decode method allow extraction from raw acquired data of packet detailed information and analysis of the message protocol. The method returns an IRPacketobject.

Authors: Daniele MAzzei and Giacomo Baldi
Copyright Viper Team 2015
License: GPL 3