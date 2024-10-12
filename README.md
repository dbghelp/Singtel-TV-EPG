# Singtel-TV-EPG

## Overview

This repository contains the XML EPG (Electronic Program Guide) for Singtel TV channels. The EPG provides a schedule of the current and upcoming TV programs, enabling users to easily see what's on and plan their viewing.

## Features

- XML formatted EPG for Singtel TV channels
- Up-to-date information on channel programming
- Easy integration with various applications and services

## Usage

To use the EPG data, you can fetch the XML file from this repository and parse it in your application to display the program schedule.

In your M3U8 playlist, 

1. Change your url-tvg to "https://raw.githubusercontent.com/dbghelp/Singtel-TV-EPG/refs/heads/main/singtel.xml":

```#EXTM3U url-tvg="https://raw.githubusercontent.com/dbghelp/Singtel-TV-EPG/refs/heads/main/singtel.xml" refresh="3600"```

2. Change your tvg-id to the following for the respective channels:
  
|   tvg-id   |      Channel Name       |
|------------|-------------------------|
| 5002       | Ch 5 (HD)               |
| 5003       | Ch 8 (HD)               |
| 5004       | Suria (HD)              |
| 5005       | Vasantham (HD)          |
| 5006       | CNA (HD)                |
| 5007       | Ch U (HD)               |
| 5501       | e-Le (HD)               |
| 5521       | ETTV Asia (HD)          |
| 5615       | SEA Today               |
| 6119       | Fight Sports (HD)       |
| 5119       | (HD) Outdoor Channel    |
| 5260       | TechStorm (HD)          |
| 4102       | Hub Premier 1           |
| 4103       | Hub Premier 2           |
| 4104       | Hub Premier 3           |
| 4105       | Hub Premier 4           |
| 5111       | mio Sports (HD)         |
| 5112       | mio Sports 2 (HD)       |
| 5113       | mio Sports 3 (HD)       |
| 6114       | SPOTV (HD)              |
| 6115       | SPOTV 2 (HD)            |
| 6116       | EUROSPORT (HD)          |
| 5118       | Premier Sports          |
| 5123       | mio Cricket (HD)        |
| 5124       | mio Cricket Plus (HD)   |
| 6126       | beIN SPORTS (HD)        |
| 6127       | beIN SPORTS 2 (HD)      |
| 6110       | beIN SPORTS 3 (HD)      |
| 5127       | beIN SPORTS 4 (HD)      |
| 5128       | beIN SPORTS 5 (HD)      |
| 5131       | MOLA Sport (HD)         |
| 5151       | Sky News HD             |
| 5155       | CGTN (HD)               |
| 5157       | NHK World - Japan       |
| 5041       | France 24 (English)     |
| 5161       | DW (English)            |
| 5165       | FOX News Channel HD     |
| 6166       | BBC News (HD)           |
| 5167       | CNN International       |
| 5171       | Bloomberg TV (HD)       |
| 5173       | CNBC Asia (HD)          |
| 5202       | Discovery Ch (HD)       |
| 6203       | BBC Earth (HD)          |
| 5204       | Discovery Asia (HD)     |
| 5206       | C+I (HD)                |
| 5208       | Animal Planet (HD)      |
| 5209       | HISTORY (HD)            |
| 5211       | CGTN-Documentary        |
| 5226       | Cartoon Network (HD)    |
| 5228       | Cartoonito (HD)         |
| 5233       | DreamWorks (HD)         |
| 6236       | CBeebies (HD)           |
| 5238       | Nick Jr (HD)            |
| 5240       | Nickelodeon Asia HD     |
| 5250       | HGTV (HD)               |
| 5251       | ABC Australia           |
| 5252       | Food Network (HD)       |
| 5254       | TLC (HD)                |
| 6255       | BBC Lifestyle (HD)      |
| 5256       | AFN (HD)                |
| 5257       | TRACE Sport Stars HD    |
| 6301       | HITS MOVIES (HD)        |
| 5302       | Lifetime (HD)           |
| 5303       | HITS NOW (HD)           |
| 5304       | AXN (HD)                |
| 5310       | ROCK Action (HD)        |
| 5318       | ROCK ENT (HD)           |
| 5326       | HITS (HD)               |
| 5340       | ANIPLUS HD              |
| 5342       | Animax (HD)             |
| 5349       | MTV LIVE HD             |
| 6420       | HBO HD                  |
| 6421       | HBO Signature (HD)      |
| 6422       | HBO Family (HD)         |
| 6423       | HBO Hits (HD)           |
| 6424       | CINEMAX (HD)            |
| 5502       | Jia Le Channel (HD)     |
| 6507       | TVBS Asia               |
| 5511       | TVB Jade (HD)           |
| 5512       | now Jelli (HD)          |
| 5513       | ONE HD (Mandarin)       |
| 6516       | TVBS News               |
| 5517       | TVB Xing He (HD)        |
| 5518       | tvN HD (Mandarin)       |
| 5038       | KBS World (HD)          |
| 5528       | tvN Movies On Demand    |
| 5534       | CCTV Entertainment      |
| 5535       | Dragon TV Intl          |
| 5536       | Hunan International     |
| 5537       | BRTV International      |
| 5538       | China Movie Channel     |
| 6547       | Phoenix InfoNews        |
| 5555       | CCTV-4 (HD)             |
| 5557       | CTI Asia (HD)           |
| 5561       | ETTV Asia News (HD)     |
| 6571       | CM+                     |
| 5580       | CCM                     |
| 5585       | Celestial Movies(HD)    |
| 5602       | Astro Prima HD          |
| 5604       | ONE HD (Malay)          |
| 5607       | Pesona HD               |
| 5608       | Astro Ria HD            |
| 5610       | Citra Drama (HD)        |
| 5618       | Drama Channel           |
| 5619       | tvN HD                  |
| 5622       | Sun TV HD               |
| 5623       | Colors Tamil HD         |
| 5624       | Zee Thirai              |
| 5625       | KTV HD                  |
| 5627       | Sun Music HD            |
| 5628       | Adithya TV              |
| 5630       | Sony YAY                |
| 5632       | Zee Tamil HD            |
| 5634       | Vijay TV (HD)           |
| 5638       | Asianet                 |
| 5639       | Asianet Movies          |
| 5644       | SET (HINDI)             |
| 5646       | Zee TV                  |
| 5648       | SAB TV                  |
| 5652       | Colors                  |
| 5654       | Star Bharat             |
| 5656       | STAR Plus               |
| 5658       | MTV India               |
| 5662       | STAR Gold               |
| 5668       | Sony MAX                |
| 5670       | maa movies              |
| 5671       | Star Maa                |
| 5676       | Times Now               |
| 5677       | Zoom TV                 |
| 5680       | WION                    |
| 5682       | NHK World Premium HD    |
| 5040       | France 24 (French)      |
| 5056       | GMA Pinoy TV            |
| 5689       | GMA Life TV             |
| 5690       | GMA News TV Intl        |
| 6692       | Cinema One Global       |
| 5693       | The Filipino Ch (HD)    |
| 6694       | ABS-CBN News Channel    |


