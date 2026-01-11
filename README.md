# DramaBox 🎬

Website streaming drama Pendek Gratis.

## 🚀 Fitur

- **Beranda** - Drama yang dipersonalisasi untuk kamu
- **Terbaru** - Drama-drama terbaru yang baru rilis
- **Terpopuler** - Drama trending yang sedang banyak ditonton
- **Sulih Suara** - Drama dengan dubbing bahasa Indonesia
- **Detail Drama** - Informasi lengkap, sinopsis, dan pemeran
- **Video Player** - Streaming dengan pilihan resolusi, auto-next episode

## 🛠️ Tech Stack

- **Framework**: [Next.js 16](https://nextjs.org/) (App Router)
- **Styling**: [Tailwind CSS](https://tailwindcss.com/)
- **UI Components**: [shadcn/ui](https://ui.shadcn.com/)
- **State Management**: [TanStack Query](https://tanstack.com/query)
- **Icons**: [Lucide React](https://lucide.dev/)

## 📦 Instalasi

```bash
# Clone repository
git clone https://github.com/Slavecode/dramabox
cd dramabox

# Install dependencies
npm install

# Jalankan development server
npm run dev
```

Buka [http://localhost:3000](http://localhost:3000) di browser.

## 🔧 Scripts

| Command | Description |
|---------|-------------|
| `npm run dev` | Jalankan development server |
| `npm run build` | Build untuk production |
| `npm run start` | Jalankan production server |
| `npm run lint` | Jalankan ESLint |

## 📁 Struktur Project

```
src/
├── app/                    # Next.js App Router pages
│   ├── api/dramabox/      # API Routes (proxy ke backend)
│   ├── detail/[bookId]/   # Halaman detail drama
│   ├── watch/[bookId]/    # Halaman video player
│   ├── terbaru/           # Halaman drama terbaru
│   ├── terpopuler/        # Halaman drama trending
│   └── sulih-suara/       # Halaman dubbing Indonesia
├── components/            # React components
│   └── ui/                # shadcn/ui components
├── hooks/                 # Custom React hooks
├── lib/                   # Utility functions
├── styles/                # Global CSS
└── types/                 # TypeScript types
```