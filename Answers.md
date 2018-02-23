# Your responses to the short answer questions should be laid out here using Mark Down.
### For help with markdown syntax [Go here](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
1. Describe some of the differences between .forEach & .map.
    - forEach allows you to loop through an array one 
    - map allows you to loop through an array and create a copy of that arr

2. Name five different Types in JavaScript. A Type is something that can represent data. What is so special about    Arrays?
    - string, boolean, number, undefined, obl
    - arrays are special types of objects that store ordered collections

3. What is closure? Can you code out a quick example of a closure?
    - closures are environments in which functions can live
    - ex: const animal = 'cat' (global)
            function sayHiAnimal(){
                console.log('hello I'm a cat');
            }
            sayHiAnimal();

4. Describe the four rules of the 'this' keyword. No need to provide examples about it this time.
        - window/global binding, implicit binding, explicit binding, new binding 
        