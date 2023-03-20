---
title: How to Connect to CU-Resident Wi-Fi
date: 2023-03-20 07:00:00 -0800
categories: [College Life Hacks, First Day]
tags: [cornerstone, resident, wifi]                   #tags should always be lowercase
---

Getting connected to Wi-Fi at CU may seem straightforward, but the process can be intricate, similar to connecting to a printer here... This guide will walk through the steps to connect your device to the CU-Resident Wi-Fi network and enable extra security using the free [quad9.net](https://quad9.net/) DNS service. It's recommended to connect to a Wi-Fi network as "CU-Guest" is heavily bandwidth limited, meaning on average on CU-Guest you would normally get 10mbps while on "CU-Resident" you can achieve speeds on average of 100mbps. Though, if you add a custom DNS through [quad9.net](https://quad9.net/) you can achieve speeds well over 100mpbs, while increasing privacy and security of your devices.

`CU-Resident only allows on campus residents to log in to register their devices.`

## Registering a Device (Required)
Although registering a device may seem complicated, this guide simplifies the process and makes it straightforward. `The only requirement is that you have a device already connected to the network, which can be either CU-Resident or Cornerstone.`

1. **Visit** - [https://clearpass.cornerstone.edu](https://clearpass.cornerstone.edu)

    `Note - If you are not connected to either CU-Resident or Cornerstone, the site will return an error "We can’t connect to the server at clearpass.cornerstone.edu."`
2. **Login** - to clear pass by using the following format `Username` is `"first initial, followed by a 0, then ID number"` example "a0123456". `Password` is your `Microsoft account password`.
3. **Click** - `"Guest Management"` located under `"ClearPass Guest"`
4. **Click** - `Add Device` located on the right near `"List Devices"` and the `"Logout"` button.
5. **Add** - a `"Device Name"`, it's recommended to not personally identify the real device. I would put device 1, device 2, device 3, etc. This increases privacy a little bit. 
6. **Add** - the `"Mac Address"` of the device, this can be found in various places on a variety of devices. I recommend to lookup on YouTube, "How to find mac address for (blank product)" 

    `Apple Products - Settings → General → About → "Wi-Fi address"`

    `Windows - Settings → Network & Internet → Ethernet or Wi-Fi → Select the connection → Properties → "Physical address (MAC)"`

    `Linux - Open Terminal/Console → Type and enter "ip link" → Mac address → Mac address will be listed after "link/ether"`
7. **Press** - `"Create Device"` once you have entered your device's Mac address, be sure to leave `"Enable AirGroup"` blank. 

    `Note - CU only allows 3 devices to be connected to one account, meaning you can only have 3 devices registered per account.`

## Connecting a Device (Required)
Once you have completed all the steps to register your devices, you can now simply connect to `"CU-Resident"` as you would with any other Wi-Fi network. I do highly recommend setting up quad9 as a custom DNS with the instructions below, but it's only optional.

## Enabling Extra Security (Recommended)
This is an optional step but is highly recommend as not only does it give your devices more security and privacy, but it could increase Wi-Fi speed quite significantly. Based on my tests alone, it allowed a number of my friends to download/update various PlayStation games well over 50 GB's in less than 10 minutes. Since quad9 is relatively a big non-profit organization, they have crafted a handful of guides made per devices and operating systems.

[https://quad9.net/support/set-up-guides](https://quad9.net/support/set-up-guides)

### Enabling Extra Security via VPN (Recommended)
While I highly recommended adding quad9 to your devices simply due to it being a trustworthy non-profit organization, and it's free. If you are looking for a secure and fast VPN, I recommend either [ProtonVPN](https://pr.tn/ref/AWDACPD704Z0), [Mullvad](https://mullvad.net/) or [IVPN](https://www.ivpn.net/). Although I have a custom code for `"Proton Mail Plus"` as they are allowing me to give away one month of Proton Mail Plus completely free. Which gives you access to many perks including a secure and private VPN. 

[Free One Month of Proton Mail Plus Click Here](https://pr.tn/ref/AWDACPD704Z0)

`Note - If you are connected to CU Wi-Fi, they block any website name with the words "VPN" due to VPNs having the capability to unblock all network restrictions on their censored networks.`