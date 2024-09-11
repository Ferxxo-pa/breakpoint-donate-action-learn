# Solana Action & Blink

One-Click Deployment:

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/Fankouzu/solana-action&env=RECIPIENT,BASE_AMOUNT,AVATAR,TITLE,DESCRIPTION&envDescription=Variables%20to%20setup%20your%20own%20information&envLink=https://github.com/Fankouzu/solana-action&project-name=my-blink-donate-action&repository-name=my-blink-donate-action&demo-title=Solana%20blink%20action&demo-description=A%20solana%20blink%20action%20example%20using%20Next.js&demo-url=https://solana-action.vercel.com/api/actions/donate&demo-image=https://raw.githubusercontent.com/Fankouzu/solana-action/main/public/solana_devs.jpg)

Configure the environment variables in Vercel:

```shell
RECIPIENT="<Your wallet address>"
BASE_AMOUNT=0.1
TITLE="<Your title>"
AVATAR="<Your avatar URL>"
DESCRIPTION="<Your description>"
```

Visit https://<your-repository-name>.vercel.com/api/actions/donate to see the JSON response. If it shows correctly, your deployment was successful, and you can verify the environment variables you entered.

Visit https://dial.to/?action=solana-action%3Ahttps%3A%2F%2F<your-repository-name>.vercel.app%2Fapi%2Factions%2Fdonate to view your Blink link.
