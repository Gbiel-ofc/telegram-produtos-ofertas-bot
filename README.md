
# Bot Telegram - Resumo de Ofertas

Este bot recebe links de produtos (Amazon, Shopee, Mercado Livre e Magazine Luiza) e responde automaticamente com um resumo formatado contendo título, preço e desconto.

## Funcionalidades

- Responde links enviados no Telegram
- Suporta as seguintes lojas:
  - Amazon
  - Shopee
  - Mercado Livre
  - Magazine Luiza
- Roda online 24h via Render.com usando webhook

## Como usar

### 1. Clonar o repositório
```bash
git clone https://github.com/seu-usuario/telegram-produtos-ofertas-bot.git
cd telegram-produtos-ofertas-bot
```

### 2. Instalar dependências
```bash
pip install -r requirements.txt
```

### 3. Executar localmente
```bash
python bot.py
```

### 4. Variáveis de ambiente necessárias (no Render)
- `BOTTOKEN`: Token do bot do Telegram
- `WEBHOOK_URL`: URL do Render que será usada como webhook

---

Desenvolvido por Gabriel Nascimento
