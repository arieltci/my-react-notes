# my-react-notes

## (4) Components and props
Components let you split the UI into independent reusable pieces and think about each 
piece in isolation. 

### (4.1) Function and class components 
A function component that accepts props: 

```javascript
function Welcome(props) {
  return <h1>Hello, {props.name}</h1>;
}
```
can also use ES6 class: 
```javascript
class Welcome extends React.Component {
  render() {
    return <h1>Hello, {this.props.name}</h1>;
  }
}
```

## (5) State and lifecycle



