# ProductlistApp

This project was generated using [Angular CLI](https://github.com/angular/angular-cli) version 19.2.1.

## Development server
Hey ! this is a demo product listing app, made to view products and view their details

Step to locally run it in your machine 

1. clone this repository to your local machine : `git clone <insert repo url>`

2. install angular cli (if not installed) : `npm install -g @angular/cli`

3. To start a local development server, run:

```bash
ng serve
```

Once the server is running, open your browser and navigate to `http://localhost:4200/`. The application will automatically reload whenever you modify any of the source files.

## Components and Data Handling
In Angular, components are the application's building pieces, with each encapsulating a section of the user interface and its associated activity.
In this project we have different components like
1. product-card
2. product-details
3. product-list
Each component has HTML, CSS, Typescript.
HTML: Defines the structure and layout.
CSS: Specifies the appearance.
TypeScript Class: Contains the logic and data bindings.

## Services
In Angular, services are employed to encapsulate reusable logic that can be shared among components.  They frequently manage data retrieval, business logic, or interactions with external APIs.  A ProductService may be implemented in the context of a product listing application to:

 1. Retrieve Product Data: Extract product information 
    from a database or API.
 2. Maintaining State: Maintaining the current 
    inventory of products or the specifics of a 
    selected product.
 3. Manage business logic: Execute operations such as 
    categorizing or filtering products.


## Routing
In Angular, routing enables the user to navigate between various views or components by utilizing the URL.  The Angular Router renders the corresponding view by interpreting the browser's URL.  The routing configuration for a product listing application may be as follows:
1. Routes Configuration: Define routes in the AppRoutingModule, mapping URL paths to components.
2. Router Outlet:  Use <router-outlet></router-outlet> in the main application template to serve as a placeholder for the routed components.
3. Navigation:  Implement navigation links using the RouterLink directive.
## Additional Information
For more information on using the Angular CLI, including detailed command references, visit the [Angular CLI Overview and Command Reference](https://angular.dev/tools/cli) page.
