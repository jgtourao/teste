# Rotas Pai D'Água

Aplicação web para explorar pontos turísticos, praias, hotéis e restaurantes em Belém do Pará, com funcionalidade de criação de rotas personalizadas.

## 🚀 Funcionalidades

- **Exploração de Locais**: Navegue por categorias (pontos turísticos, praias, hotéis, restaurantes)
- **Mapa Interativo**: Visualize todos os locais em um mapa usando Leaflet
- **Criação de Rotas**: Crie rotas personalizadas com múltiplas paradas
- **Navegação GPS**: Obtenha direções a pé ou de carro
- **Geolocalização**: Encontre sua localização atual no mapa

## 🛠️ Tecnologias

- **Next.js 15** - Framework React
- **TypeScript** - Tipagem estática
- **Tailwind CSS** - Estilização
- **Leaflet** - Mapas interativos
- **OSRM** - Cálculo de rotas

## 📦 Instalação

\`\`\`bash
# Instalar dependências
npm install

# Executar em desenvolvimento
npm run dev

# Build para produção
npm run build
npm start
\`\`\`

## 📁 Estrutura do Projeto

\`\`\`
├── app/
│   ├── page.tsx              # Página principal
│   └── layout.tsx            # Layout raiz
├── components/
│   ├── header.tsx            # Cabeçalho com logo
│   ├── main-menu.tsx         # Menu principal
│   ├── lista-locais.tsx      # Lista de locais por categoria
│   ├── mapa-container.tsx    # Container do mapa
│   ├── mapa-leaflet.tsx      # Componente do mapa Leaflet
│   └── painel-controles.tsx  # Painel de controles de rota
├── lib/
│   ├── types.ts              # Tipos TypeScript
│   └── locais-data.ts        # Dados dos locais
└── public/
    ├── logo.png              # Logo da aplicação
    ├── fundo.jpg             # Imagem de fundo
    └── ...                   # Outros assets
\`\`\`

## 🎨 Imagens Necessárias

Adicione as seguintes imagens na pasta `public/`:

- `logo.png` - Logo da aplicação
- `fundo.jpg` - Imagem de fundo
- `botao.jpg` - Textura dos botões
- `turistico.jpg` - Ícone pontos turísticos
- `praia.png` - Ícone praias
- `hotel.png` - Ícone hotéis
- `restaurante.png` - Ícone restaurantes
- `rotas.png` - Ícone criar rota

## 📝 Licença

MIT
