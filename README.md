<div align="center">

<img src="public/logo.png" alt="Gem+" width="110" />

# Gem+

**Launcher desktop para simular o tempo de execução de jogos e concluir missões do Discord Quests — de forma automática, local e em segundo plano.**

*Desktop launcher that simulates game runtime to complete Discord Quests — automatically, locally and in the background.*

<br/>

![version](https://img.shields.io/badge/version-1.0.1-E6007A?style=for-the-badge)
![platform](https://img.shields.io/badge/platform-Windows-0a0a0a?style=for-the-badge&logo=windows)
![electron](https://img.shields.io/badge/Electron-33-47848F?style=for-the-badge&logo=electron&logoColor=white)
![supabase](https://img.shields.io/badge/Supabase-Auth-3FCF8E?style=for-the-badge&logo=supabase&logoColor=white)

[**⬇️ Baixar / Download**](https://github.com/dxntagency/Gem/releases/latest) · [**📝 Changelog**](CHANGELOG.md)

</div>

---

## 🇧🇷 Português

### 💎 O que é
O **Gem+** é um launcher desktop com visual premium que simula o tempo de execução de jogos para ajudar a concluir as **missões do Discord Quests**, sem precisar baixar dezenas de jogos pesados. A simulação roda localmente e em segundo plano.

### ✨ Recursos
- 🎮 **Biblioteca com +60 jogos** prontos (FPS, MMO, Anime/Gacha, Survival, Indie e mais), com capas.
- ⏱️ **Quests de 15 minutos** com acompanhamento de progresso em tempo real.
- 🕹️ **Simulação em segundo plano** — inicie e pode fechar o launcher.
- 🔐 **Contas com Supabase** — login por e-mail/senha ou **Google e Discord** (abrindo no navegador, mais seguro).
- 👤 **Perfil personalizável** (foto, nome e username).
- 🕘 **Histórico separado por conta**.
- 🌐 **Bilíngue** — Português e English, troca em tempo real.
- 🎨 Tema escuro premium e atualização automática.

### ⬇️ Instalação
1. Baixe o instalador mais recente em **[Releases](https://github.com/dxntagency/Gem/releases/latest)** (`Gem-Plus-Setup-x.y.z.exe`).
2. Execute, aceite os termos e escolha a pasta de instalação.
3. Pronto! O app se mantém atualizado sozinho a cada nova versão.

### 🛠️ Tecnologias
- **Electron** (app desktop) + **Express** (servidor local embutido)
- **HTML / CSS / JavaScript** (sem framework no front)
- **Supabase** (autenticação e perfis)
- **electron-builder** + **electron-updater** (instalador NSIS e auto-update)

### 👨‍💻 Desenvolvimento
```bash
# Instalar dependências
npm install

# Rodar em modo desktop (Electron)
npm run electron

# Rodar apenas o servidor web (http://localhost:3000)
npm run dev
```

Crie um arquivo **`.env`** na raiz com as credenciais do Supabase:
```env
PORT=3000
SUPABASE_URL=https://SEU-PROJETO.supabase.co
SUPABASE_ANON_KEY=sb_publishable_sua_chave_publica
```
> Use sempre a chave **publishable/anon** (pública). Nunca a chave secreta.

### 🚀 Build e publicação
```bash
# Gerar o instalador localmente (pasta release/)
npm run dist

# Publicar uma nova versão no GitHub Releases (auto-update)
#  1) suba a "version" no package.json
#  2) cole seu token do GitHub em gh-token.txt
npm run release
```

---

## 🇺🇸 English

### 💎 What it is
**Gem+** is a premium desktop launcher that simulates game runtime to help complete **Discord Quests** without downloading dozens of heavy games. The simulation runs locally and in the background.

### ✨ Features
- 🎮 **Library of 60+ ready games** (FPS, MMO, Anime/Gacha, Survival, Indie and more), with cover art.
- ⏱️ **15-minute Quests** with real-time progress tracking.
- 🕹️ **Background simulation** — start it and close the launcher if you want.
- 🔐 **Supabase accounts** — email/password or **Google and Discord** login (opens in the browser, more secure).
- 👤 **Customizable profile** (photo, name and username).
- 🕘 **Per-account history**.
- 🌐 **Bilingual** — Portuguese and English, switch on the fly.
- 🎨 Premium dark theme and automatic updates.

### ⬇️ Installation
1. Download the latest installer from **[Releases](https://github.com/dxntagency/Gem/releases/latest)** (`Gem-Plus-Setup-x.y.z.exe`).
2. Run it, accept the terms and pick the install folder.
3. Done! The app keeps itself updated on every new release.

### 🛠️ Tech stack
- **Electron** (desktop app) + **Express** (embedded local server)
- **HTML / CSS / JavaScript** (no front-end framework)
- **Supabase** (authentication and profiles)
- **electron-builder** + **electron-updater** (NSIS installer and auto-update)

### 👨‍💻 Development
```bash
npm install        # install dependencies
npm run electron   # run as desktop app (Electron)
npm run dev        # run only the web server (http://localhost:3000)
```

Create a **`.env`** file in the root with your Supabase credentials:
```env
PORT=3000
SUPABASE_URL=https://YOUR-PROJECT.supabase.co
SUPABASE_ANON_KEY=sb_publishable_your_public_key
```
> Always use the **publishable/anon** (public) key. Never the secret key.

### 🚀 Build & release
```bash
npm run dist       # build the installer locally (release/ folder)
npm run release    # publish a new version to GitHub Releases (auto-update)
```

---

## ⚠️ Aviso / Disclaimer

**PT:** O Gem+ é fornecido "no estado em que se encontra", para uso pessoal e educacional. O uso é de inteira responsabilidade do usuário, que deve respeitar as leis aplicáveis e os termos de serviço de terceiros (Discord, plataformas de jogos, etc.).

**EN:** Gem+ is provided "as is", for personal and educational use. Use is entirely the user's responsibility and must comply with applicable laws and third-party terms of service (Discord, game platforms, etc.).

<div align="center">
<br/>
<sub>© 2026 Gem+ Project — feito por <b>DXN'T</b></sub>
</div>
