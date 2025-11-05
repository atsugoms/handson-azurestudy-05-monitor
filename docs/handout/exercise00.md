# Exercise0: 初期環境構築（ARMテンプレート）

## 【目次】

![](images/ex00-0000-arm.png)


## Azureへリソースを展開

1. 以下のボタンからテンプレートを展開

    [![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fatsugoms%2Fhandson-azurestudy-05-monitor%2Fmain%2Finfra%2Farm%2Fdeploy-resources.json)

    (*) "Deploy ボタン" からうまく飛べない場合、 以下のJSONファイルをダウンロードして「カスタムテンプレートのデプロイ」に読み込ませる

    [ARMテンプレート JSON ファイル](https://raw.githubusercontent.com/atsugoms/handson-azurestudy-05-monitor/main/infra/arm/deploy-resources.json)

1. Bastion が必要な場合

    Bastionが必要な場合、以下のテンプレートも展開し、 VNet Peering を作成

    [![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fatsugoms%2Fhandson-azurestudy-05-monitor%2Fmain%2Finfra%2Farm%2Fdeploy-vnet-hub.json)


    [ARMテンプレート JSON ファイル](https://raw.githubusercontent.com/atsugoms/handson-azurestudy-05-monitor/main/infra/arm/deploy-vnet-hub.json)
