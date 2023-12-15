<!-- markdownlint-disable MD024 MD033 MD041 -->

<p align="center" dir="auto">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github.com/nitic-pbl-p8/lockerai/assets/85730998/674aea68-3b93-477d-9981-c4966240a9e7">
    <source media="(prefers-color-scheme: light)" srcset="https://github.com/nitic-pbl-p8/lockerai/assets/85730998/9b8973a3-c78a-4810-b296-538aef808d24">
    <img src="https://github.com/nitic-pbl-p8/lockerai/assets/85730998/674aea68-3b93-477d-9981-c4966240a9e7" alt="Locker.ai" width="80%" height="auto" />
  </picture>
</p>

# Locker.ai 🗝️

Locker.ai is a service that uses a unique AI-driven authentication mechanism to safely report and retrieve lost items.
This repository contains the system prompt given to LVLM to caption images of lost items.

## GPT Assistants

You can test out the AI yourself on ChatGPT!

### [Lost Item Descriptor](https://chat.openai.com/g/g-iA2pCCvrs-lost-item-descriptor-by-locker-ai)

Just click the link above and start playing with the AI!
Simply upload the images of lost items and the AI will describe them for you.

#### Example outputs

```json
{
  "success": true,
  "description": "This item is an Anker S21 Power Bank (PowerCore Fusion, 45W). It is a portable battery charger with a light purple or lavender casing. The front face has the Anker logo and a circular button, while the back contains technical specifications. It has a 5000mAh capacity, and input/output details are provided. The side has a USB-C port and a USB-A port. The device is decorated with several stickers, including 'New Jeans' and other designs, suggesting personalization by the owner.",
  "summary": "The item is a lavender Anker PowerCore Fusion portable charger with a 5000mAh capacity, adorned with personal stickers.",
  "title": "Lavender Anker Power Bank",
  "hasSecrets": false
}
```

```json
{
  "success": true,
  "description": "This item is a black leather wallet with tan interior and a wrist strap. The wallet has a metal snap closure and displays signs of use. Inside, it contains multiple card slots filled with various cards, including a T-Card, QUO card, and others, indicating the owner's personal affiliations or memberships.",
  "summary": "The item is a black and tan leather wallet with a wrist strap, containing multiple cards in its slots.",
  "title": "Black Leather Wallet with Cards",
  "hasSecrets": true
}
```

```json
{
  "success": true,
  "description": "This item is a white USB charging cable with a Lightning connector on one end and a USB-C connector on the other. It is neatly coiled and secured with a blue velcro strap.",
  "summary": "The item is a white USB charging cable with Lightning and USB-C connectors, coiled and secured with a blue strap.",
  "title": "White Lightning to USB-C Charging Cable",
  "hasSecrets": false
}
```

### 🚧 [Lost Item Descriptor (日本語)](https://chat.openai.com/g/g-QJeUrMjCZ-lost-item-descriptor-by-locker-ai-ri-ben-yu)

#### Example outputs

```json
{
  "success": true,
  "description": "これは、Ankerブランドのグレーのポータブルバッテリーです。正面には銀色のAnkerロゴと円形のボタンがあります。裏面にはモデル名「PowerCore Fusion 5000」と技術的な情報、警告、製造者情報が記載されており、「Made in China」の文字が見えます。もう一つの面には、カラフルなステッカーがいくつか貼られており、特に「NEW JEANS」と「Hawaii」の文字が印刷されたステッカーが目立ちます。",
  "summary": "これは、Ankerのグレーのモバイルバッテリーで、「PowerCore Fusion 5000」モデルです。カラフルなステッカーが貼られており、特に「NEW JEANS」と「Hawaii」が目立ちます。",
  "title": "Ankerグレーモバイルバッテリー「PowerCore Fusion 5000」",
  "hasSecrets": false
}
```
