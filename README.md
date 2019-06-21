# my-react-notes

##(4) Components and props
Components let you split the UI into independent reusable pieces and think about each 
piece in isolation. 

###(4.1) Function and class components 
The simplest component is a JS function : 
```javascript
function Welcome(props) {
  return <h1>Hello, {props.name}</h1>;
}
```

