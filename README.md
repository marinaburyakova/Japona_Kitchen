# Japona Kitchen - Premium Japanese Cuisine SPA

[![React](https://img.shields.io/badge/React-18.3-61dafb?logo=react)](https://reactjs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.0-3178c6?logo=typescript)](https://www.typescriptlang.org/)
[![Vite](https://img.shields.io/badge/Vite-5.0-646cff?logo=vite)](https://vitejs.dev/)
[![CSS Modules](https://img.shields.io/badge/CSS%20Modules-✓-blue)](https://github.com/css-modules/css-modules)

A premium, production-ready Single Page Application for **Japona Kitchen** — an exclusive Japanese cuisine restaurant. Built with modern React, TypeScript, and Vite, featuring elegant animations, a shopping cart with localStorage persistence, and a luxurious glassmorphism design.

![Japona Kitchen Preview](https://via.placeholder.com/800x400?text=Japona+Kitchen+Preview)

---

##  Features

###  Design & UX
- **Premium minimalist design** — elegant typography (Cormorant Garamond + Montserrat), generous whitespace
- **Glassmorphism effects** — frosted glass styling on hover with backdrop blur
- **Smooth scroll animations** — fade-in effects using Intersection Observer API
- **Responsive layout** — perfect from 350px mobile to 4K desktop (flexbox + CSS Grid)
- **Custom SVG logo** — authentic Japanese-inspired crest design

###  Shopping Cart
- **Add to cart** with beautiful toast notifications
- **Quantity controls** (+/-) and item removal
- **LocalStorage persistence** — cart survives page reload
- **Real-time total calculation** — optimized with `useMemo`
- **Drawer-style cart** — smooth slide-out panel with overlay

###  Search & Filter
- **Debounced search** — 300ms delay for optimal performance
- **Category filtering** — filter dishes by Signature, Sushi, Main, Dessert, Ramen, etc.
- **Mobile-adaptive filter** — compact dropdown on small screens
- **Real-time results count** — shows X of Y dishes
 Technical Excellence
- **TypeScript** — full type safety with strict mode
- **Custom hooks** — `useCart`, `useDebounce`, `useThrottle`, `useIntersectionObserver`
- **Memoization** — `React.memo`, `useMemo`, `useCallback` for optimal renders
- **Code splitting ready** — lazy loading components
- **Toast notification system** — beautiful animated alerts instead of `alert()`
- **Body scroll lock** — prevents scrolling when modal/cart is open


##  Tech Stack

| Technology | Purpose |
|------------|---------|
| **React 18** | UI library with functional components & hooks |
| **TypeScript** | Static type checking & better DX |
| **Vite** | Fast build tool & dev server |
| **CSS Modules** | Scoped, maintainable styles |
| **Intersection Observer** | Scroll-triggered animations |
| **LocalStorage API** | Persistent cart state |




