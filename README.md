# 🏐 Placar de Vôlei - App Web + Android

Este é um projeto de placar de vôlei interativo, desenvolvido em HTML/CSS/JS, com suporte para execução em navegadores e dispositivos Android via Capacitor. Ideal para uso offline durante partidas reais.

---

## 🚀 Funcionalidades

- Placar dividido por time (toque para pontuar)
- Botões para remover pontos
- Cronômetro com minutos e segundos
- Relógio digital no canto superior direito
- Interface responsiva para telas com entalhe (notch)
- Ícone personalizado do app Android

---

## 📦 Como rodar o projeto do zero

### 1. Clonar o repositório

git clone https://github.com/LorineiAlves/Placar.git
cd seu-repositorio


### 2. Instalar dependências (se necessário)
Se estiver usando npm:

npm install


### 3. Instalar o Capacitor

npm install @capacitor/core @capacitor/cli
npx cap init


### 4. Criar a pasta Android

npx cap add android


### 5. Copiar os arquivos web para o Android

npx cap copy android


> ⚠️ Sempre rodar esse comando após mudanças no HTML/CSS/JS

### 6. Abrir o projeto no Android Studio

npx cap open android


### 7. Ajustar o AndroidManifest.xml
Certifique-se que o tema esteja assim:

android:theme="@style/AppTheme.NoActionBar"


### 8. Gerar Keystore (opcional, para builds assinadas)

keytool -genkey -v -keystore meuapp.keystore -alias meuappkey -keyalg RSA -keysize 2048 -validity 10000


### 9. Gerar APK ou AAB no Android Studio
- Build > Generate Signed Bundle / APK
- Selecione o keystore
- Siga os passos até concluir

### 10. Rodar no dispositivo Android
- Conecte o celular com modo desenvolvedor ativado
- Clique em **Run 'app'** no Android Studio

---

## 🧰 Tecnologias

- HTML5
- CSS3
- JavaScript
- Capacitor
- Android Studio

---

## 📷 Captura de Tela

*(adicione uma imagem do app em funcionamento aqui)*

---

## 📌 Autor
**Lorinei** - Analista de Sistemas e desenvolvedor de soluções 👨‍💻

---

Se curtiu o projeto, dá uma estrela ⭐ no repositório e compartilha com os amigos da quadra! 🏐

