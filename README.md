
# AIO Music Helper

An all-in-one bot to handle all your musomaniac needs
## Features

- Supports Spotify, Deezer, Tidal, Qobuz, KKBOX
## Installation
**Pre-req :** Docker & Git installed  

Clone the github repo
```
git clone https://github.com/vinayak-7-0-3/AIO-Music-Helper
```  
Get into the directory AIO-Music-Helper
```
cd AIO-Music-Helper
```
Fill in the sample.env file  
Use nano or any editor as you like
```
nano sample.env
```
Build the docker image
```
sudo docker build . -t aiomusic
```
Run the image
```
sudo docker run -d --name aiom aiomusic
```
To check the logs
```
sudo docker container logs aiom
```




## ⚛️ Deploying on Heroku

<p><a href="https://dashboard.heroku.com/new?button-url=https%3A%2F%2Fgithub.com%2F&template=https://github.com/CangkirKosong/AIO-GRUP-TIDAL"> <img src="https://img.shields.io/badge/Deploy%20To%20Heroku-blueviolet?style=for-the-badge&logo=heroku" alt="Deploy to Heroku" /></a></p>


## Credits
- **Yaronzz** - For [Tidal-Media-Downloader](https://github.com/yaronzz/Tidal-Media-Downloader)
- [**Orpheus-DL Community**](https://github.com/yarrm80s/orpheusdl) - For KKBOX and Deezer 
- **vitiko98** - For [qobuz-dl](https://github.com/vitiko98/qobuz-dl)
- **ZSpotify** - For Spotify
