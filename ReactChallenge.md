# React Challenge

## Purpose and objective

Skills Workflow, as an organization, must make sure we hire resources that are not only knowledgeable but resourceful as well.
Here we propose a challenge to candidates for positions that involve the advanced use of React.

The main goal of this challenge is to assess the candidate's knowledge of the React framework, it's main concepts, idioms, project structure, etc. as well as to 
assess how the candidate can think out of the box and use React in unusual or non trivial ways.

## Scope

* To address this challenge candidates must use React version 18 or later if available (latest version is preferred)
* Any doubts or assumptions regarding the challenge must be documented to be discussed later
* Assume that you are a React developer producing a reusable module / library for other developers to use on their own applications
* Unit tests are not mandatory, but are highly desirable

## The challenge
 
The challenge consists of producing a reusable React component or library that contains a new component named `dynamic-form`.
When a developer includes this module or library on their application they should be able to use it on their html templates.

**Example**
```html
<dynamic-form definition="{formJSON}" />
```

This component's purpose is to render forms dynamically at runtime. 

These forms should be defined in JSON and should be able to handle 3 kinds of controls:
* text input
* selection combo-box
* list

Of course, in order for this to be useful it should be possible to define bindings for each control on the dynamic form.

It is up to the candidate to design and implement this feature as well as design the required configuration JSON format.

### Output
The result of this challenge should be:
1. React project for the `dynamic-form` component/library
2. Recat application that uses the new component/library and serves as proof of concept 

**Important**

> Both projects should be made available on a github repository so we can evaluate.
>
> Don't forget to include eventual design decisions or assumptions on the repo README file.
