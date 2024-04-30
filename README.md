# InformationGathering
Information Gathering Techiques

# To perform information gathering techniques

# AIM:

To perform information gathering techniques using kali linux 

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:
Open terminal/browser and try execute necessary commands/use url to perform information gathering

## PEN TEST TOOLS CATEGORIES:
Following Categories of pen test tools are identified for information gathering:

Footprinting is a part of the reconnaissance process which is used for gathering possible information about a target computer system or network.

http://www.whois.com/whois website to get detailed information about a domain name information including its owner, its registrar, date of registration, expiry, name server, owner's contact information, etc.

## OUTPUT:

![image](https://github.com/Catty12384/InformationGathering/assets/120629225/7aee5040-bc48-403f-9f7f-bfe2ccc00a41)

### Finding IP address:

Ping command is available on Windows as well as on Linux OS. 
Following is the example to find out the IP address of saveetha.ac.in.

```
  ping saveetha.ac.in
```
## OUTPUT:

![image](https://github.com/Catty12384/InformationGathering/assets/120629225/1373afdb-a24d-4e14-9200-72eaa951e527)

### Finding Hosting Company:

Get further detail by using ip2location.com website.  

## OUTPUT:

![image](https://github.com/Catty12384/InformationGathering/assets/120629225/f6a85b2e-50b3-48bb-98fc-60f7a9fc8160)

### History of Website:

## OUTPUT:

![image](https://github.com/Catty12384/InformationGathering/assets/120629225/42c436a0-a361-48c1-89e3-1ab6555be471)

## WEB SERVER FINGERPRINT:

### NETCAT:

```
  nc 172.17.52.118 80
```
## OUTPUT:

![image](https://github.com/Catty12384/InformationGathering/assets/120629225/6ebc3133-c261-4406-a79f-cf07993fb2a8)

### namap:

```
  nmap -p 21 -sV --script=banner ftp.vim.org
```
## OUTPUT:

![image](https://github.com/Catty12384/InformationGathering/assets/120629225/f2d2e831-04b9-4475-97f3-90298ce50145)

### Whatweb:

```
  whatweb infosys.com
```
```
  whatweb zoho.com
```
```
  whatweb -v -a 3 172.17.52.201
```
## OUTPUT:

![image](https://github.com/Catty12384/InformationGathering/assets/120629225/08d5be2f-8677-4c1f-a0bc-ca8511b076ed)

### httprint:InformationGathering:

```
httprint -h 172.17.52.201 -s /usr/share/httprint/signatures.txt -P0 |more
```
## OUTPUT:

![image](https://github.com/Catty12384/InformationGathering/assets/120629225/0d60ab44-4dd7-4b3d-b02e-209d35c079e3)

## Tracing the Location:

### TCP Traceroute:

```
sudo traceroute -T www.saveetha.ac.in
```
## OUTPUT:

![image](https://github.com/Catty12384/InformationGathering/assets/120629225/f013ac9f-bdfc-4efc-8b5e-d49468eae594)

### UDP Traceroute:

```
sudo traceroute -U www.saveetha.ac.in
```
## OUTPUT:

![image](https://github.com/Catty12384/InformationGathering/assets/120629225/bd9165c6-d85a-4790-bef7-bd78b9c92e0c)

### ICMP Traceroute:

```
sudo traceroute  www.saveetha.ac.in
```

## OUTPUT:

![image](https://github.com/Catty12384/InformationGathering/assets/120629225/d9587732-bfd9-441e-a6f1-3901a6f5b0c7)

## RESULT:
The information gathering techniques tools/procedure were  identified successfully
