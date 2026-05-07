<div align="center">

# 🧱 typescript-temp

<p align="center">
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white"/>
  <img src="https://img.shields.io/badge/Discord.js-5865F2?style=for-the-badge&logo=discord&logoColor=white"/>
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white"/>
</p>

<p align="center">
  <img src="https://img.shields.io/github/stars/abdulrahmanqdev/typescript-temp?style=flat-square&color=yellow"/>
  <img src="https://img.shields.io/github/forks/abdulrahmanqdev/typescript-temp?style=flat-square&color=green"/>
  <img src="https://img.shields.io/github/last-commit/abdulrahmanqdev/typescript-temp?style=flat-square&color=orange"/>
</p>

<p align="center">
  <strong>TypeScript kullanmak isteyenler için boş Discord bot altyapısı.</strong><br/>
  Komut, event handler ve utils yapısıyla hazır başlangıç şablonu.
</p>

</div>

---

## 📖 Genel Bakış

**typescript-temp**, Discord botu geliştirmek isteyenler için TypeScript ile hazırlanmış sade ve genişletilebilir bir başlangıç şablonudur. Slash komutları, event handler'lar ve modüler utils yapısıyla hemen geliştirmeye başlayabilirsin.

---

## ✨ Özellikler

- ⚡ Discord.js v14 + TypeScript desteği
- 🗂️ Modüler komut yapısı
- 📡 Event handler sistemi
- 🔧 Slash komutlarını otomatik kaydet (`registerCommands.ts`)
- 🔌 Event'leri otomatik yükle (`registerEvents.ts`)
- 🔒 Tam TypeScript tip güvenliği
- 🪶 Sade ve kolayca genişletilebilir yapı

---

## 🛠️ Teknoloji Yığını

| Teknoloji | Amaç |
|---|---|
| TypeScript | Dil |
| Discord.js | Discord API Kütüphanesi |
| Node.js | Çalışma Ortamı |

---

## 🚀 Başlarken

### Gereksinimler
- Node.js `>= 18.x`
- [Discord Developer Portal](https://discord.com/developers/applications) üzerinden bir bot token'ı

### Kurulum

```bash
git clone https://github.com/abdulrahmanqdev/typescript-temp.git
cd typescript-temp
npm install
```

### Yapılandırma

`src/config.ts` dosyasına bot bilgilerini gir:

```ts
export default {
  token: "BOT_TOKEN_BURAYA",
  clientId: "CLIENT_ID_BURAYA",
  guildId: "GUILD_ID_BURAYA",
}
```

### Slash Komutlarını Kaydet

```bash
npx ts-node src/utils/registerCommands.ts
```

### Çalıştır

```bash
npx ts-node src/index.ts
```

---

## 📁 Proje Yapısı

```
typescript-temp/
├── src/
│   ├── commands/
│   │   └── ping.ts                  # Örnek slash komutu
│   ├── events/
│   │   ├── interactionCreate.ts     # Etkileşim olayı
│   │   └── ready.ts                 # Bot hazır olayı
│   ├── utils/
│   │   ├── registerCommands.ts      # Slash komut kayıt
│   │   └── registerEvents.ts        # Event yükleyici
│   ├── config.ts                    # Bot yapılandırması
│   └── index.ts                     # Ana giriş noktası
├── tsconfig.json
├── package.json
└── LICENSE
```

---

## 🤝 Katkıda Bulunma

1. Repoyu fork'la
2. Yeni dal oluştur (`git checkout -b ozellik/yeni-ozellik`)
3. Değişiklikleri kaydet ve Pull Request aç

---

## 👤 Geliştirici

**@abdulrahmanqdev**
