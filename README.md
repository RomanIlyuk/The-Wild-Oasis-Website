# The Wild Oasis Website 🏕️

A modern full-stack booking application where users can explore luxury cabins, authenticate with Google, reserve cabins, manage reservations, and experience a clean premium UI inspired by modern hotel booking platforms.

---

# 🌄 Live Demo

## Vercel Deployment

https://the-wild-oasis-website-demo-pink-omega.vercel.app/

---

# 🌄 Preview

The project presents a calm and premium landing page experience focused on nature, luxury, and simplicity.

Main technologies used in this project:

- React
- Next.js App Router
- Server Components
- Server Actions
- Supabase
- Authentication
- Tailwind CSS
- Date handling
- Dynamic routing
- Optimistic UI updates
- Modern React patterns

---

# 🚀 Features

## Authentication

- Google Authentication
- Protected routes
- Session handling
- Guest area access
- Secure login flow

## Cabin Booking System

- Browse all cabins
- View detailed cabin information
- Filter cabins by capacity
- Dynamic booking system
- Date selection
- Reservation management
- Edit and delete reservations

## Guest Dashboard

- Manage profile information
- Update guest data
- View booking history
- Reservation tracking

## Modern UI/UX

- Responsive design
- Smooth layout structure
- Large cinematic hero section
- Clean typography
- Interactive states
- Reusable UI components
- Elegant dark theme

## Performance & Architecture

- Server Components
- Streaming
- Partial rendering
- Route caching
- Data fetching optimization
- Server-side rendering
- Lazy loading
- Revalidation

---

# 🛠️ Tech Stack

## Front-End

- React
- Next.js 14+
- Tailwind CSS
- JavaScript

## Back-End / Services

- Supabase Database
- Supabase Authentication
- Server Actions
- REST API integration

## Additional Libraries

- date-fns
- react-day-picker
- next-auth / auth.js
  n- Heroicons

---

# 📚 Concepts Practiced In This Project

This project covers many advanced modern React and Next.js concepts.

## React Concepts

- Component architecture
- Reusable components
- Props composition
- State management
- Client Components
- Hooks
- Suspense
- Concurrent UI patterns

## Next.js Concepts

- App Router
- Nested layouts
- Dynamic routes
- Loading UI
- Error boundaries
- Metadata API
- Route groups
- Server Components
- Client Components
- Static & dynamic rendering
- Server Actions
- Caching & revalidation

## Full-Stack Concepts

- Authentication flow
- Authorization
- Database interaction
- Secure server communication
- CRUD operations
- Form handling
- Async data fetching

---

# 📂 Project Structure

```bash
.
├── app/
│   ├── _components/
│   ├── _lib/
│   ├── _styles/
│   ├── about/
│   ├── account/
│   ├── api/
│   ├── cabins/
│   ├── fonts/
│   ├── login/
│   ├── error.js
│   ├── icon.png
│   ├── layout.js
│   ├── loading.js
│   ├── not-found.js
│   └── page.js

```

---

# 🎨 Design System

## Typography

The project uses large cinematic typography with strong spacing hierarchy.

### Recommended Fonts

#### Headings

```css
font-family: "Josefin Sans", sans-serif;
```

#### Body Text

```css
font-family: "Inter", sans-serif;
```

---

## Color Palette

### Primary Colors

```js
colors: {
  primary: {
    50: '#E1E8EF',
    100: '#D4DEE7',
    200: '#B7C7D7',
    300: '#99B0C7',
    400: '#7C99B6',
    500: '#5E82A6',
    600: '#4C6B8A',
    700: '#3C546C',
    800: '#2C3D4F',
    900: '#1B2631',
    950: '#141C24',
  },
  accent: {
    50: '#FAF5F0',
    100: '#F4ECE1',
    200: '#E8D6BF',
    300: '#DDC2A2',
    400: '#D2AF84',
    500: '#C69963',
    600: '#B78343',
    700: '#926835',
    800: '#6C4D28',
    900: '#4B351B',
    950: '#382814',
  },
},
```

---

# ⚡ Installation

## 1. Clone repository

```bash
git clone https://github.com/RomanIlyuk/the-wild-oasis-website.git
```

## 2. Navigate to project folder

```bash
cd the-wild-oasis-website
```

## 3. Install dependencies

```bash
npm install
```

## 4. Create environment variables

Create a `.env.local` file:

```env
NEXTAUTH_URL=
NEXTAUTH_SECRET=
GOOGLE_CLIENT_ID=
GOOGLE_CLIENT_SECRET=
SUPABASE_URL=
SUPABASE_KEY=
```

## 5. Start development server

```bash
npm run dev
```

---

# 🔐 Authentication Flow

The authentication system is based on Google OAuth.

Process:

1. User clicks login button
2. Google OAuth window opens
3. User authenticates
4. Session gets created
5. Protected routes become accessible

---

# 🗄️ Database

Supabase is used as the main backend database.

Main tables:

- cabins
- bookings
- guests
- settings

Relationships:

- One guest → many bookings
- One cabin → many reservations

---

# 📅 Booking Logic

Core booking features:

- Prevent overlapping reservations
- Calculate number of nights
- Calculate total price
- Validate date ranges
- Update availability dynamically

---

# 📱 Responsive Design

The application is fully responsive and optimized for:

- Desktop
- Tablet
- Mobile devices

Main responsive techniques:

- CSS Grid
- Flexbox
- Tailwind breakpoints
- Fluid typography
- Responsive spacing

---

# 🧠 Important Learning Outcomes

After completing this project, the following skills are practiced:

- Real-world React architecture
- Modern Next.js development
- Full-stack application structure
- Authentication systems
- Database integration
- Server Actions
- Advanced routing
- Clean component structure
- Production-ready patterns

---

# 🚀 Future Improvements

Possible future enhancements:

- Payment integration
- Email notifications
- Admin dashboard
- Reviews & ratings
- Advanced search
- Wishlist system
- Dark/light theme switcher
- Internationalization (i18n)

---

# 🧑‍💻 Author

Developed as part of the learning journey toward becoming a professional Front-End Developer.

---

# 📄 License

This project is for educational purposes.

Inspired by modern full-stack React and Next.js application architecture.
