# Summary

## State in React

State is private data of a component. These data can only used inside of its component and can't be accessed by another components. The characteristics of State:

1. Modifiable data by using setState
2. Every time there is a modification, there will be a re-render
3. Asynchronous
4. Used in Class component

## Statefull VS Stateless

Statefull component is the Class component that have state. The advantages of Class component is it has lifecycle.

Stateless component is the component that have not state. Generally, stateless components are created using Function because the code is more concise.

Below is the differrences between stateless component with statefull component:

| Stateless Component               | Statefull Component                   |
| --------------------------------- | ------------------------------------- |
| Don't know about the app          | Know about the app                    |
| Data not fetching                 | Fetching data                         |
| The main purpose is visualization | Interaction with the app              |
| Reusable                          | Not reusable                          |
| Only communicate with the parent  | Forward status and data to the childs |

## Event Handling in React

Event handling is a method for handling an event that received from the user to the component. Besides that, event is an incident triggered by the useron a component, for example button pressed. The example of list Event:

1. Clipboard Events (promise fulfilled)
2. Form Events (onChange, onSubmit)
3. Mouse Events (onClick, onDoubleClick, onMouseOver)
4. Generic Events (onError, onLoad)

# Event Handling Practice

Build "To Do List" App with below criterias:

1. Allowed to add new action
2. There is checkbox for each action
3. Checklist the checkbox if action finished
4. Provide delete button to delete action
5. Give alert if the input is empty

<p align="center">
    Homepage:
    <br><br>
    <img src="./screenshots/homepage.png" alt="homepage" width="1000"/>
</p>
<p align="center">
    After Adding New Action:
    <br><br>
    <img src="./screenshots/afterAddToDo.png" alt="afterAddToDo" width="1000"/>
</p>
<p align="center">
    When Input Is Empty:
    <br><br>
    <img src="./screenshots/inputIsEmpty.png" alt="inputIsEmpty" width="1000"/>
</p>
