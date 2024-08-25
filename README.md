# Solana Action & Blink

一鍵部署：

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/Fankouzu/solana-action&env=RECIPIENT,BASE_AMOUNT,AVATAR,TITLE,DESCRIPTION&envDescription=Variables%20to%20setup%20your%20own%20information&envLink=https://github.com/Fankouzu/solana-action&project-name=my-blink-donate-action&repository-name=my-blink-donate-action&demo-title=Solana%20blink%20action&demo-description=A%20solana%20blink%20action%20example%20using%20Next.js&demo-url=https://solana-action.vercel.com/api/actions/donate&demo-image=https://raw.githubusercontent.com/Fankouzu/solana-action/main/public/solana_devs.jpg)

在vercel修改環境變量配置：

```shell
RECIPIENT="<Your wallet address>"
BASE_AMOUNT=0.1
TITLE="<Your title>"
AVATAR="<Your avatar URL>"
DESCRIPTION="<Your description>"
```

訪問
https://<你的倉庫名>.vercel.com/api/actions/donate 看到json返回結果就代表部署正確，並且核對你輸入的環境變量

訪問https://dial.to/?action=solana-action%3Ahttps%3A%2F%2F<你的倉庫名>.vercel.app%2Fapi%2Factions%2Fdonate 可以看到你的Blink連結