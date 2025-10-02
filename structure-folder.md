src/
├── app/                          # App configuration & providers
│   ├── providers/               # Context providers, Redux store
│   │   ├── ReduxProvider.tsx
│   │   ├── ThemeProvider.tsx
│   │   └── index.ts
│   ├── store/                   # Redux store configuration
│   │   ├── index.ts
│   │   ├── rootReducer.ts
│   │   └── middleware.ts
│   └── App.tsx
│
├── shared/                      # Shared utilities & components
│   ├── components/             # Reusable UI components
│   │   ├── ui/                # shadcn/ui components
│   │   │   ├── button.tsx
│   │   │   ├── input.tsx
│   │   │   ├── card.tsx
│   │   │   └── index.ts
│   │   ├── forms/             # Form components
│   │   │   ├── FormField.tsx
│   │   │   ├── FormWrapper.tsx
│   │   │   └── index.ts
│   │   ├── layout/            # Layout components
│   │   │   ├── Header.tsx
│   │   │   ├── Sidebar.tsx
│   │   │   ├── Footer.tsx
│   │   │   └── index.ts
│   │   └── feedback/          # Loading, Error, Success components
│   │       ├── Loading.tsx
│   │       ├── ErrorBoundary.tsx
│   │       └── index.ts
│   ├── hooks/                 # Custom hooks
│   │   ├── useLocalStorage.ts
│   │   ├── useDebounce.ts
│   │   └── index.ts
│   ├── utils/                 # Utility functions
│   │   ├── cn.ts             # className utility
│   │   ├── formatters.ts
│   │   ├── validators.ts
│   │   └── index.ts
│   ├── constants/            # App constants
│   │   ├── routes.ts
│   │   ├── api.ts
│   │   └── index.ts
│   └── types/               # TypeScript type definitions
│       ├── api.ts
│       ├── user.ts
│       └── index.ts
│
├── features/                # Feature-based modules
│   ├── auth/               # Authentication module
│   │   ├── components/    # Auth-specific components
│   │   │   ├── LoginForm.tsx
│   │   │   ├── SignupForm.tsx
│   │   │   └── index.ts
│   │   ├── hooks/        # Auth hooks
│   │   │   ├── useAuth.ts
│   │   │   └── index.ts
│   │   ├── services/     # Auth API calls
│   │   │   ├── authApi.ts
│   │   │   └── index.ts
│   │   ├── store/        # Auth Redux slice
│   │   │   ├── authSlice.ts
│   │   │   ├── authSelectors.ts
│   │   │   └── index.ts
│   │   ├── types/        # Auth types
│   │   │   └── index.ts
│   │   └── index.ts      # Feature exports
│   │
│   ├── dashboard/          # Dashboard module
│   │   ├── components/
│   │   │   ├── DashboardStats.tsx
│   │   │   ├── RecentActivity.tsx
│   │   │   └── index.ts
│   │   ├── hooks/
│   │   ├── services/
│   │   ├── store/
│   │   ├── types/
│   │   └── index.ts
│   │
│   ├── products/           # Products module
│   │   ├── components/
│   │   │   ├── ProductCard.tsx
│   │   │   ├── ProductList.tsx
│   │   │   ├── ProductForm.tsx
│   │   │   └── index.ts
│   │   ├── hooks/
│   │   ├── services/
│   │   ├── store/
│   │   ├── types/
│   │   └── index.ts
│   │
│   └── users/              # Users module
│       ├── components/
│       ├── hooks/
│       ├── services/
│       ├── store/
│       ├── types/
│       └── index.ts
│
├── pages/                  # Page components (routing)
│   ├── HomePage.tsx
│   ├── LoginPage.tsx
│   ├── DashboardPage.tsx
│   ├── ProductsPage.tsx
│   └── index.ts
│
├── assets/                 # Static assets
│   ├── images/
│   ├── icons/
│   └── fonts/
│
├── styles/                 # Global styles
│   ├── globals.css        # Global CSS + shadcn/ui
│   ├── components.css     # Component-specific styles
│   └── utilities.css      # Utility classes
│
├── main.tsx               # App entry point
└── vite-env.d.ts         # Vite types