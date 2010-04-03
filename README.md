
Network Discovery
=================

Machines discovery/mapping (over Wifi) and port scan (over 3G/Wifi) utility for Android devices.

Features
--------

 *  Discover Machines on a LAN
 *  TCP Port Scanner (connect() scan)
 *  NIC vendor database
 *  Export results to your sdcard in XML
 *  Fast access to Wifi Settings
 *  Adaptive scanning rate (slow start, then adaptive to network latency)
 *  Open Source, available at http://github.com/rorist/android-network-discovery

Build
-----

 *  Native Code: Follow instructions in native/README
 *  APK: 
  * build.xml is provided for ant
  * simply type this command: ant debug

Todo
----

 * Network interface choice in preferences
 * Uses-intents in manifest
 * Save all scan in DB, open previous scan, export previous scan, etc
 * Discovery: restrict range or change cidr
 * Settings: prevent phone from sleeping, discovery method (root/non-root)
 * RateControl: better rate by host ?
 * NMAP build script (ARM and other arch (using AOSP?))
 * Refactor host info (inflater + dynamic layouts), and add new info such as Hops (using MTR?)
 * Support of other protocol: UDP, SCTP
 * Send custom packets (shell codes, exploits, ...)
 * Nat Traversal
 * Proxy (auto)support

GPLv2 License
-------

Copyright (C) 2009-2010 Aubort Jean-Baptiste (Rorist)

This program is free software; you can redistribute it and/or
modify it under the terms of the GNU General Public License
as published by the Free Software Foundation; either version 2
of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program; if not, write to the Free Software
Foundation, Inc., 51 Franklin Street, Fifth Floor, Boston, MA  02110-1301, USA.

Copy of the license can be found in gpl-2.0.txt
