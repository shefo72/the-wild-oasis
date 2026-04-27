# The Wild Oasis 🏨

A full-featured property management application built with React and Vite. Manage cabins, bookings, guests, and user accounts with an intuitive dashboard and real-time analytics.

---

## ✨ Features

- **Dashboard Analytics:** Real-time sales charts, duration tracking, and key daily statistics.
- **Cabin Management:** Full CRUD operations for cabin listings, including image uploads and pricing adjustments.
- **Booking System:** Manage guest bookings, track statuses, and handle check-ins/check-outs efficiently.
- **Authentication & Security:** Secure login, account management, and profile updates powered by Supabase.
- **Modern UI/UX:** Responsive design, real-time toast notifications, and seamless form validation.
- **Data Management** - Guest management and system-wide settings configuration

---

## 🛠️ Tech Stack

| Category       | Technology                    | Purpose                                 |
| -------------- | ----------------------------- | --------------------------------------- |
| **Frontend**   | React 19 & Vite 7             | UI creation and fast development builds |
| **UI & UX**    | React Icons & React Hot Toast | Handle UI and user experience           |
| **Routing**    | React Router 7                | Client-side navigation                  |
| **State/Data** | React Query 5                 | Server state management and caching     |
| **Backend**    | Supabase                      | PostgreSQL database and authentication  |
| **Styling**    | Styled Components             | CSS-in-JS component styling             |
| **Forms**      | React Hook Form               | Performant form validation              |

**Development Tools:**

- ESLint - Code quality and style enforcement
- TanStack React Query DevTools 5.99 - Developer tools

---

## 📁 Project Structure

```
src/
├── data
├── features/
│   ├── authentication
│   ├── bookings
│   ├── cabins
│   ├── check-in-out
│   ├── dashboard
│   └── settings
├── hooks/
├── pages/
├── services/
├── ui/
└── utils/
```

---

## 🚀 Getting Started

1. **Clone the repository**

   ```bash
   git clone https://github.com/shefo72/the-wild-oasis.git
   cd the-wild-oasis
   ```

2. **Install dependencies**

   ```bash
   npm install
   ```

3. **Environment Setup**
   Create a .env.local file with your Supabase credentials:

   ```
   VITE_SUPABASE_URL=your_supabase_url
   VITE_SUPABASE_ANON_KEY=your_supabase_anon_key
   ```

4. **Start the development server**
   ```bash
   npm run dev
   ```
   The application will open at `http://localhost:5173`

---

Built with ❤️ using modern React tools and best practices.
