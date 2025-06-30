# Getting Started
Install the dependencies and run the project
```
npm install
npm start
```

Head over to https://vitejs.dev/ to learn more about configuring vite
## About Scrimba

At Scrimba our goal is to create the best possible coding school at the cost of a gym membership! 💜
If we succeed with this, it will give anyone who wants to become a software developer a realistic shot at succeeding, regardless of where they live and the size of their wallets 🎉
The Frontend Developer Career Path aims to teach you everything you need to become a Junior Developer, or you could take a deep-dive with one of our advanced courses 🚀

- [Our courses](https://scrimba.com/allcourses)
- [The Frontend Career Path](https://scrimba.com/learn/frontend)
- [Become a Scrimba Pro member](https://scrimba.com/pricing)

Happy Coding!# TravelWebApp

# Travel Web App

Dieses Projekt dient als Übung in modernen React-Techniken und konzentriert sich auf:

- **React Router**: Implementierung von Routen und Navigation in einer Single-Page-Application.
- **React Hooks**: Zustand und Nebenwirkungen mit Hooks wie `useState`, `useEffect`, `useParams` und `useNavigate`.
- **Single-Page-Application**: Dynamisches Navigieren ohne Seitenreload für eine flüssige Nutzererfahrung.

## Gelernt

### React Router
- Definition von Routen mit `<Routes>` und `<Route>`.
- Navigation per `<Link>` und programmatisch mit `useNavigate()`.
- Zugriff auf URL-Parameter mit `useParams()`.
- Implementierung geschützter Routen (Protected Routes).

### React Hooks
- **useState**: Lokaler Komponenten-Zustand.
- **useEffect**: Auslösen von Nebenwirkungen (z. B. Daten-Fetch).
- **useParams**: Auslesen von Routendaten.
- **useNavigate**: Programmatische Navigation.
- Erstellen eigener Hooks zur Wiederverwendbarkeit.

## Projektstruktur

```
/src
├── components/   # Wiederverwendbare UI-Komponenten
├── pages/        # Seiten, jeweils als Route
├── hooks/        # Eigene React-Hooks
└── App.jsx       # Hauptkomponente mit Routen-Setup
```

## Installation & Start

```bash
npm install
npm start
```

## Ausblick

- Anbindung eines Backends (z. B. REST oder GraphQL).
- Erweiterung um State-Management (Context API, Redux).
- Einbindung von Tests (Jest, React Testing Library).