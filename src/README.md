# 🎓 LesCatur - Platform Kursus Catur Indonesia

Platform kursus catur komprehensif dengan video pembelajaran, e-book, kelas virtual 1-on-1, dan AI trainer untuk semua level.

## 🚨 FIX ERROR 403 - BACA INI DULU!

**Jika mendapat error:**
```
Error 403: XHR for "/api/integrations/supabase/.../edge_functions/make-server/deploy"
```

**➡️ Baca file `SETUP_NOW.md` untuk solusi lengkap!**

---

## ✨ Fitur Utama

- 📹 **Video Kursus** - Kursus catur lengkap dari pemula hingga mahir
- 📚 **E-Book** - Koleksi buku strategi, taktik, dan opening catur
- 🎯 **Kelas Virtual** - Sesi 1-on-1 dengan instruktur profesional
- 🤖 **AI Trainer** - AI pelatih catur interaktif (Premium)
- 🛒 **Shopping Cart** - Sistem keranjang belanja terintegrasi
- 📖 **My Library** - Perpustakaan kursus yang sudah dibeli
- 💳 **Subscription** - Paket Basic dan Premium
- 📱 **Responsive** - UI ramah anak dan mobile-friendly

## 🚀 Quick Start

### 1. Setup Structure (IMPORTANT!)

**Read `SETUP_NOW.md` first!** Then run:

```bash
# Copy files to /src
# (See SETUP_NOW.md for detailed commands)

# Install dependencies
npm install

# Run dev server
npm run dev
```

### 2. Development

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000)

### 3. Build

```bash
npm run build
```

## 📁 Project Structure

```
lescatur/
├── src/                    # Source code
│   ├── components/        # React components
│   │   ├── ui/           # ShadCN components
│   │   ├── figma/        # Figma utilities
│   │   └── data/         # Data files
│   ├── utils/            # Utility functions
│   │   └── supabase/     # Supabase client
│   ├── styles/           # CSS files
│   ├── guidelines/       # Documentation
│   ├── App.tsx          # Main app component
│   └── main.tsx         # Entry point
├── index.html           # HTML entry
├── package.json         # Dependencies
├── vite.config.ts       # Vite config
└── tsconfig.json        # TypeScript config
```

## 💰 Pricing

- **Kursus Video**: Rp 100.000 - Rp 150.000
- **E-Book**: Rp 100.000 - Rp 110.000
- **Kelas Virtual**: Rp 100.000 - Rp 135.000 / sesi
- **Subscription Premium**: AI Trainer access

## 🔧 Tech Stack

- **Frontend**: React 18 + TypeScript
- **Styling**: Tailwind CSS v4
- **UI Components**: ShadCN/UI + Radix UI
- **Chess**: chess.js + react-chessboard
- **Backend**: Supabase (Client-side only)
- **Build Tool**: Vite

## 📦 Scripts

| Script | Description |
|--------|-------------|
| `npm run dev` | Start development server |
| `npm run build` | Build for production |
| `npm run preview` | Preview production build |

## 🎨 Features

### For Users
- Browse video courses and e-books
- Book 1-on-1 virtual chess classes
- Access AI trainer (with subscription)
- Track learning progress
- Manage purchased courses
- View upcoming sessions

### Technical Features
- Client-side Supabase integration
- Responsive design (mobile-first)
- Interactive chess board
- Progress tracking
- Shopping cart system
- User authentication

## 🌐 Responsive Design

3-stage adaptive layout:
- **Desktop** (>692px): Full text labels
- **Tablet** (421-692px): Short text labels
- **Mobile** (≤420px): Icon only

## 🔑 Environment Variables

Create `.env` file (optional):

```env
VITE_SUPABASE_URL=https://your-project.supabase.co
VITE_SUPABASE_ANON_KEY=your_anon_key_here
```

## 📝 Important Notes

1. **No Server-Side Functions** - This is a pure frontend app
2. **Supabase Client-Side Only** - No edge functions deployment
3. **No 403 Errors** - Structure optimized for Figma Make
4. **All Features Work** - Despite being frontend-only

## 🆘 Troubleshooting

### Error 403 when deploying?
➡️ **Read `SETUP_NOW.md`** - Complete fix guide

### Build fails?
```bash
# Check if files in /src
ls src/

# Reinstall dependencies
rm -rf node_modules
npm install
```

### CSS not loading?
```bash
# Check files exist
ls src/styles/globals.css
ls src/styles/MobileResponsive.css

# Check imports in src/App.tsx
```

## 📖 Documentation Files

- `SETUP_NOW.md` - **Fix Error 403 (READ THIS FIRST!)**
- `MOBILE_RESPONSIVE_GUIDE.md` - Responsive design guide
- `BACKEND_API_DOCUMENTATION.md` - API documentation
- `REAL_AUTH_IMPLEMENTATION.md` - Auth implementation
- `guidelines/Guidelines.md` - Project guidelines

## 🤝 Contributing

Contributions welcome! This is a learning project.

## 📞 Support

For issues:
1. Check `SETUP_NOW.md` for setup issues
2. Check browser console for errors
3. Verify file structure matches documentation

---

**LesCatur** - Belajar Catur Jadi Mudah! ♟️

**Version**: 1.0.0  
**Status**: Production Ready (after setup)  
**Last Updated**: 2024
