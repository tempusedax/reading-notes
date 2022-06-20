#Questions 
1. A new array with the result of whatever functional logic the user input.
2. You can attach the map() method to the array and pass a callback function that gets called for each iteration. When rendering the User component, pass a unique value to the key prop as an argument like we did for hornedbeasts.
3. Key.
4. Keys help React identify which items have changed, are added, or are removed.
5. The spread operator is syntax for adding items to arrays, combining arrays or objects, and spreading an array out into a function’s arguments.
6. It can copy an array, add to state, combining objects and using other math functions.
7. Example from the website 
   [...["😋😛😜🤪😝"]] // Array [ "😋😛😜🤪😝" ]
   [..."🙂🙃😉😊😇🥰😍🤩!"] // Array(9) [ "🙂", "🙃", "😉", "😊", "😇", "🥰", "😍", "🤩", "!" ]

  const hello = {hello: "😋😛😜🤪😝"}
  const world = {world: "🙂🙃😉😊😇🥰😍🤩!"}

  const helloWorld = {...hello,...world}
  console.log(helloWorld) // Object { hello: "😋😛😜🤪😝", world: "🙂🙃😉😊😇🥰😍🤩!" }
  
8.const fewFruit = ['🍏','🍊','🍌']
  const fewMoreFruit = ['🍉', '🍍', ...fewFruit]
  console.log(fewMoreFruit) //  Array(5) [ "🍉", "🍍", "🍏", "🍊", "🍌" ]
9.const objectOne = {hello: "🤪"}
  const objectTwo = {world: "🐻"}
  const objectThree = {...objectOne, ...objectTwo, laugh: "😂"}
  console.log(objectThree) // Object { hello: "🤪", world: "🐻", laugh: "😂" }
  const objectFour = {...objectOne, ...objectTwo, laugh: () => {console.log("😂".repeat(5))}}
  objectFour.laugh() // 😂😂😂😂😂
