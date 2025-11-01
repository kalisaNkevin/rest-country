# REST Countries

Interact with countries REST api using HTTP Client, and manage state with Ngrx.

Live URL: [link](some url)

## 📌 Table of Contents

- [🚀 Getting Started](#-getting-started)
- [🛠️ Tech Stack](#-tech-stack)
- [📦 Installing](#-installing)
- [💻 Running the Application](#-running-the-application)
- [🚀 Deployment](#-deployment)
- [👤 Author](#-author)

## 🚀 Getting Started

This project is built using Angular, SCSS, Typescript and hosted on Netlify.

## 🛠️ Tech Stack

- Angular
- RxJS
- Jasmine & Karma(test runner)
- Typescript
- SCSS

## 📦 Installing

Clone the repository and run the command:

```sh
git clone https://github.com/kalisankevin/rest-countries
cd rest-countries
```


**Component Structure**

- Next, I created services for:

1. Abstracting HTTP into an `ApiClientService`
2. Creating an error handler service `ErrorHandlerService`
3. Defining a data service for country to call api endpoints via the `ApiClientService`

**Component Details**

- Implement selecting a single country from Ngrx store
- Modify API_URL to add extra params like cca3 to get country codes, borders etc
- Add method for fetching a single country from the api url by code
- Render country details in the details page

**Implement theme**
- Add theme toggle functionality by storing theme state in ngrx store


## 👤 Author

Kalisa Ngabo Kevin
