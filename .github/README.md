<img src="https://telegra.ph/file/6f85dc68c2c347ca763e3.jpg" align="center" width="300" height="200"/>

# Zetsu Music Bot <img src="https://img.shields.io/github/v/release/damsyx/ZetsuMusic?color=black&logo=github&logoColor=black&style=social" alt="RELEASE">

[Zetsu Music Bot](https://github.com/damsyx/ZetsuMusic) is a Powerful Telegram Music+Video Bot written in Python using Pyrogram and Py-Tgcalls by which you can stream songs, video and even live streams in your group calls via various sources.

* Youtube, Soundcloud, Apple Music, Spotify, Resso, Live Streams and Telegram Audios & Videos support.
* Written from scratch, making it stable and less crashes with attractive thumbnails.
* Loop, Seek, Shuffle, Specific Skip, Playlists etc support
* Multi-Language support


# ⚡️ Getting Started

### Before deploying Zetsu Music Bot , please have a look towards [all available config vars](../config/README.md) , also please check [all available commands](../strings/command.yml) of the project.

## 🖇 Generating Pyrogram String Session

- Generate a Pyrogram String Session via [Telegram String Generation Bot](https://t.me/ZetsuStringBot)

# Deployment on Heroku or VPS

<details>
<summary><b> 🚀 Heroku Deployment</b></summary>
<br>

<h4>Click the button below to deploy Zetsu on Heroku!</h4>    
<a href="https://heroku.com/deploy?template=https://github.com/damsyx/ZetsuMusic"><img src="https://img.shields.io/badge/Deploy%20To%20Heroku-blueviolet?style=for-the-badge&logo=heroku" width="200""/></a>

<h4>Click the button below to deploy Zetsu on bot Telegram!</h4>
<a href="https://telegram.dog/XTZ_HerokuBot?start=ZGFtc3l4L1pldHN1TXVzaWMgbWFzdGVy"><img src="https://img.shields.io/badge/Deploy%20To%20Bot%20Telegram-blue?style=for-the-badge&logo=telegram" width="200""/></a>
</details>

<details>
<summary><b>⚡ Deploy on VPS</b></summary>
<br>
    
### Tutorial Deploy on VPS
- Upgrade & Update :
```sh
sudo apt-get update && sudo apt-get upgrade -y
```
- Menginstal Paket yang Diperlukan :
```sh
sudo apt-get install python3-pip ffmpeg -y
```
- install pip :
```sh
sudo pip3 install -U pip
```
- Install Node
```sh
curl -fssL https://deb.nodesource.com/setup_17.x | sudo -E bash - && sudo apt-get install nodejs -y && npm i -g npm
```
- cloning repository
```sh
git clone https://github.com/damsyx/ZetsuMusic
```
- ubah direktori.
```sh
cd ZetsuMusic
```
- install requirements
```sh
pip3 install -U -r requirements.txt
```
- mengganti nama sample.env dengan .env
```sh
cp sample.env .env
```
- Masuk ke .env
```sh
nano .env
```
- Masukan semua data data bot music mu disitu
- Setelah semua data dimasukan silahkan 
```sh
ctrl + s dan x
```
- Buat Screen agar bot Aktif terus menerus 
```sh
screen -S ZetsuMusic
```
- Mulai Jalanin Bot :
```sh
bash start
```

</details>

## 🗂 License

This project is licensed under the **GNU General Public License v3**. All designs were created by [@xflsdam](https://github.com/damsyx) .

See [LICENSE](../LICENSE) for more information.

Special thanks to these amazing projects/people which/who help power Zetsu Music Bot:

- [Pyrogram](https://github.com/pyrogram/pyrogram)
- [Py-Tgcalls](https://github.com/pytgcalls/pytgcalls)
- [CallsMusic Team](https://github.com/Callsmusic)
- [TheHamkerCat](https://github.com/TheHamkerCat)
- [Charon Baglari](https://github.com/XCBv021)
- [TeamYukki](https://github.com/TeamYukki)
