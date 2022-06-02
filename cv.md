# Nastassia Fralova
### Civil engeneer

Phone: +375444693214\
E-mail: nastya.frolowa1994@yandex.ru

## About
I am a graduate of the Belarusian National Technical University with a degree in civil engineering. In the course of my work, I use various programs for calculating concrete and metal structures, often working with numbers and formulas. Sometimes there are no programs for such calculations, and I thought about writing my own programs. So I decided to try myself in programming, to learn something new for myself.\
I like to solve logical problems and I want to apply this in writing code. I always try to perform the tasks set for myself responsibly, on time and efficiently. I will spend a lot of time and effort for this to succeed. 

I studied German at school, so I am studying English in parallel with RS. Now my English level is A1+, every day I train my level in Duolingo, watch movies in English with subtitles and independently study with a textbook.


## Skills and Proficiency
* HTML5, CSS
* JavaScript Basics
* VS Code
* Adobe Photoshop


## Code example
Coding in function findSimilarity. Function accept two parameters: str, a sentence contains some words, separated by spaces; word, a sample word.
Task is to keep the words that are similar to the sample word, and to remove the other words.
The similarity is defined as: the same length as the sample; the letter at the beginning and the end of word are same as the sample too.
If there are no similar words in the sentence, should return an empty string.

```
function findSimilarity(str,word){
  var regstr=word[0]                             //first letter
          +word.slice(1,-1).replace(/./g,".")  //middle letters
          +word.slice(-1);                     //last letter
  var reg1=new RegExp("^"+regstr+"$");
  return str.split(/ /).filter(x=> x.match(reg1)).join(" ");
}
```

More examples from Codewars: https://www.codewars.com/users/Nastyafro/completed_solutions


## Courses
* RS School Course "JavaScript/Front-end. Stage 0" (in Progress)
* JavaScript manual on https://justjavascript.com/