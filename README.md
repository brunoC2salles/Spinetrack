# SpineTrack — Landing Page

Site institucional da plataforma SpineTrack, desenvolvido para deploy via Vercel.

## Deploy

### Via Vercel (recomendado)
1. Faça push deste repositório para o GitHub
2. Acesse [vercel.com](https://vercel.com) e importe o repositório
3. Framework Preset: **Other**
4. Build Command: *(deixar vazio)*
5. Output Directory: *(deixar vazio — raiz do projeto)*
6. Clique em **Deploy**

### Via Vercel CLI
```bash
npm i -g vercel
vercel --prod
```

## Estrutura
```
spinetrack-site/
├── index.html      # Landing page completa (self-contained)
├── vercel.json     # Configuração de headers e rotas
├── .gitignore
└── README.md
```

## Atualizar a logo
A logo está embutida em base64 dentro do `index.html`.  
Para substituir: localize `data:image/png;base64,` e substitua pelo novo base64.

## Contato
contato@spinetrack.com.br  
WhatsApp: +55 55 92481-0050
