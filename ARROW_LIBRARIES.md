# 🧰 Tech Stack & Packages

A breakdown of the libraries and tools I use across my React frontend and Node.js backend projects.

---

## ⚛️ Frontend — React Projects

### Project 1: Alas Web *(Online Ordering System)*

**Core**
- `react` · `react-dom`
- `react-router-dom`
- `vite`

**UI & Styling**
- `tailwindcss` · `@tailwindcss/vite` · `tailwind-merge` · `clsx` · `class-variance-authority`
- `flowbite-react` · `radix-ui` · `@radix-ui/*` (dialog, dropdown-menu, popover, select, separator, slot, switch, tabs)
- `lucide-react` · `react-icons`
- `framer-motion` · `lottie-react` · `react-confetti` · `react-fast-marquee`
- `sonner` · `vaul` · `cmdk`
- `react-aria-components` · `@internationalized/date`

**Forms & Validation**
- `react-hook-form` · `@hookform/resolvers` · `yup`

**Data & State**
- `@tanstack/react-query` · `@tanstack/react-query-devtools`
- `@tanstack/react-table`
- `zustand`
- `axios`

**Charts & Maps**
- `apexcharts` · `react-apexcharts`
- `leaflet` · `react-leaflet`

**Utilities**
- `date-fns` · `dayjs` · `lodash`
- `socket.io-client`
- `@react-pdf/renderer`
- `dotenv`

**Dev Tools**
- `eslint` · `eslint-plugin-react` · `eslint-plugin-react-hooks` · `eslint-plugin-react-refresh` · `eslint-plugin-jsx-a11y` · `@eslint/js`
- `prettier` · `prettier-plugin-tailwindcss`
- `vite-plugin-compression` · `source-map-explorer`
- `@vitejs/plugin-react` · `tw-animate-css`
- `@types/node` · `@types/react` · `@types/react-dom` · `globals`

---

### Project 2: OJT Development *(NEA Service Requests)*

**Core**
- `react` · `react-dom`
- `react-router-dom`
- `vite`

**UI & Styling**
- `tailwindcss` · `@tailwindcss/vite` · `daisyui` · `clsx`
- `lucide-react` · `react-icons`
- `framer-motion` · `@tippyjs/react`
- `react-hot-toast` · `react-image-magnify-lib`

**Forms & Validation**
- `react-hook-form` · `@hookform/resolvers` · `zod`

**Data & State**
- `zustand`
- `@supabase/supabase-js`

**Charts**
- `chart.js` · `react-chartjs-2`

**Utilities**
- `date-fns` · `lodash.debounce`
- `xlsx`

**Dev Tools**
- `eslint` · `eslint-plugin-react-hooks` · `eslint-plugin-react-refresh` · `@eslint/js`
- `prettier` · `prettier-plugin-tailwindcss`
- `autoprefixer` · `postcss`
- `@vitejs/plugin-react` · `globals`
- `@types/react` · `@types/react-dom`

---

## 🟢 Backend — Node.js API

**Core**
- `express`
- `nodemon` · `express-async-handler`

**Database**
- `knex` · `mysql2`
- `mongoose`
- `sql-template-strings`

**Authentication & Security**
- `bcrypt` · `jsonwebtoken`
- `helmet` · `cors` · `cookie` · `cookie-parser`
- `express-rate-limit` · `joi`

**File & Media**
- `multer` · `multer-storage-cloudinary` · `cloudinary`

**Real-time & Caching**
- `socket.io`
- `apicache` · `node-cache`

**Utilities**
- `axios` · `node-fetch` · `dotenv` · `dayjs`
- `node-cron`
- `nodemailer`
- `pdfmake`
- `compression`

**Logging**
- `winston` · `@axiomhq/winston`

**Dev Tools**
- `eslint` · `eslint-plugin-n` · `eslint-plugin-security` · `@eslint/js`
- `knip` · `globals`

---

## 📦 Full Package List (Quick Reference)

### Frontend
`@hookform/resolvers` · `@internationalized/date` · `@radix-ui/react-dialog` · `@radix-ui/react-dropdown-menu` · `@radix-ui/react-popover` · `@radix-ui/react-select` · `@radix-ui/react-separator` · `@radix-ui/react-slot` · `@radix-ui/react-switch` · `@radix-ui/react-tabs` · `@react-pdf/renderer` · `@supabase/supabase-js` · `@tailwindcss/vite` · `@tanstack/react-query` · `@tanstack/react-query-devtools` · `@tanstack/react-table` · `@tippyjs/react` · `apexcharts` · `axios` · `chart.js` · `class-variance-authority` · `clsx` · `cmdk` · `daisyui` · `date-fns` · `dayjs` · `dotenv` · `flowbite-react` · `framer-motion` · `leaflet` · `lodash` · `lodash.debounce` · `lottie-react` · `lucide-react` · `radix-ui` · `react` · `react-apexcharts` · `react-aria-components` · `react-chartjs-2` · `react-confetti` · `react-day-picker` · `react-dom` · `react-fast-marquee` · `react-hook-form` · `react-hot-toast` · `react-icons` · `react-image-magnify-lib` · `react-leaflet` · `react-router-dom` · `socket.io-client` · `sonner` · `tailwind-merge` · `tailwindcss` · `vaul` · `xlsx` · `yup` · `zod` · `zustand`

### Backend
`@axiomhq/winston` · `apicache` · `axios` · `bcrypt` · `cloudinary` · `compression` · `cookie` · `cookie-parser` · `cors` · `dayjs` · `dotenv` · `express` · `express-async-handler` · `express-rate-limit` · `helmet` · `joi` · `jsonwebtoken` · `knex` · `mongoose` · `multer` · `multer-storage-cloudinary` · `mysql2` · `node-cache` · `node-cron` · `node-fetch` · `nodemailer` · `pdfmake` · `socket.io` · `sql-template-strings` · `winston`

### Dev Dependencies
`@eslint/js` · `@types/node` · `@types/react` · `@types/react-dom` · `@vitejs/plugin-react` · `autoprefixer` · `eslint` · `eslint-plugin-jsx-a11y` · `eslint-plugin-n` · `eslint-plugin-react` · `eslint-plugin-react-hooks` · `eslint-plugin-react-refresh` · `eslint-plugin-security` · `globals` · `knip` · `nodemon` · `postcss` · `prettier` · `prettier-plugin-tailwindcss` · `source-map-explorer` · `tw-animate-css` · `vite` · `vite-plugin-compression`
