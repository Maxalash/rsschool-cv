# Makhmut Zhantleuov
<img src="./PhotoSquare.jpg" width="150" alt = "My profile">

----
Mobile number: +7 778 7209234  
Email: makhmut.zhantleuov@gmail.com  
Date of birth: 18.11.2002  
Nationality: Kazakhstani  
[LinkedIn](https://www.linkedin.com/in/mahmoud-man-a5088a1b5/)  

----
**About me:**  
I'm an avid computer science student with a year and a half of experience in front-end development. I am interested in web development as there are many career opportunities in this field. Moreover, there are free quality resources for learning and self-education, as well as various developer communities.  
I believe that my ability to acquire new knowledge and skills will lead me to a skilled front-end developer.

## Education   
**BACHELOR DEGREE IN COMPUTER SCIENCE** - Astana IT Univerity  
 - 01/09/2020 - CURRENT - Business-center EXPO, C1, Nur-Sultan, Kazakhstan 

## Digital Skills
 - HTML5, CSS3
 - Javascript Basics
 - Git, GitHub
 - VSCode
 - REST API

## Code example:
**Moves in squared strings (I):** You are given a string of n lines, each substring being n characters long.  
**Task:**
 - Write vertical mirror function ``vertMirror(string)`` function
 - Write horizonral mirror function ``horMirror(string)`` function

 - Write high-order function ``oper(fct, s)`` where:

   - fct is the function of one variable f to apply to the string s (fct will be one of vertMirror, horMirror)  
   
 Code:  
```javascript
function vertMirror(strng) {  
    const matx = strng.split("\n")    
    var len_ = matx.length  

    for (let i = 0; i<len_; i++){  
      var temp = matx[i].split("")  
      matx[i] = temp.reverse().join("")  
    }  
    return matx.join("\n")  

}  
function horMirror(strng) {  
    const matx = strng.split("\n")  
    return matx.reverse().join("\n")  
}  
function oper(fct, s) {  
    if (fct == vertMirror){  
      return vertMirror(s)  
    }else if(fct==horMirror){  
      return horMirror(s)  
    }  
}
```

## Languages
 - Kazakh
 - Russian
 - English



