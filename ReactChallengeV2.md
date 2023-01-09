# React Challenge

## Purpose and objective

Skills Workflow, as an organization, must make sure we hire resources that are not only knowledgeable but resourceful as well.
Here we propose a challenge to candidates for positions that involve the advanced use of React.

The main goal of this challenge is to assess the candidate's knowledge of the React framework, it's main concepts, idioms, project structure, etc. as well as to 
assess how the candidate can think out of the box and use React in unusual or non trivial ways.

## Scope

* To address this challenge candidates must use React version 18 or later if available (latest version is preferred). 
* Usage of the latest React API such as functional components and hooks is required.
* Use Typescript and all it's advantages: strong typing, type inference, etc. Latest version is preferred
* Make use of Redux to centralize the application state. 
* Familiarity with key Redux terms and concepts like "actions", "reducers", "store", and "dispatching" is recommended.
* Any doubts or assumptions regarding the challenge must be documented to be discussed later
* Unit tests are not mandatory, but are highly desirable

## The challenge
 
The challenge consists of producing a React App or library that contains a new component named `WorkspaceComponent`.

**Example**
```html
<WorkspaceComponent component="{theWorkspaceJSON}" />
```

This component's purpose is to render forms/controls dynamically at runtime. 

Structure to be rendered should be defined in JSON and should be able to handle 3 kinds of controls:
* text input
* selection combo-box
* list - a list of text or selection controls

The JSON definition should support multiple levels:
	- Should have a root element - can be of any of the 3 control types 
	- a collection of child elements, when it makes sense - the list control ia a collection of controls

In order for this to be reusable/scalable, application must support state persistence.

It is up to the candidate to design and implement this feature as well as design the required configuration JSON format.

### Output
The result of this challenge should be:
1. React application that uses the new component/library and serves as proof of concept
2. The React library for the WorkspaceComponent if it was created as a separate module

**Important**

> Projects should be made available on a github repository so we can evaluate.
>
> Don't forget to include eventual design decisions or assumptions on the repo README file.
