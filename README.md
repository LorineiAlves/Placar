# 🏐 Placar de Vôlei - App Web + Android

Este é um projeto de placar de vôlei interativo, que também pode ser utilizado para outros esportes, desenvolvido em HTML/CSS/JS, com suporte para execução em navegadores e dispositivos Android via Capacitor. Ideal para uso offline durante partidas reais.

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

```bash
git clone https://github.com/seu-usuario/seu-repositorio.git
cd seu-repositorio
```

### 2. Instalar dependências (se necessário)

Se estiver usando npm:

```bash
npm install
```

### 3. Instalar o Capacitor

```bash
npm install @capacitor/core @capacitor/cli
npx cap init
```

### 4. Criar a pasta Android

```bash
npx cap add android
```

### 5. Copiar os arquivos web para o Android

```bash
npx cap copy android
```

> ⚠️ Sempre rodar esse comando após mudanças no HTML/CSS/JS

### 6. Abrir o projeto no Android Studio

```bash
npx cap open android
```

### 7. Ajustar o AndroidManifest.xml

Certifique-se que o tema esteja assim:

```xml
android:theme="@style/AppTheme.NoActionBar"
```

### 8. Gerar Keystore (opcional, para builds assinadas)

```bash
keytool -genkey -v -keystore meuapp.keystore -alias meuappkey -keyalg RSA -keysize 2048 -validity 10000
```

### 9. Gerar APK ou AAB no Android Studio

- Build > Generate Signed Bundle / APK
- Selecione o keystore
- Siga os passos até concluir

### 10. Rodar no dispositivo Android

- Conecte o celular com modo desenvolvedor ativado
- Clique em **Run 'app'** no Android Studio

---

## 🔄 Atualizando o projeto no GitHub

Sempre que fizer alterações no projeto:

```bash
git status                                          # (opcional) Ver o que mudou
git add .                                           # Adiciona todas as mudanças
git commit -m "Commite exemplo"                     # Descreve a mudança
git push                                            # Envia para o GitHub
git pull origin main --allow-unrelated-histories    # Trás edições do GitHub

```

Atalho para tudo de uma vez:

```bash
git add . && git commit -m "sua mensagem" && git push
```

---

## 🧰 Tecnologias

- HTML5
- CSS3
- JavaScript
- Capacitor
- Android Studio

---

## 📷 Captura de Tela

![App rodando](screenshot.png)
![Ícone App](screenshoticone.png)


---

## 📌 Autor

**Lorinei** - Analista de Sistemas e desenvolvedor de soluções 👨‍💻

---

Se curtiu o projeto, dá uma estrela ⭐ no repositório e compartilha com os amigos da quadra! 🏐

