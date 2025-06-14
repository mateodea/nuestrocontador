# Nuestro Contador

Aplicación web para llevar puntuación de juegos de mesa y cartas.

## Estructura del Proyecto

\`\`\`
nuestrocontador/
├── app/
│   ├── layout.tsx
│   ├── page.tsx
│   └── globals.css
├── components/
│   ├── ui/
│   ├── game-selector.tsx
│   ├── player-setup.tsx
│   ├── scoreboard.tsx
│   ├── settings-screen.tsx
│   └── ...
├── types/
│   ├── game.ts
│   └── tournament.ts
├── utils/
│   └── tournament.ts
├── public/
│   ├── manifest.json
│   └── ...
├── package.json
├── next.config.mjs
├── tailwind.config.ts
├── tsconfig.json
├── netlify.toml
└── .nvmrc
\`\`\`

## Instalación

\`\`\`bash
npm install
npm run dev
\`\`\`

## Despliegue

La aplicación está configurada para desplegarse en Netlify con Next.js static export.

## Juegos Soportados

- Truco
- Chinchón
- UNO
- Chancho
- Escoba de 15
- Casita Robada
- Torneos por Llaves

## Contacto

Para consultas: mateodea@live.com
