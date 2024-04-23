# pi.hole Basic Domine Blacklist
![alt text](https://badgen.net/badge/platform/pi.hole/blue?) ![alt text](https://badgen.net/badge/content/blacklist/red?)

Basic Blacklist for pi.hole

## Description
This domine blacklist for Pi-hole has been created based on the project [Toolz](https://github.com/d3ward/toolz).

## List Content
The list contains the blocks indicated in the table below.

|    Block        |   Service       |
| --------------- | --------------- |
|    ADS          |   Amazon        |
|                 |   Google        |
|                 | Doubleclick.net |
|                 |   Adolony       |
|  Analytics      |   Google        |
|                 |   Hotjar        |
|                 |   MouseFlow     |
|                 |   FreshWorks    |
|                 | Stats WP Plugin |
|                 |   Luckyorange   |
| Error Trackers  |   Bugsnag       |
|                 |   Sentry        |
| Social Trackers |   Facebook      |
|                 |   Twitter       |
|                 |   LinkedIn      |
|                 |   Pinterest     |
|                 |   Reddit        |
|                 |   YouTube       |
|                 |   TikTok        |
|    MIX          |   Yahoon        |
|                 |   Yandex        |
|                 |   Unity         |
|    OEMs         |   Realme        |
|                 |   Xiaomi        |
|                 |   OnePlus       |
|                 |   Huawei        |
|                 |   Apple         |
|                 |   Samsung       |

## Upload to pihole database

To configure the domain list, please follow these steps:

Download the script:
``` 
cd /opt
sudo wget https://raw.githubusercontent.com/paolo-hub/pi.hole_basic_domine_blacklist/main/pihole_domain_black.py
``` 

Execute the script:
``` 
python3 pihole_domain_black.py
``` 

This will load the domains with the description "Basic Domain Blocked" and place them in the Default group.






****
