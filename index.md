## About the Author

Existence for around 9 years in the tech world. Last seen on github **OCT 21st 2021 @11.51.16AM with 2 Contributions**.


## You can find me :point_down:

[Twitter](https://twitter.com/godfernThirteen)  [:earth_asia:](http://godfreyfernandes.com/)  [Instagram](https://www.instagram.com/godfern13/)


## Let's get started...

1. **Nullish Coalescing**
  Nullish coalescing adds the ability to truly check nullish values instead of falsey values.
  Differernt falsey values are _empty strings, the number 0, undefined, null, false, NaN_
  Inorder to check explicitly undefined and null values we can us **??**
  
  ###Example
 
  ```markdown
    //Nullish Coalescing ??
    console.log(false ?? "Flipkart Wholesale")
    console.log(false || "Flipkart Wholesale")

    console.log(undefined ?? "Flipkart Wholesale")
    console.log(undefined || "Flipkart Wholesale")

    console.log(null ?? "Flipkart Wholesale")
    console.log(null || "Flipkart Wholesale")

    console.log(0 ?? "Flipkart Wholesale")
    console.log(null || "Flipkart Wholesale") 
  ```
  
 [JS Fiddle](https://jsfiddle.net/godfern13/jw38poan/8/) 
 
 
 2. **Optional Chaining**
  Optional chaining syntax allows you to access deeply nested object properties without worrying if the property exists or not. 
  If it exists, great! If not, undefined will be returned. **?.**
  
  ###Example
 
  ```markdown
    //Optional Chaining
    let developers = {
      frontend:{
        javascript: "Yes",
        react: "Yes",
        java: "No",
        node:"Yes",
        otherActivities:[
          "Sleeps","Eats","Smokes","Drinks","Party"
        ]
      },
      backend:{
        javascript: "No",
        react: "No",
        java: "Yes"
      }
    }

    console.log(developers.frontend.java);
    console.log(developers.backend.otherActivities?.[0]); 
  ```
  
 [JS Fiddle](https://jsfiddle.net/godfern13/j2q5hy7z/7/) 
 
 
 3. **new Map**
  The Map object holds key-value pairs and remembers the original insertion order of the keys. **new Map()**
  
  ###Example
 
  ```markdown
    //new Map()
    var map = new Map([[ 1, 'Bitcoin' ],[ 2, 'Ethereum' ], [ 3, 'Ripple' ],[ 4, 'Litecoin' ]]);


    map.set(1, "Tron");
    map.delete(2); 
    console.log(map.size); //map size
    console.log(map.get(1)) 


    for (const [key, value] of map) {
      console.log(key, value);
    } 
  ```
  
 [JS Fiddle](https://jsfiddle.net/godfern13/yzfvdq7b/18/) 
 
 
 4. **new Set**
  A Set is a special type of object in ES6 that lets you create a collection of unique values. **new Set()**
  
  ###Example
 
  ```markdown
    //new Set()
    const birds = new Set();
    // add items
    birds.add('🐦');
    birds.add('🦉');
    birds.add('🦆');
    birds.add('🦅');
    // check if item exists
    birds.has('🦉'); // true
    birds.has('🐥'); // false
    // get items count
    birds.size; // 4
    // delete item
    birds.delete('🦆'); // true
    birds.delete('🦆'); // false - already deleted
    // delete all items
    birds.clear();
  ```
  
 [JS Fiddle](https://jsfiddle.net/godfern13/qLx7npfa/9/)
 
 
 5. **Array.fill()**
  Using the Array.fill method is an obvious choice — you supply the method with the value you want to populate your array with, and the method returns a modified   version of the array. **Array.fill()**
  
  ###Example
 
  ```markdown
    let filledArray = new Array(10).fill('hello');
    console.log(filledArray)
  ```
  
 [JS Fiddle](https://jsfiddle.net/godfern13/qLx7npfa/9/) 
 
 
 
