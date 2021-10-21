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
 
