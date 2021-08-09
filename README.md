# Port Scan Detector (CS-Network-Security) [![GitHub stars](https://img.shields.io/github/stars/badges/shields.svg?style=social&label=Stars)](https://github.com/buraktokman/Port-Scan-Detector---CS-Network-Security/)

[![Travis](https://img.shields.io/travis/rust-lang/rust.svg)](https://github.com/buraktokman/Port-Scan-Detector---CS-Network-Security)
[![Repo](https://img.shields.io/badge/source-GitHub-303030.svg?maxAge=3600&style=flat-square)](https://github.com/buraktokman/Port-Scan-Detector---CS-Network-Security)
[![Requires.io](https://img.shields.io/requires/github/celery/celery.svg)](https://requires.io/github/buraktokman/Port-Scan-Detector---CS-Network-Security/requirements/?branch=master)
[![Scrutinizer](https://img.shields.io/scrutinizer/g/filp/whoops.svg)](https://github.com/buraktokman/Port-Scan-Detector---CS-Network-Security)
[![DUB](https://img.shields.io/dub/l/vibe-d.svg)](https://choosealicense.com/licenses/mit/)
[![Donate with Bitcoin](https://img.shields.io/badge/Donate-BTC-orange.svg)](https://blockchain.info/address/17dXgYr48j31myKiAhnM5cQx78XBNyeBWM)
[![Donate with Ethereum](https://img.shields.io/badge/Donate-ETH-blue.svg)](https://etherscan.io/address/91dd20538de3b48493dfda212217036257ae5150)

### Instructions
------

A port scan attack occurs when an attacker sends packets to a machine, varying the destination port. The attacker can use this to find out what services running, open ports, and to get a pretty good idea of the operating system to have.

Port scan detectors are tools that inform the administrator or the user of the machine. Port scan detectors have signatures that are very good at detecting port scans. Obviously, it is always possible for an attacker to make his/her attack either very unlikely to be noticed or very unlikely to be traced to its real origin, while still being able to obtain the port number information. To obsecure the attack, the attacker could do it very slowly and hide.

This project aims to catch the port scan happening on the system by an attacker. scanlogd is a minimal, reliable port scan detection tool that is used in this project and made the following modifications for our objectives as descripted below.



### LICENSE
------

MIT License
