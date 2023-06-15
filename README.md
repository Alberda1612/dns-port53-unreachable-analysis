# DNS Server Unavailability: Investigating UDP Port 53 Unreachable Error
![](network.jpg)

## Introduction
The DNS Port 53 Unreachable Analysis project is a comprehensive investigation into a specific network issue encountered while accessing a website. The repository provides detailed logs and network captures. This is used to analyze the DNS and ICMP traffic, aiming to identify the underlying problem causing the unavailability of the DNS server.

## Objectives
1. Identify the affected network protocol: Determine which network protocol (e.g., UDP, TCP) is causing the "UDP port 53 unreachable" error, leading to the DNS server unavailability.
2. Analyze DNS and ICMP traffic: Utilize network analyzer tools (e.g., tcpdump) to capture and analyze the DNS and ICMP packets, examining the source, destination IP addresses, timestamps, and error messages.
3. Determine the root cause: Investigate the logs and network captures to identify the underlying issue causing the unavailability of the DNS server, such as misconfigurations, network blocks, or potential malicious activities.

## Skills / Concepts Demonstrated
1. Network Traffic Analysis.
2. Log Analysis.
3. Network Security Awareness
4. Problem Solving.

## Background Information 
You are a cybersecurity analyst working at a company that specializes in providing IT consultant services. Several customers contacted your company to report that they were not able to access the company website www.yummyrecipesforme.com, and saw the error “destination port unreachable” after waiting for the page to load. 

You are tasked with analyzing the situation and determining which network protocol was affected during this incident. To start, you visit the website and you also receive the error “destination port unreachable.” Next, you load your network analyzer tool, tcpdump, and load the webpage again. This time, you receive a lot of packets in your network analyzer. The analyzer shows that when you send UDP packets and receive an ICMP response returned to your host, the results contain an error message: “udp port 53 unreachable.” 

**__Task:__** : Your task is to inspect and review the log file generated from using the network protocol analyzer, tcpdump to investigate the error, and determine the possible causes of the incidents. 

## Review of Log File
![](log.JPG)

