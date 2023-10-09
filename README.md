<div align='center'>
  <img  src='https://github.com/Yosef-Eid/joscript/assets/117477110/2abd752c-6128-4b26-9e41-dc11ef3acadc'/>  
</div>

  <div>
    <h1 >joscript</h1> 
    <p>
      I have created and developed a new library called (joscript) that simplifies JavaScript code so that developing and building websites is easier than would be           possible with JavaScript alone
    </p>

```jsx
import { jo } from "../../joscript/joScript.js";



function App() {let load = window.onload = () => {

    return(
        jo('div', {class:'app ', id:'app' ,children:[

        jo('h1', {text:'Welcome to joscript', id:'x'},{height:'100px', color:'#383D45'}),
            jo('img', {src:'/src/App/joScript-logo.svg'})

        ]})
    )

};return load()}
export default App;
```
   

  </div>
  

