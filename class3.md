#Questions 
1. A new array with the result of whatever functional logic the user input.
2. You can attach the map() method to the array and pass a callback function that gets called for each iteration. When rendering the User component, pass a unique value to the key prop as an argument like we did for hornedbeasts.
3. Key.
4. Keys help React identify which items have changed, are added, or are removed.
5. The spread operator is syntax for adding items to arrays, combining arrays or objects, and spreading an array out into a functionβs arguments.
6. It can copy an array, add to state, combining objects and using other math functions.
7. Example from the website 
   [...["ππππ€ͺπ"]] // Array [ "ππππ€ͺπ" ]
   [..."ππππππ₯°ππ€©!"] // Array(9) [ "π", "π", "π", "π", "π", "π₯°", "π", "π€©", "!" ]

  const hello = {hello: "ππππ€ͺπ"}
  const world = {world: "ππππππ₯°ππ€©!"}

  const helloWorld = {...hello,...world}
  console.log(helloWorld) // Object { hello: "ππππ€ͺπ", world: "ππππππ₯°ππ€©!" }
  
8.const fewFruit = ['π','π','π']
  const fewMoreFruit = ['π', 'π', ...fewFruit]
  console.log(fewMoreFruit) //  Array(5) [ "π", "π", "π", "π", "π" ]
9.const objectOne = {hello: "π€ͺ"}
  const objectTwo = {world: "π»"}
  const objectThree = {...objectOne, ...objectTwo, laugh: "π"}
  console.log(objectThree) // Object { hello: "π€ͺ", world: "π»", laugh: "π" }
  const objectFour = {...objectOne, ...objectTwo, laugh: () => {console.log("π".repeat(5))}}
  objectFour.laugh() // πππππ
