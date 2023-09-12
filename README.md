# angular-interview
Interview Questions

1. How to optimize an Angular application to increase its performance?

There can be various methods by which we can increase the performance of an Angular application. They are:

Reducing the bundle size 
Lazy loading to load only the necessary code when required 
AOT Compilation to pre-compile templates and reduce the runtime overhead
Reactive programming to minimize unnecessary API calls and optimize data flow.

2. What are Angular guards?

Guards are a feature in Angular that allows users to manage and control the application's routing. Angular Guards can protect routes, 
control access to certain routes based on user authentication, and perform pre-navigation checks or modifications.

3.Differentiate between AOT and JIT in Angular?

AOT stands for Ahead of Time.
JIT stands for Just in Time.
It is a process where Angular templates and components are compiled during the building phase.
It is a process where Angular templates and components are compiled in the browser at the time of execution.
AOT compiles the templates into efficient JavaScript code that can be executed directly by the web browser without the need for further compilation at runtime.
JIT compilation generates the JavaScript code for templates as the application runs, which leads to a small delay during application startup.
JIT and AOT are both two ways used to compile code in an Angular project. JIT compiler is used in development mode while AOT is used for production mode.

4.Explain transpiling in Angular?

In Angular, transpiling refers to the process of converting the TypeScript code into JavaScript code that can be understood and executed by web browsers or other JavaScript runtime environments.
 Transpiling in Angular occurs internally as a part of the build process.
 
 5. How can you improve the size of Angular bundles?
 
Code minification: reducing the size of the code by removing unnecessary parts.
Tree shaking: to remove unused code from the bundles
Lazy loading: loading components and modules on-demand
Optimizing dependencies, etc.

6. What is the difference between Observables and Promises in Angular?

Promise Observable
It emits a single value. It emits multiple values over a period of time.
Not Lazy Lazy. An observable is not called until we subscribe to the observable.
We can not cancel
it. We can cancel it by using the unsubscribe() method.
Observable provides operators like map, forEach, filter, reduce, retry, retryWhen etc.
