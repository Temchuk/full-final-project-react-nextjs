# Movie App

Movie App - це веб-додаток для перегляду інформації про фільми, пошуку фільмів за назвою, перегляду жанрів та інших функцій. Додаток побудований з використанням Next.js, React, та використовує API [The Movie Database (TMDb)](https://www.themoviedb.org/) для отримання даних про фільми.

## Учасники

Над цим проектом працювала Олена Темчук.

## Особливості

- Перегляд списку фільмів з підтримкою пагінації.
- Пошук фільмів за назвою.
- Перегляд фільмів за жанрами.
- Перегляд детальної інформації про кожен фільм.
- Темна та світла теми з можливістю перемикання.
- Адаптивний дизайн для різних розмірів екранів.
- Авторизація користувачів з можливістю реєстрації.

## Технології

- **Next.js** - фреймворк для React, що підтримує рендеринг на сервері та статичну генерацію.
- **React** - бібліотека для побудови користувацьких інтерфейсів.
- **Redux** - керування станом додатку.
- **TypeScript** - мова програмування, що розширює JavaScript, додаючи типізацію.
- **CSS Modules** - для стилізації компонентів.

## Вимоги

- Node.js версії 14 або вище
- NPM (Node Package Manager) або Yarn

## Встановлення та Використання

1. Склонуйте репозиторій на свій комп'ютер.
2. Відкрийте файл full-project.html у вашому веб-браузері, щоб переглянути сайт.
3. Веб-сайт є адаптивним і адаптованим для версій планшета та мобільного телефону.
4.Для запуску проекту в режимі розробки виконайте команду: npm run dev

##Структура проекту
/src - головна папка з кодом додатку.
/components - містить компоненти додатку.
/pages - сторінки Next.js.
/services - містить API-сервіси для отримання даних.
/store - Redux store та slices.

public/ - містить усі зображення, використовувані в проекті.
src/components/ - компоненти React, такі як HeaderComponent, FooterComponent і т.д.
src/ - сторінки додатку для різних маршрутів (Home, Movies, Genres, Contacts, Login).
src/services/ - файли для взаємодії з API.
src/store/ - Redux store і slice для управління станом.
next.config.js - конфігурація Next.js.
README.md - документація проекту.
Ця структура організована і відповідає типовій структурі проекту на Next.js.


├── README.md
├── next.config.js
├── package.json
├── public/
│   ├── Telephone.png
│   ├── gmail loogo.png
│   ├── Twitter.png
│   ├── Facebook.png
│   ├── Instagram.png
│   ├── Linkdin.png
│   └── logo.jpg
├── src/
│   ├── app/
│   │   ├── contacts/
│   │   │   ├── page.tsx
│   │   │   └── Contacts.module.css
│   │   ├── favicon.ico
│   │   ├── page.module.css
│   │   ├── layout.tsx
│   │   ├── global.css
│   │   ├── page.tsx
│   │   ├── (client)/moives/
│   │   │   ├── [id]/
│   │   │   │   ├── page.tsx
│   │   │   │   └── MoviePageID.module.css
│   │   │   ├── Pagination.module.css
│   │   │   ├── Movie.module.css
│   │   │   └── page.tsx
│   │   ├── (client)/genres/s
│   │   │   ├── Genres.module.cs
│   │   │   └── page.tsx
│   │   ├── login/
│   │   │   ├── LoginPage.module.css
│   │   │   └── page.tsx
│   │   ├── contacts/
│   │   │   ├── Contacts.module.css
│   │   │   └── page.tsx
│   │   ├── search/
│   │   │   └── page.tsx
│   ├── components/
│   │   ├── ClientProviders.tsx
│   │   ├── ThemeProvider.tsx
│   │   ├── HeaderComponent.tsx
│   │   ├── FooterComponent.module.css
│   │   ├── FooterComponent.tsx
│   │   ├── StarRating.module.css
│   │   ├── StarRating.tsx
│   │   └── HeaderComponent.module.css
│   ├── services/
│   │   └── api.service.ts
│   ├── store/
│   │   ├── store.ts
│   │   └── themeSlice.ts
└── tsconfig.json





# Movie App

Movie App is a web application for viewing information about movies, searching for movies by title, viewing genres and other features. The app is built using Next.js, React, and uses [The Movie Database (TMDb)](https://www.themoviedb.org/) API to retrieve movie data.

## Participants

Olena Temchuk worked on this project.

## Features

- Browsing a list of movies with pagination support.
- Search movies by title.
- View movies by genre.
- View detailed information about each movie.
- Switchable dark and light themes.
- Responsive design for different screen sizes.
- User authorization with the possibility of registration.

## Technologies

- **Next.js** - a framework for React that supports rendering on the server and static generation.
- **React** - a library for building user interfaces.
- **Redux** - application state management.
- **TypeScript** - a programming language that extends JavaScript by adding typing.
- **CSS Modules** - for styling components.

## Requirements

- Node.js version 14 or higher
- NPM (Node Package Manager) or Yarn

## Installation and Use

1. Clone the repository to your computer.
2. Open the full-project.html file in your web browser to view the site.
3. The website is responsive and adapted for tablet and mobile phone versions.
4. To start the project in development mode, execute the command: npm run dev

##Project structure
/src - the main folder with the application code.
/components - contains application components.
/pages - Next.js pages.
/services - contains API services for receiving data.
/store - Redux store and slices.

public/ - contains all images used in the project.
src/components/ - React components such as HeaderComponent, FooterComponent, etc.
src/ - application pages for various routes (Home, Movies, Genres, Contacts, Login).
src/services/ - files for interacting with the API.
src/store/ - Redux store and slice for state management.
next.config.js - Next.js configuration.
README.md - project documentation.
This structure is organized and follows the typical Next.js project structure.
