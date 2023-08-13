# RF-CTF-Equipment

## INFO

This page covers some of the equipment used to host the CTF.  All equipment is subject to change, likely without notice, possibly without updating this page.

If you see something on the table that's not listed here, ask us about it, or don't.

## WiFi AP Box

## WiFi Client Box

## SDR Box
This box contains an intel nuc using 3 BladeRF Software Defined Radios (SDR) and an ubertooth one. It is believed that this box is used to transmit various flags within the room. Researching the transmit bandwidth and frequency range that these devices are capable of may assist in narrowing down which parts of the spectrum to look in. Also keep in mind that there are certain bands that people are legally allowed to transmit within (those are good places to check). 

![](https://raw.githubusercontent.com/rfhs/rfhs-wiki/master/files/images/rfctfequipment/sdrbox.JPG)

## King of the Hill
![](https://github.com/rfhs/rfhs-wiki/blob/master/files/images/PXL_20230430_173702141.jpg)
The Wifi King of the hill Challenge requires users to connect to the RFHS_RFCTF_KingOfTheHill Wifi network and submit their team name to the webpage hoted on the router. 
When a team is able to successfully connect to the network and submit their team name, the scoring system will record their submission, and then stop broadcasting the network for 60 seconds.
After 60 seconds have elapsed the AP resumes broadcsting the network and teams can attempt to connect to the access point and submit their team name to the web page again.
For the duration of the CTF the router will continue to run and and cycles its brodcastings for 60 seconds after a team has connected and submitted their name, always coming back up on a random channel and with a random MAC addess.

Scoring works by taking the total number of team name submissions to the page hosted on the ap and dividing the points the challenge is worth up proportionally up amongst the teams that submitted their team name successfully.


**New players potentially beware:** Some long time veteran teams have dedicated hard ware designed to automatically connect and submit their team names to the web page, so it may take you some time to see this AP if automated hardware is being run. Additionaly players should look out for teams running rogue APs that are pretending to be be the one hosted by the RFHS. You can submit your team name to rogue AP, but the RFHS wont award you any proportional points for you effort. Pre-con testing and preperation are keys to being successful with this challenge. Consider building a simulation of the challenge itself. The following simulators could be useful:

- [https://github.com/blunderbuss-wctf/koth_simulator](https://github.com/blunderbuss-wctf/koth_simulator)
 
 
## 6LoWPAN
![](https://raw.githubusercontent.com/rfhs/rfhs-wiki/master/files/images/rfctfequipment/6lowpan.JPG)

## LRS Pagers
Long Range Systems manufacture several versions of pagers and paging devices. At the table you may notice something similar to the one in this image:

Each pager is similar to what you would find at a restaurant. Check the scoreboard for what challenges are live, but if you see this you might need to receive and or transmit packets to and from these devices. LRS usually involves a restaurant id, and a pager id. These numbers are useful and you should figure out how to find them and use them

![](https://raw.githubusercontent.com/rfhs/rfhs-wiki/master/files/images/rfctfequipment/lrspager.JPG)


## ICS

## RFID (Building-in-a-)Box
Pictured below is the RFID Building in a Box. Within you will notice several different types of RFID readers and keypads, all of which are commonly found in buildings. These readers support different types of rfid cards. There will be an accompanying selection of cards available at the table, often on a big wire loop. Challenges are usually for each type of badge or specific attacks on certain card types. Inspect the rfid cards, it may also be helpful to pay attention to the markings on the cards. 

![](https://raw.githubusercontent.com/rfhs/rfhs-wiki/master/files/images/rfctfequipment/rfidbib.JPG)

## Magic Mixie
This most magical of challenges will put your wand skills to the test. Have you gone to the wand academy? If not you should.

![](https://raw.githubusercontent.com/rfhs/rfhs-wiki/master/files/images/rfctfequipment/rfidbib.JPG)
