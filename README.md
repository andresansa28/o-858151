# Orangery Ventures

Un sito web moderno e responsivo per Orangery Ventures, costruito con React, TypeScript e Tailwind CSS.

## 🚀 Panoramica

Orangery Ventures è una piattaforma di venture capital che si concentra su founder diversificati e sottovalutati, con particolare attenzione al mercato baltico. Il sito presenta la filosofia di investimento, l'approccio e la community dell'azienda.

## 🛠️ Tecnologie Utilizzate

- **React 18** - Libreria per l'interfaccia utente
- **TypeScript** - Superset tipizzato di JavaScript
- **Vite** - Build tool e dev server ultrarapido
- **Tailwind CSS** - Framework CSS utility-first
- **shadcn/ui** - Componenti UI riutilizzabili
- **React Router Dom** - Routing lato client
- **TanStack Query** - Gestione dello stato server
- **Radix UI** - Componenti headless accessibili
- **Framer Motion** (tramite animazioni custom) - Animazioni
- **Docker** - Containerizzazione dell'applicazione

## 📁 Struttura del Progetto

```
├── public/                     # File statici
│   └── lovable-uploads/       # Immagini caricate
├── src/
│   ├── components/            # Componenti React
│   │   ├── ui/               # Componenti shadcn/ui
│   │   ├── ui-custom/        # Componenti UI personalizzati
│   │   ├── animations/       # Componenti di animazione
│   │   ├── About.tsx         # Sezione Chi Siamo
│   │   ├── Community.tsx     # Sezione Community
│   │   ├── Footer.tsx        # Footer del sito
│   │   ├── Gap.tsx           # Sezione Gap
│   │   ├── Header.tsx        # Header e navigazione
│   │   ├── Hero.tsx          # Sezione hero principale
│   │   ├── InvestmentApproach.tsx # Approccio agli investimenti
│   │   ├── Manifesto.tsx     # Tesi di investimento
│   │   └── FoundersInSearch.tsx # Founder ricercati
│   ├── hooks/                # Custom hooks
│   ├── lib/                  # Utilità e configurazioni
│   ├── pages/                # Pagine dell'applicazione
│   │   ├── Index.tsx         # Pagina principale
│   │   └── NotFound.tsx      # Pagina 404
│   ├── App.tsx              # Componente root
│   ├── main.tsx             # Entry point
│   └── index.css            # Stili globali e design system
├── docker-compose.yml        # Configurazione Docker Compose
├── Dockerfile               # Configurazione Docker
├── nginx.conf              # Configurazione Nginx
└── tailwind.config.ts      # Configurazione Tailwind
```

## 🎨 Design System

Il progetto utilizza un design system basato su token semantici definiti in `src/index.css`:

- **Colori**: Palette di colori coerente con varianti per light/dark mode
- **Tipografia**: Font serif per titoli e font sans per il corpo del testo  
- **Spaziature**: Sistema di spaziature consistente
- **Animazioni**: Transizioni fluide e naturali

## 🚀 Avvio Rapido

### Prerequisiti

- Node.js 18+ 
- npm o yarn

### Installazione

1. **Clona il repository**
   ```bash
   git clone <URL_DEL_REPOSITORY>
   cd orangery-ventures
   ```

2. **Installa le dipendenze**
   ```bash
   npm install
   ```

3. **Avvia il server di sviluppo**
   ```bash
   npm run dev
   ```

4. **Apri il browser**
   
   Il sito sarà disponibile su `http://localhost:8080`

### Build di Produzione

```bash
# Crea la build di produzione
npm run build

# Anteprima della build
npm run preview
```

## 🐳 Docker

### Build e Run con Docker

```bash
# Build dell'immagine Docker
docker build -t orangery-ventures .

# Run del container
docker run -p 3000:80 orangery-ventures
```

### Utilizzo con Docker Compose

```bash
# Avvia tutti i servizi
docker-compose up -d

# Fermati servizi
docker-compose down
```

Il sito sarà disponibile su `http://localhost:3000`

## 🧩 Componenti Principali

### Sezioni del Sito

- **Hero**: Sezione principale con immagine di background e messaging chiave
- **Manifesto**: Tesi di investimento e filosofia aziendale
- **Gap**: Descrizione del gap di mercato identificato
- **FoundersInSearch**: Tipologie di founder ricercati
- **InvestmentApproach**: Approccio agli investimenti
- **About**: Informazioni sull'azienda
- **Community**: Sezione community e network
- **Footer**: Contatti e link utili

### Animazioni

Il progetto utilizza animazioni custom tramite il componente `FadeIn` per creare transizioni fluide durante lo scroll.

## 🔧 Configurazione

### Tailwind CSS

La configurazione Tailwind è estesa con:
- Colori personalizzati del brand
- Font personalizzati
- Animazioni custom
- Breakpoint responsivi

### Vite

Configurazione ottimizzata per:
- Hot Module Replacement (HMR)
- Alias di path (`@/` per `src/`)
- Build ottimizzata per produzione

## 📱 Responsività

Il sito è completamente responsivo con breakpoint per:
- Mobile: < 768px
- Tablet: 768px - 1024px  
- Desktop: > 1024px

## 🌐 SEO e Performance

- Meta tag ottimizzati
- Immagini ottimizzate
- Lazy loading
- Code splitting automatico
- Compression gzip (via Nginx)
- Cache headers per asset statici

## 🤝 Contribuzioni

1. Fork del progetto
2. Crea un branch per la feature (`git checkout -b feature/AmazingFeature`)
3. Commit delle modifiche (`git commit -m 'Add some AmazingFeature'`)
4. Push al branch (`git push origin feature/AmazingFeature`)
5. Apri una Pull Request

## 📄 Licenza

Questo progetto è distribuito sotto licenza MIT. Vedi il file `LICENSE` per maggiori informazioni.

## 📞 Contatti

**Orangery Ventures**
- Website: [orangeryventures.com](https://orangeryventures.com)
- Email: info@orangeryventures.com

---

Realizzato con ❤️ da Orangery Ventures