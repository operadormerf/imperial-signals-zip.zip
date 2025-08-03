# 📡 Painel Imperial de Sinais com IA Neural

Sistema React para leitura de sinais de mercado com análise automática, gráficos interativos BTC e XAU/USD, e envio via Telegram.

## 🔧 Tecnologias
- React + Chart.js
- TailwindCSS
- Axios (consumo de API)
- Telegram Bot API
- Exportação CSV

## 🚀 Como rodar
```bash
npm install
npm run dev
```

## 🧠 Funcionalidades
- Leitura de padrões técnicos
- Precisão aleatória simulada
- Envio automático de sinais
- Histórico exportável
- Gráficos com Médias Móveis (MA50, MA75, MA100)

## 🛡️ Segurança
Configure um arquivo `.env` na raiz:
```
VITE_TWELVE_API=your_twelvedata_api_key
VITE_TELEGRAM_URL=https://api.telegram.org/botXXXX/sendMessage?chat_id=XXXX
```

## 🧩 Expansão futura
- Integração com IA real (tensorflow.js)
- Backtest de sinais
- Supabase para login e histórico em nuvem
