### `Installed npm packages`
- prop-types: for using types with props, this is not TypeScript
- react-fontawesome: FontAwesome for React
- styled-components: for styled components
- @reach-router: for routing when we go to different pages, another alternative is react-router

### `Another dependencies`

Other things in the src folder were provided with the course
    this zip which containts all are available in my DropBox -> Learn -> react folder

### `Movie db API`

link: themoviedb.org/documentation/api

### `About React`

1. JSX is syntactic sugar for React.createElement
2. JSX can selfclose
    <div /> instead of <div> </div>
3. User defined components should start with a capital letter
    so if we have a Header component it won't be confused with header
        -> <Header></Header> vs <header></header>, the first is our component, the second is built-in
4. You can use JavaScript expressions inside of JSX
    <div>{ 5 + 5}</div> 
        -> in the div, it will be 10
5. You can nest components just like in html
6. Nested content can be accessed in props.children
