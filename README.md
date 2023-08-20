# Subtitle Downloader

[![zh](https://img.shields.io/badge/lang-中文-blue)](https://github.com/wayneclub/Subtitle-Downloader/blob/main/README.zh-Hant.md)

**NON-COMMERCIAL USE ONLY**

Subtitle-Downloader supports downloading subtitles from multiple streaming services, such as Disney Plus, HBOGO Asia, KKTV, LineTV, friDay Video, CatchPlay, iq.com, Viu (support HK and SG without vpn), WeTV, NowE, Now Player, AppleTV Plus, iTunes and etc.

## DESCRIPTION

Subtitle-Downloader is a command-line program to download subtitles from the most popular streaming platform. It requires the Python interpreter, version 3.6+, and is not platform specific. It should work on Linux, on Windows or on macOS. This project is only for personal research and language learning.

## INSTALLATION

- Linux:
```
pip install -r requriements
```

- Windows: Execute install_requirements.bat

## USAGE

- Online **_(Colab environment is in the US, if you want to use in other region please execute on local)_**
  1. Connect Colab
  2. Install the requirements (Click 1st play button)
  3. Depend the download platform and modify the text field  (Cick the play button next to it when modified complete)
  4. Download the subtitles from the left side menu

  <a href="https://colab.research.google.com/drive/1Qu7MHUt4QXym9cNOORCKTezIBYBNNg3V?usp=sharing" target="_blank"><img src="https://colab.research.google.com/assets/colab-badge.svg" title="Open this file in Google Colab" alt="Colab"/></a>

- Local

  1. Depend on download platform and modify Subtitle-Downloader/configs/config.py
  2. Follow each platform requirements and put cookies.txt into Subtitle-Downloader/configs/cookies
  3. Execute the program with command line or Subtitle-Downloader.bat (Paste title url)
  ```
  python subtitle_downloader.py URL [OPTIONS]
  ```


## OPTIONS

```
  -h, --help                    show this help message and exit

  -s --season                   download season [0-9]

  -e --episode                  download episode [0-9]

  -l, --last-episode            download last episode

  -o, --output                  output directory

  -email, --email               account for Disney Plus and HBOGO Asia

  -password, --password         password for Disney Plus and HBOGO Asia

  -slang, --subtitle-language   languages of subtitles; use commas to separate multiple languages
                                default: Traditional Chinese
                                all: download all available languages

  -alang, --audio-language      languages of audio-tracks; use commas to separate multiple languages

  -p, --proxy                   proxy
```



## Subtitle Languages

Disney+

| Codec         | Language                           | 語言                         |
| ------------- | ---------------------------------- | ---------------------------- |
| en            | English [CC]                       | 英文                         |
| zh-Hant       | Chinese (Traditional)              | 台繁                         |
| zh-Hans       | Chinese (Simplified)               | 簡中                         |
| zh-HK         | Cantonese                          | 港繁                         |
| da            | Dansk                              | 丹麥文                       |
| de            | Deutsch                            | 德文                         |
| de-forced     | Deutsch [forced]                   | 德文 [強制軌]                |
| es-ES         | Español                            | 西班牙文                     |
| es-ES-forced  | Español [forced]                   | 西班牙文 [強制軌]            |
| es-419        | Español (Latinoamericano)          | 西班牙文（拉丁美洲）         |
| es-419-forced | Español (Latinoamericano) [forced] | 西班牙文（拉丁美洲）[強制軌] |
| fr-FR         | Français                           | 法文                         |
| fr-FR-forced  | Français [forced]                  | 法文 [強制軌]                |
| fr-CA         | Français (Canadien)                | 法文（加拿大）               |
| fr-CA-forced  | Français (Canadien) [forced]       | 法文（加拿大）[強制軌]       |
| it            | Italiano                           | 義大利文                     |
| it-forced     | Italiano [forced]                  | 義大利文 [強制軌]            |
| ja            | Japanese                           | 日文                         |
| ja-forced     | Japanese [forced]                  | 日文 [強制軌]                |
| ko            | Korean                             | 韓文                         |
| ko-forced     | Korean [forced]                    | 韓文 [強制軌]                |
| nl            | Nederlands                         | 荷蘭文                       |
| no            | Norsk                              | 挪威文                       |
| pl            | Polski                             | 波蘭文                       |
| pl-forced     | Polski [forced]                    | 波蘭文 [強制軌]              |
| pt-PT         | Português                          | 葡萄牙文                     |
| pt-BR         | Português (Brasil)                 | 葡萄牙文（巴西）             |
| pt-BR-forced  | Português (Brasil) [forced]        | 葡萄牙文（巴西）[強制軌]     |
| fi            | Suomi                              | 芬蘭文                       |
| sv            | Svenska                            | 瑞典文                       |

HBOGO Asia

| Codec   | Language            | 語言     |
| ------- | ------------------- | -------- |
| en      | English             | 英文     |
| zh-Hant | Traditional Chinese | 繁體中文 |
| zh-Hans | Simplified Chinese  | 簡體中文 |
| ms      | Malay               | 馬來文   |
| th      | Thai                | 泰文     |
| id      | Indonesian          | 印尼文   |

iq.com

| Codec   | Language            | 語言     |
| ------- | ------------------- | -------- |
| en      | English             | 英文     |
| zh-Hant | Traditional Chinese | 繁體中文 |
| zh-Hans | Simplified Chinese  | 簡體中文 |
| ms      | Malay               | 馬來文   |
| vi      | Vietnamese          | 越南文   |
| th      | Thai                | 泰文     |
| id      | Indonesian          | 印尼文   |
| es      | Spanish             | 西班牙文 |
| ko      | Korean              | 韓文     |
| ar      | Arabic              | 阿拉伯文 |

Viu
| Codec | Language | 語言 |
| --- | --- | --- |
| en | English | 英文 |
| zh-Hant | Traditional Chinese | 繁體中文 |
| zh-Hans | Simplified Chinese | 簡體中文 |
| ms | Malay | 馬來文 |
| th | Thai | 泰文 |
| id | Indonesian | 印尼文 |
| my | Burmese | 緬甸文 |

WeTV
| Codec | Language | 語言 |
| --- | --- | --- |
| en | English | 英文 |
| zh-Hant | Traditional Chinese | 繁體中文 |
| zh-Hans | Simplified Chinese | 簡體中文 |
| ms | Malay | 馬來文 |
| th | Thai | 泰文 |
| id | Indonesian | 印尼文 |
| pt | Português | 葡萄牙文 |
| es | Spanish | 西班牙文 |
| ko | Korean | 韓文 |

## Friday Video

1. Install https://chrome.google.com/webstore/detail/get-cookiestxt-locally/cclelndahbckbenkjhflpdbgdldlbecc
2. Login Friday Video, and use this plugin download video.friday.tw_cookies.txt (Don't modify anything even the file name)
3. Put cookie.txt into Subtitle-Downloader/configs/cookies
4. Make sure the movies or series which you're going to download is playable in your region.

## CatchPlay

1. Install https://chrome.google.com/webstore/detail/get-cookiestxt-locally/cclelndahbckbenkjhflpdbgdldlbecc
2. Login CatchPlay, and use this plugin download catchplay.com_cookies.txt (Don't modify anything even the file name)
3. Put cookie.txt into Subtitle-Downloader/configs/cookies
4. Make sure the movies or series which you're going to download is playable in your region.

## Now E, Now Player

1. Install https://chrome.google.com/webstore/detail/get-cookiestxt-locally/cclelndahbckbenkjhflpdbgdldlbecc
2. Login NowE, and use this plugin download nowe.com_cookies.txt (Don't modify anything even the file name)
3. Copy user-agent from login browser (https://www.whatsmyua.info/) and paste it in Subtitle-Downloader/configs/config.py (USER_AGENT). The user-agent must be same as login browser user-agent.
3. Put cookie.txt into Subtitle-Downloader/configs/cookies
4. Make sure the movies or series which you're going to download is playable in your region.

## iq.com

1. Install https://chrome.google.com/webstore/detail/get-cookiestxt-locally/cclelndahbckbenkjhflpdbgdldlbecc
2. Use this plugin download iq.com_cookies.txt (Don't modify anything even the file name)
3. Put cookie.txt into Subtitle-Downloader/configs/cookies
4. Install NodeJS https://nodejs.org/en/download (Windows install .msi)
5. Make sure the movies or series which you're going to download is playable in your region.

## WeTV

1. Install https://chrome.google.com/webstore/detail/get-cookiestxt-locally/cclelndahbckbenkjhflpdbgdldlbecc
2. Use this plugin download wetv.vip_cookies.txt (Don't modify anything even the file name)
3. Put cookie.txt into Subtitle-Downloader/configs/cookies
4. Make sure the movies or series which you're going to download is playable in your region.

## AppleTV+ (iTunes)

1. Install https://chrome.google.com/webstore/detail/get-cookiestxt-locally/cclelndahbckbenkjhflpdbgdldlbecc
2. Use this plugin download tv.apple.com_cookies.txt (Don't modify anything even the file name)
3. Put cookie.txt into Subtitle-Downloader/configs/cookies
4. Make sure the movies or series which you're going to download is playable in your region.


## More Examples
- Download all seasons and all episodes
```
python subtitle_downloader.py URL
```

- Download season 1 episode 1
```
python subtitle_downloader.py URL -s 1 -e 1
```

- Download season 1 episode 1's subtitle with all langugages
```
python subtitle_downloader.py URL -s 1 -e 1 -slang all
```

- Download all episodes subtitles with all langugages: en, zh-Hant
```
python subtitle_downloader.py https://www.disneyplus.com/series/loki/6pARMvILBGzF -slang en,zh-Hant
```

- Download latest episode
```
python subtitle_downloader.py URL -l
```

- Download season 1 episode 1-10
```
python subtitle_downloader.py URL -s 1 -e 1-10
```

- Download season 1 episode 1,3,5
```
python subtitle_downloader.py URL -s 1 -e 1,3,5
```

- Download season 1 with proxy (clash)
```
python subtitle_downloader.py URL -p http://127.0.0.1:7890
```

## FAQ

- Any issue during downloading subtitles, upload the screenshot and log file (Please provide title, platform and region).
- Make sure the video contains embedded subtitles and it is playable in your region.

