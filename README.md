A few exercises looking through old classwork. Still partial/incomplete, will add as time permits.

***Firewalls (Bash, 2015)***

Some intro firewall exercises (iptables)

***Hash Collision (Python, 2018)***

Simple MD5 Collision

Two files, 1 and 2, with a different inserted blob generated with a collision tool. Running MD5sum will yield the same hash but SHAsum will yield 2 different hashes. Executing the python files will yield 2 different messages.

This is why MD5 should not be used as a hashing algorithm to ensure integrity (though it still is frequently in Digital Forensics)

***Length Extension (Python, 2018)***

Merkle-Damgard Construct hash functions are vulnerable to a length extension attack. The example file shows interactive python output where, given an md5 hash of a string, an attacker can compute a valid md5 hash of
 
"message1+padding+message2"

**Wireless Penetration (Bash, 2015/2018)**

Some attacks I've replicated from a guest lecture

Beacon Flood
Sends junk beacon frames advertising fake access points. Run this script then check available wireless networks.

Wifi DeAuth
TBD 
