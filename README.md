# Angular-WorkBook  

## Introduction

Angular is a powerful open-source web application framework maintained by Google. It's used for building dynamic and robust web, mobile, and desktop applications using HTML, CSS, and TypeScript.  

## Table of Contents

1. [Observables](#observables)
2. [ngFor](#ngfor)
3. [ngIf](#ngif)
4. [OnInit Interface](#oninit-interface)
5. [Routing](#routing)
6. [Lazy Loading](#lazy-loading)
7. [Angular CLI](#angular-cli)
8. [Dependency Injection](#dependency-injection)
9. [Lifecycle Hooks](#lifecycle-hooks)
10. [Error Handling](#error-handling)
11. [Async Pipe](#async-pipe)
12. [Two-Way Data Binding](#two-way-data-binding)
13. [Angular Modules](#angular-modules)
14. [Angular Services](#angular-services)
15. [Angular Forms](#angular-forms)
16. [Angular Interceptors](#angular-interceptors)
17. [Angular Testing](#angular-testing)
18. [Angular Directives](#angular-directives)
19. [Angular Pipes](#angular-pipes)
20. [Angular ViewChild](#angular-viewchild)

## Observables

An Observable is a powerful tool in Angular used for handling asynchronous operations. It represents a stream of data that can be observed over time.

## ngFor

`ngFor` is a structural directive in Angular used for iterating over a collection, such as an array or an object, and rendering each item in the collection.

## ngIf

`ngIf` is a structural directive in Angular used for conditionally rendering elements based on the evaluation of an expression.

## OnInit Interface

The `OnInit` interface in Angular is used to define a lifecycle hook called `ngOnInit()`. It is invoked after Angular has initialized all data-bound properties of a directive or component.

## Routing

Routing in Angular refers to the process of navigating between different components or views based on the URL changes in the browser. It's used to build Single Page Applications (SPAs).

## Lazy Loading

Lazy loading is a technique used in Angular routing to load modules and their associated components asynchronously when they are requested by the user, instead of loading them all upfront.

## Angular CLI

Angular CLI (Command Line Interface) is a command-line tool provided by the Angular team for initializing, developing, scaffolding, and maintaining Angular applications.

## Dependency Injection

Dependency injection in Angular is a design pattern used for creating and managing dependencies between different parts of an application. It allows for better modularity, testability, and scalability.

## Lifecycle Hooks

Angular provides several lifecycle hooks that allow you to tap into key moments in the lifecycle of a component or directive. These hooks include `ngOnInit`, `ngOnChanges`, `ngOnDestroy`, and more.

## Error Handling

Errors in Observable streams in Angular can be handled using the `catchError` operator or by using the `subscribe()` method with separate error handling callbacks.

## Async Pipe

The async pipe in Angular is used to automatically subscribe to an Observable or Promise and unsubscribe when the component is destroyed. It also handles the unwrapping of the asynchronous data.

## Two-Way Data Binding

Two-way data binding in Angular is implemented using the `[(ngModel)]` directive, which binds the value of an input element to a property in the component class and updates both the view and the component class when either changes.

## Angular Modules
### What are Angular modules and why are they important?

Angular modules are containers for a cohesive block of code dedicated to an application domain, workflow, or closely related set of capabilities. They help organize an application into cohesive blocks of functionality. Modules consolidate components, directives, pipes, and services into functional sets; in doing so, they can be easily integrated with other Angular applications.

### How do you create a new Angular module?

To create a new Angular module, you use the `@NgModule` decorator. This decorator takes a metadata object where you define the module's characteristics such as imports, declarations, providers, and bootstrap components.

## Angular Services
### What is an Angular service and how is it different from a component?

An Angular service is a singleton object created once and shared throughout an application. It encapsulates functionality that does not belong to any specific component. Services are used for reusable logic, data sharing, and communication between components.

### How do you create and use a service in Angular?

To create a service in Angular, you use the `@Injectable()` decorator to provide metadata about the service. Then, you define the service class and its methods. To use the service, you inject it into the constructor of the components or other services that need it.

## Angular Forms
### What are Angular Reactive Forms?

Angular Reactive Forms provide a model-driven approach to handling form inputs. They're built around observable streams that represent the state of the form at any point in time. Reactive Forms offer advantages like immutability, scalability, and ease of testing.

### How do you implement form validation in Angular?

Form validation in Angular can be implemented using built-in validators like `required`, `minLength`, `maxLength`, etc., or by creating custom validators. Validators can be applied in the template using directives or programmatically in the component.

## Angular Interceptors
### What are Angular interceptors and what are they used for?

Angular interceptors are middleware logic that you can use to intercept incoming or outgoing HTTP requests and responses. They provide a way to modify requests or responses globally before they're handled by the application.

### How do you create and use an interceptor in Angular?

To create an interceptor in Angular, you implement the `HttpInterceptor` interface. Then, you define the intercept method to handle the interception logic. Interceptors are typically provided in the `providers` array of an Angular module.

## Angular Testing
### Why is testing important in Angular development?

Testing is crucial in Angular development to ensure that the application behaves as expected and remains stable as it evolves. It helps catch bugs early in the development process, ensures code quality, and provides confidence when making changes.

### What are the different types of tests in Angular?

In Angular, you can write different types of tests, including Unit Tests, which test individual components, services, or directives in isolation; Integration Tests, which test the interaction between components; and End-to-End (E2E) Tests, which simulate user interactions with the application.

## Angular Directives
### What are Angular directives and how are they used?

Angular directives are markers on a DOM element that tell Angular to attach a specified behavior to that DOM element or even to transform the DOM element and its children. Directives can be classified into three types: component directives, attribute directives, and structural directives.

### How do you create a custom directive in Angular?

To create a custom directive in Angular, you use the `@Directive` decorator. This decorator allows you to define the selector for the directive and specify its behavior through a directive class. You can then use this directive in your templates like any built-in directive.

## Angular Pipes
### What are Angular pipes and what is their purpose?

Angular pipes are a way to transform data directly within your templates, without having to write lengthy code in the component class. Pipes allow you to format data for display, convert data from one format to another, and perform other transformations.

### How do you use built-in pipes in Angular?

To use built-in pipes in Angular, you simply add the pipe name to the interpolation expression in your template, followed by a `|` symbol. For example, `{{ myDate | date }}` would format the `myDate` variable as a date according to the default date format.

## Angular ViewChild
### What is `@ViewChild` in Angular and how is it used?

`@ViewChild` is a decorator in Angular used to get the first element or the directive matching the selector from the view DOM. It allows a parent component to query its child component or directive and access its properties and methods.

### How do you use `@ViewChild` in Angular?

To use `@ViewChild` in Angular, you first import it from `@angular/core`. Then, you use it as a decorator on a property of your component class, specifying the selector of the child component or directive you want to query. Finally, you access the queried element using the property in your component class.
