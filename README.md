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