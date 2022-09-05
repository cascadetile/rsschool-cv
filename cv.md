## Temirlan Aryngazy

### Contacts

Email: collent.credev@gmail.com, but prefer Telegram: @il_buono and rs-school Discord: Temirlan (@cascadetile) 

### About me

Junior Developer on Halyk Bank since 2021. Love to optimize things, not always succesfull

### Skills

* JavaScript (npm, Vue)
* Golang (Echo, Fiber, Gin)
* Git
* IDE: VSCode for frontend, GoLand for backend
* HTML 
* CSS (BEM, SCSS)

### Code examples

All repositories of projects I worked on are private but I have [CodeWars profile](https://www.codewars.com/users/SeverBryan/completed_solutions)

Delete occurrences of an element if it occurs more than n times:

```
function deleteNth(arr,n){
  let hashMap = new Map();
  
  let resArr = [];
  
  for (let i = 0; i < arr.length; i++) {
    hashMap.set(arr[i], 0);
  }
  
  for (let i = 0; i < arr.length; i++) {

    if (hashMap.get(arr[i]) < n) {
      resArr.push(arr[i]);
      hashMap.set(arr[i], hashMap.get(arr[i]) + 1);
    }
    
  }
  
  return resArr;
}
```

### Work Experience

2020 - 2021 

Occasional landing freelance

2021 - currently

Halyk Bank Junior Developer

### Education

Courses
* [Programming in Golang](https://stepik.org/course/54403/promo)
* [Just JavaScript](https://justjavascript.com/)
* [Go: The Complete Developer's Guide (Golang)](https://www.udemy.com/course/go-the-complete-developers-guide)
* [JavaScript Algorithms and Data Structures](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/)

Books
* You Don't Know JS Yet
* Eloquent JavaScript
* Modern JavaScript for the Impatient
* JavaScript: The Definitive Guide (partly)


### English Level

CEFR B2.2
