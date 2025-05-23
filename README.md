## TrendReel-SPA
It is a gateway to trending cinema reviews and you can share your opinion!

## SPA_Project
SPA_Project is a Single Page Application (SPA) built with Angular. It includes features like user authentication, movie listings, and a star rating system. The project is modular, scalable, and designed for maintainability.

## Features

- *Authentication*: Login and logout functionality using AuthService.
- *Header Component*: A reusable header for navigation.
- *Home Component*: Displays trending, theater, and popular movies.
- *Star Rating Component*: A custom component for displaying star ratings.
- *Environment Configuration*: Separate configurations for development and production.
- *Modular Architecture*: Well-structured code for scalability and maintainability.

## Project Structure
```
SPA_Project/
 ├── src/
│ ├── app/
│ │ ├── header/
│ │ │ ├── header.component.ts
│ │ │ ├── header.component.html
│ │ │ ├── header.component.scss
│ │ ├── home/
│ │ │ ├── home.component.ts
│ │ │ ├── home.component.html
│ │ │ ├── home.component.scss
│ │ ├── login/
│ │ │ ├── login.component.ts
│ │ │ ├── login.component.html
│ │ │ ├── login.component.scss
│ │ ├── movie/
│ │ │ ├── movie.component.ts
│ │ │ ├── movie.component.html
│ │ │ ├── movie.component.scss
│ │ ├── feature/
│ │ │ ├── feature.module.ts
│ │ │ ├── star-rating/
│ │ │ │ ├── star-rating.component.ts
│ │ │ │ ├── star-rating.component.html
│ │ │ │ ├── star-rating.component.css
│ │ ├── services/
│ │ │ ├── auth.service.ts
│ │ │ ├── auth.service.spec.ts
│ │ ├── app.module.ts
│ │ ├── app.component.ts
│ │ ├── app.component.html
│ │ ├── app.component.scss
│ ├── environments/
│ │ ├── environment.ts
│ │ ├── environment.prod.ts
│ ├── main.ts
│ ├── index.html
│ ├── styles.scss
├── angular.json
├── package.json
├── tsconfig.json
├── README.md

```
---

## Installation & Setup

### Prerequisites
- Install [Node.js](https://nodejs.org/) (v16 or higher recommended).
- Install Angular CLI globally:
  ```sh
  npm install -g @angular/cli
  ```

## Steps
1.Clone the repository:
```sh
git clone <repository-url>
cd SPA_Project
```
2.Install dependencies:
```sh
npm install
```
3.Set up environment files:
src/environments/environment.ts:
```sh
export const environment = {
  production: false,
  apiUrl: 'http://localhost:3000/api'
};
```
environment.prod.ts:
```sh
export const environment = {
  production: true,
  apiUrl: 'https://api.example.com'
};
```

## Usage
1.Start the development server:
```sh
ng serve
```
2.Open your browser and navigate to:
```sh
http://localhost:4200
```
3.Use the following credentials to log in:
```sh
Username: Sonali
Password: sonali@1
```

## Testing
To execute unit tests and validate functionalities, run:
```sh
ng test
```
## Build for Production
To build the application for production, run:
```sh
ng build --prod
```

## Contributing
Contributions are welcome! If you'd like to contribute:  
1. Fork the repository.  
2. Create a feature branch (git checkout -b feature-branch).  
3. Commit your changes (git commit -m "Add new feature").  
4. Push to the branch (git push origin feature-branch).  
5. Open a Pull Request.  

For major changes, please open an issue first to discuss your proposal.
