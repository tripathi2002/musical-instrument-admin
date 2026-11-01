# Musical Instrument Store – Admin

Angular admin dashboard for the musical instrument e-commerce store. It connects to the store API to manage catalog data (products, categories, brands, images) and view customers and orders, behind an authenticated login.

## Features

- Login, signup and forgot-password pages, with a route guard for logged-in users
- Dashboard with navbar and sidebar layout
- Add / list products, categories and brands
- Product image upload (`product/upload/:id`)
- Customer list and orders view

## Tech stack

Angular 15 · TypeScript · RxJS · Angular Material · Bootstrap / ng-bootstrap

## Project structure

```
src/app/api.ts               # API base URLs
src/app/authentication/      # login, signup, forgot-password
src/app/catalog/             # products, categories, brands, customers, orders, image upload
src/app/main-layout/         # dashboard, navbar, sidebar
src/app/models/              # auth, brand, cart, category, coupon, customer, order, product
src/app/services/            # API services + logged.guard
```

## Getting started

```bash
npm install
npm start          # http://localhost:4200
npm run build
```

Requires the store API running at `http://127.0.0.1:1000/api` (see `src/app/api.ts`), for example [ecommerse-api](https://github.com/tripathi2002/ecommerse-api).

## Environment variables

None. API URLs are set in `src/app/api.ts`.
## Screenshots

_Screenshots coming soon._

## License

No license file has been added to this repository yet.
