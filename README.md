# SKYNETchat V1 – Image Downloader para Android (Termux)

**Autor:** SKYNETchat – Domínio público  
**Descrição:**  
Um downloader de imagens rápido e direto para Android usando Termux. Ele pesquisa imagens na internet, salva no armazenamento do Android e força a galeria a atualizar automaticamente.

## ⚙️ Requisitos

1. **Termux atualizado**  
   ```bash
   pkg update && pkg upgrade -y
   pkg install python -y
   pip install requests        # Biblioteca para baixar imagens
   pkg install termux-api -y
   termux-setup-storage -y
   pkg install git -y          # Para clonar ou versionar scripts   
   
   

# ia-de-imagens-ia.2.0

## ⚙ linha única para instalar

1. **Termux atualizado**  
   ```bash
   
   
   pkg update && pkg upgrade -y && \
   pkg install python -y && \
   pip install requests && \
   pkg install termux-api -y && \
   termux-setup-storage -y && \
   pkg install git -y && \
   git clone   https://github.com/snaidermadilus-debug/ia-de-imagens-ia.2.0.git && \
   cd ia-de-imagens-ia.2.0 && \
   python ia.py
   
# ia-de-imagens-ia.2.0




# ia-de-imagens-ia.2.0

Execute o script

python ia.py

⚠️ Observações

ele só vai Imagine se daqui

SAVE_DIR = "/sdcard/Pictures/IA"

Esse link te leva direto à página do cliente oficial do
 F‑Droid, onde você pode baixar 
o APK e instalar no seu celular Android. � para baixar u TERMUX e
 u TERMUX API

👉 https://f-droid.org/en/packages/org.fdroid.fdroid/ 

---

## ✅Funcionalidades
1. **Busca de imagens**  

2. **Download e salvamento**  
   - Salva imagens na pasta configurada (`/sdcard/Pictures/IA` ou outra que você escolher)  
   - Gera nomes seguros e únicos para cada imagem usando timestamp e hash  

3. **Atualização da galeria**  
   - Força o Android a reconhecer as imagens usando:
     - `termux-media-scan`  
     - Broadcast do `android.intent.action.MEDIA_SCANNER_SCAN_FILE`  

4. **Histórico de pesquisas**  
   - Mantém um arquivo `history.txt` com todas as pesquisas realizadas  

5. **Interface interativa (CLI)**  
   - Menu simples para escolher entre:
     1. Baixar uma imagem  
     2. Baixar várias imagens  
     3. Visualizar histórico  
     0. Sair

---

## 📂 Estrutura do Script

- **`ia.py`** → Script principal
- **`history.txt`** → Histórico das buscas (gerado automaticamente)
- **`/sdcard/Pictures/IA`** → Pasta padrão de salvamento das imagens (criada automaticamente)

---

## ⚙️ Requisitos

1. **Termux atualizado**  
   ```bash
   pkg update && pkg upgrade -y
   pkg install python -y
   pip install requests        # Biblioteca para baixar imagens
   pkg install termux-api -y
   termux-setup-storage -y
   pkg install git -y          # Para clonar ou versionar scripts   
   
   pkg update && pkg upgrade -y && pkg install python -y && pip install requests && pkg install termux-api -y && termux-setup-storage -y && pkg install git -y && git clone https://github.com/snaidermadilus-debug/ia-de-imagens-ia.2.0.git && cd ia-de-imagens-ia.2.0 && python ia.py
   
# ia-de-imagens-ia.2.0