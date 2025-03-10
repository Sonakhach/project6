 # OSINT Investigation: Unmasking a Digital Footprint (any images, not only human)

 **OSINT (Open-Source Intelligence)** is the process of collecting, analyzing, and using publicly available information from various sources to gather intelligence. It is widely used in cybersecurity, ethical hacking, law enforcement, journalism, and threat intelligence
 
**OSINT Sources Include:**

🔹 Social Media – Public profiles, posts, comments, and connections.

🔹 Websites & Domains – WHOIS data, DNS records, archived pages.

🔹 Search Engines – Google Dorking, advanced queries.

🔹 Public Databases – Breach databases, government records, business registries.

🔹 Metadata – EXIF data from images, document properties.

🔹 Dark Web & Paste Sites – Leaked credentials, hacking forums.

**Why is OSINT Important?**

✔ Helps in cybersecurity investigations & penetration testing.

✔ Assists in threat intelligence and risk assessments.

✔ Identifies fake accounts, scams, and fraud.

✔ Supports ethical hacking, journalism, and law enforcement.

1. The government led by Turkish President Recep Tayyip Erdogan was criticized earlier this month for the allocation to Somalia.
   
   Friday November 13, 2020 - 17:21:52  -> https://mogtimes.com/articles/38592/Madaxweyne-ERDOGAN-oo-lagu-dhaliilay-garab-istaag-uu-u-sameeyay-Soomaaliya
   Picture was taken near the presidential palace․
   
   **I used googl to gather information**
   
![ing](https://github.com/Sonakhach/project6/blob/main/image.png)

2. Millennium Downtown New York. The picture was taken from hotel  55 Church Street, New York City, NY 10007-> https://www.millenniumhotels.com/en/new-york/millennium-downtown-new-york/
   
![ing](https://github.com/Sonakhach/project6/blob/main/1xuvCveFEJVZT7GMjAk2qFQ.png)

3. **I used  https://pimeyes.com/ for information about man -> https://pimeyes.com/en/results/BGG_2503013zsz8ps3ueq1u9d941b392a?query=cf4300c00001ffff7d7c7cdafe640000&safesearch=true  and googl for status of Theodore Roosevelt in the American Museum of Natural History in New York (photo: amnh.org) and youtube bloger ho has youtube channel /NetworkChunk/**    
   
The museum  has a bronze sculpture of Roosevelt on display in its Theodore Roosevelt Memorial Hall. This bronze sculpture depicts Roosevelt as a real person sitting on a bench with room for visitors to sit beside him.-> https://www.gothamgazette.com/authors/130-opinion/11084-other-theodore-roosevelt-statue-american-museum-natural-history

![ing](https://github.com/Sonakhach/project6/blob/main/F6FkAd-XcAAbSwy.png)

![ing](https://github.com/Sonakhach/project6/blob/main/Screenshot%20from%202025-03-10%2011-36-14.png)

4. **used yandex reverse image**
   
   In the background of the Louvre museum in France
 The picture was done by camera, not smartphone.So he can be a traveler, blogger or someone like that.  
![ing](https://github.com/Sonakhach/project6/blob/main/GZRZ4vzWEAAveCz.png)

5. **Where is bridge?**

   Maria Pia Bridge

A railway bridge across the Douro River in Portugal. It connects the cities of Porto and Vila Nova de Gaia. It was built according to the design of Gustave Eiffel in 1877. It was named after the wife of King Luis I - Maria Pia of Savoy.

**I used yandex reverse image to gather information**

![ing](https://github.com/Sonakhach/project6/blob/main/imostik.png)

when I used exiftool ,I dont got metadata, this mean picture was screenshot

![ing](https://github.com/Sonakhach/project6/blob/main/Screenshot_2025-03-02_02_46_47.png)

6. **What camera was used to take this picture**


    **Checking Camera Info from a Picture (EXIF Data Analysis)**

   ```
   sudo apt install exiftool
   ```
   
   Download and analyze the image . Look for fields like **Make, Model**, and Lens Info to determine the camera used.
   
   ```
   wget https://raw.githubusercontent.com/ianare/exif-samples/refs/heads/master/jpg/tests/33-type_error.jpg
   exiftool 33-type_error.jpg
  
  
  ![ing](https://github.com/Sonakhach/project6/blob/main/Screenshot%20from%202025-03-02%2011-19-38.png)
   ![ing](https://github.com/Sonakhach/project6/blob/main/Screenshot_2025-03-02_02_11_46.png)
   ![ing](https://github.com/Sonakhach/project6/blob/main/Screenshot_2025-03-02_02_15_53.png)
   ![ing](https://github.com/Sonakhach/project6/blob/main/Screenshot_2025-03-02_02_16_12.png)
   ![ing](https://github.com/Sonakhach/project6/blob/main/Screenshot_2025-03-02_02_17_01.png)
  
  ![ing](https://github.com/Sonakhach/project6/blob/main/Screenshot_2025-03-02_02_14_02.png)

  ![ing](https://github.com/Sonakhach/project6/blob/main/Screenshot%20from%202025-03-02%2012-41-49.png)

7. **photo is real or AI-generated**
   
   Image metadata alone cannot confirm whether a person in a photo is real or AI-generated. However, you can use a combination of forensic analysis, reverse searches, and AI detection tools to investigate.
   

   
![ing](https://github.com/Sonakhach/project6/blob/main/men.png)

### Osint - https://tryhackme.com/room/threatinteltools

![ing](https://github.com/Sonakhach/project6/blob/main/Screenshot%20from%202025-03-06%2021-15-32.png)

### Google Dorking - https://tryhackme.com/room/googledorking

![ing](https://github.com/Sonakhach/project6/blob/main/Screenshot%20from%202025-03-10%2000-42-10.png)

![ing](https://github.com/Sonakhach/project6/blob/main/Screenshot%20from%202025-03-10%2000-40-35.png)

![ing](https://github.com/Sonakhach/project6/blob/main/Screenshot%20from%202025-03-10%2000-40-49.png)

![ing](https://github.com/Sonakhach/project6/blob/main/Screenshot%20from%202025-03-10%2000-41-03.png)

![ing](https://github.com/Sonakhach/project6/blob/main/Screenshot%20from%202025-03-10%2000-41-42.png)

### Osint exercise - https://gralhix.com/list-of-osint-exercises/osint-exercise-005/

Task briefing:

The image below is a screenshot from a zoo live cam. It was taken on January 15, 2023 at around 2pm local time.
Please answer the questions below:

a) In which zoo are these polar bears located?

at first search "polar bear live cam" with googl after that go several similar url-> https://www.facebook.com/FirstAlertSanDiego/videos/polar-bear-live-cam-from-san-diego-zoo/1347230615786668. it place is same **San Diego Zoo** 
![ing](https://github.com/Sonakhach/project6/blob/main/Screenshot%20from%202025-03-10%2013-18-24.png)
![ing](https://github.com/Sonakhach/project6/blob/main/Screenshot%20from%202025-03-10%2013-24-09.png)

b) What was the temperature at the time of the screenshot?
We have date and time, and in browser make search "historical temperature in san diego" , go https://www.wunderground.com/history/daily/us/ca/san-diego/date/2021-2-23 and get temperature ->63 F

![ing](https://github.com/Sonakhach/project6/blob/main/Screenshot%20from%202025-03-10%2013-54-54.png)

c) What were the exact coordinates of where the bears were lying down?

Go googlmap and search with  addrecc

![ing](https://github.com/Sonakhach/project6/blob/main/Screenshot%20from%202025-03-10%2014-03-39.png)
