<h1>React Responsive navbar with props</h1>



<h4>react-nscoder-navbar is a React component to build a simple and responsive navbar with hamburger menu to mobile screens</h4>



## Installation

<h5>Use the npm package manager to install react-nscoder-navbar</h5>

</br>



```bash
npm install react-nscoder-navbar  --save
```

</br>



  <img src="https://media.giphy.com/media/PmN6BuVy5VIUzA8zJ0/giphy.gif" heigt="500" width="500" />
  
  
  <p>
  Responsive navbar with props.</br>
  Simple and light npm package.</br>
  Technologies use: react,  react-hooks, CSS.</br>
  Don't waste your time building your own navbar, just simple downloaded with npm.</br>
  Required: Node.js, NPM, React.</br>
  I hope you liked and feel happy to enjoy and download.
  

  </p>
  </br>
  
  div>
  Navbar default position is fixed top </br>
  Z-index is 10 </br>

   
    <!-- position: fixed;
    top: 0%;
    left: 0%;
    width: 100%;
    height: 6vmin; -->

  </div>
  </br>
  
  
  
  
  ## Usage

```javascript
import React from 'react';


//Import SideBar from react-nscoder-navbar
import SideBar from 'react-nscoder-navbar'

//Import Css File in Your Component from node_modules/react-nscoder-navbar/App.css. 
// Be aware of your path,it depends where you're component is.

import '../node_modules/react-nscoder-navbar/App.css'






function App() {
  return (
    <div>
  
  
<SideBar
   
  
  //Change Background Color
   
   bgColor="#0D5DCD"


   //Change Logo name
    logo="LOGO"


   //Change Logo Color
    logoColor='white'


  //Change Text color of nav items
   textColor='white'


  //Change Text color of nav items on hover
   textColorHover="#FFA500"
   

  //Change Bar color 
   barsColor="red"
   
 
 //Change Menu items name Minimum-3 items, Max-6 items. Minimum 3 for responsiveness.
 //Opitmal is too have 4-6 item names for responsiveness.
   menuItems={["Mission","About","Health","Contact","App","Family"]}

//Change Menu items Links. Number of names must be exact number of links. 3 Names == 3 links. 
   menuItemsLinks={["home","about","skills","health","app","contact"]}

    />


    </div>
  )
}

export default App




```






</br>

<img align="left" alt="GitHub" width="26px" src="https://raw.githubusercontent.com/github/explore/78df643247d429f6cc873026c0622819ad797942/topics/github/github.png" />https://github.com/goranivankovic/react-nscoder-navbar

</br>
<img  align="left" alt="GitHub" width="26px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/npm/npm.png" alt="npm" />https://www.npmjs.com/package/react-nscoder-navbar



<hr></hr>

</br>
## License

[MIT](https://choosealicense.com/licenses/mit/)


</br>
</br>

##
[developed](https://github.com/goranivankovic)





