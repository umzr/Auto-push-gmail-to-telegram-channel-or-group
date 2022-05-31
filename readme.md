# Auto push gmail to telegram channel or group [Send gmail message 去 Telegram Bot / group / chat]
![issues](https://img.shields.io/github/issues/umzr/Auto-push-gmail-to-telegram-channel-or-group)
![forks](https://img.shields.io/github/forks/umzr/Auto-push-gmail-to-telegram-channel-or-group)
![stars](https://img.shields.io/github/stars/umzr/Auto-push-gmail-to-telegram-channel-or-group)
![](https://img.shields.io/github/license/umzr/Auto-push-gmail-to-telegram-channel-or-group)

Document仲未搞掂 (50%)  
Document in progress (50%)  

TL;DR: Call gmail API and connect telegram bot

# introduction 介紹

<p align="center">
    Author 作者:  
    </br> 
        風信子(Hyacinthus orientalis -- HO): <a href="https://t.me/TeleDele">Telegram</a> 
    </br>
        UMZR: <a href="https://github.com/umzr">Github</a> 
</p>

點解會放上網? 因為我前嗰排(2022)搵唔到 intern。迫不得已求其搵啲project 掉上去Github，希望有人收留我。  
Why I push this things to Github? Cos I need Intern Job, So I some project on Github.  
  
同埋小弟日日睇股票，希望整啲BOT令我自己唔使日日睇市。要記住美國佬瞓醒覺就會搞掂。  
Thus, I always watch US stock market. So HO and I created this bot to save some time not to watch the US stock market. Well, you know, all market are bullish when you wake up.

例如：我哋可以喺gmail收到 TradingView alert  
For example, we can receive tradeview alert from gmail  
![image](https://raw.githubusercontent.com/umzr/Auto-push-gmail-to-telegram-channel-or-group/main/src/image/tradingview_gmail.png?token=GHSAT0AAAAAABUVO6VCDGF6AIKGEH4CTQMAYUMWD2Q)  

個Bot就會自動射啲message過去Telegram  
The bot will send message to Telegram automatically.  
![image](https://raw.githubusercontent.com/umzr/Auto-push-gmail-to-telegram-channel-or-group/main/src/image/tradingview_notice.png?token=GHSAT0AAAAAABUVO6VCVJS7MCYXWZDJQKZWYUMWEDA)

# Instruction 點樣 Deploy

1. goto [@BotFather](https://t.me/BotFather) create new bot
2. copy my script to [google script](https://script.google.com/).
3. plate `TelegramBotToken` and `clientID` to my script
4. set Webhook https://api.telegram.org/bot<`TelegramBotToken`>/setWebhook?url=<`Current web app URL:`>
5. set timmer to Triggers the google web app
6. finish

# FAQ 你問我答

1. Q: 點解樓主英文咁差?  
    Q: Why the author's English grammar is poor?

   A: 我讀緊香港**中文**大學 :+1:  
    A: I am studing at The **Chinese** University of Hong Kong. :+1:

2. Q: 點解仲係睇唔明?  
    Q: Why is still unreadable?

   A: Code 就搞掂咗嘅，我 RUN 咗成年，de 唔 deploy 到睇緣份  
    A: Translate Server Error (I need some time to do the document. )

3. Q: 請說中文，我看不懂你說什麼？  
    Q: Please speak Chinese, I don't understand what you are writting.

    A: ......  
    A: Read English.

4. Q: 同樣係中文字，點解用唔到google翻譯？  
    Q: Why Google translate output some shit?

    A: 係囉，咁奇怪。  
    A: This is [Cantonese 廣東話](https://en.wikipedia.org/wiki/Cantonese)

5. Q: 點解樓主咁得閒整呢啲嘢？  
    Q: Why Author made this Bot?

    A:  沒有offer 的 31 天  
    A: no intern offer 31 days

# Keyword
Telegram  BOT  IFTTT  TradingView Alert  Alarm  

買______記住，升就追，跌就溝，出糧就入貨  
止蝕係多餘，回調姐係特價  
止賺都係多餘，高處未算高  
最好供埋______，心雄既就買埋call  
乜春波動大，槓桿損耗乜乜柒柒理撚得佢，呢啲野唔係我地諗得明，有咩危機美國佬會搞掂，美帝緊張過你，信自己不如信美帝金融霸權  

Remember to buy ______, catch up when you rise, ditch when you fall, and buy in when you export grain

Stop loss department is redundant, call back sister department special price

Just making money is superfluous, and the heights are not high

The volatility of Niechun is big, and the loss of leverage is too much to twist. It is not easy to understand that if there is a crisis, the Yankees will be troubled. The American emperor is nervous about you. Believing in yourself is worse than believing in the American financial hegemony.

#
Last Commit 最後修改日期:  
![](https://img.shields.io/github/last-commit/umzr/Auto-push-gmail-to-telegram-channel-or-group) 