# Angular-WorkBook  

## Introduction

Angular is a powerful open-source web application framework maintained by Google. It's used for building dynamic and robust web, mobile, and desktop applications using HTML, CSS, and TypeScript.

This README serves as a quick reference guide for Angular, covering some essential concepts and features.

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
