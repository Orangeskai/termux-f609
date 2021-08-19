# API SERVER ZTE f609
## 🤔 Concept
**This repo need to installed in your termux system**<br />
Basically this script will run the php script for restarting your router with app<br />

### 🌏Language
Right now only Indonesia only and
**Translation maybe kinda late**

### 📱Apps
**Coming soon :)**

### ✍️ Install the api server
```script
bash <(curl https://raw.githubusercontent.com/Orangeskai/termux-f609/main/set)

```

### 📝Editing the config == **REQUIRED FOR FIRST TIME**
```script
f609 --config
```

### ✨ Run the api
**For stop it just pressed ctrl + c in termux**
```shell
f609 
```

### 🛠️ Commnad
| Command          | Description                                                       |
| ---------------- | ----------------------------------------------------------------- |
| f609             | Start the api server == **For stopping press ctrl + c**           |
| f609 --help      | Show the help page                                                |
| f609 --config    | Edit the config file **REQUIRED for first time**                  |
| f609 --uninstall | Uninstall this api completely with php server also                |
| f609 --remove    | Only remove the rest of api not deleting php server               |

### ⁉️ Q&A
1. Why you not include it in the app so it just AIO ????<br />
- Good question because im dumb and kinda busy maybe also lazy

2. I had problem or bug please fix this ASAP<br />
- Sorry im kinda busy also after this maybe im not maintain this script maybe just make better the app hopefully

3. Can i to run it without the app ??<br />
Yes you can just type in your browser or click this **But dont forget to change the config first** 
- **http://localhost:8809/ip.php for checking ip** and
- **http://localhost:8809/res.php for restart the modem**.

### 🙏 Thanks for :
- Library from [Walangkaji](https://github.com/walangkaji), [Paypal](https://www.paypal.me/walangkaji)
- Terminal env from [Termux](https://termux.com/)
