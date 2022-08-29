
## CSS Text Typing Animation

Awesome Multiple Text Typing Animation using HTML & CSS
## Description
 In this animation, there is a total of four texts and each text slide and appear with a typing animation.


## Credits

- [@CodingNepal](https://www.codingnepalweb.com/text-typing-animation-using-only-html-css/)
## Authors

- [@Nayetowlf](https://github.com/Nayetwolf)


## Usage/Examples
If you want to erase back the typed text then remove the last @keyframes codes and add this 
```javascript
@keyframes typing {
  40%, 60%{
    left: calc(100% + 30px);
  }
  100%{
    left: 0;
  }
}

// And also you have to change the time duration of the animations
// Line. 36 - Replace this line with this: 
animation: slide 12s steps(4) infinite;

// Line. 56 - Replace this line with this:
animation: typing 3s steps(10) infinite;

