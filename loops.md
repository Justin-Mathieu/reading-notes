








# **Loops and operators**
>*Loops let us do some thing repeatedly.*
 
## **Types of loops**
>### **For loop**
>*a for loop reapeats until a specified condition ewvaluates to be false, to do this evaluates the expressions in the loop*
**Example**
```function displayrating() {
let output='';
let rating =  prompt('how many stars? 1-5')
for(let i = 0;i <rating; i++){
    output = output +"<img class=star src='Images/R.jpg'>"
}
return document.write(output);`  

### **Do while loop**
>* in this loop you are guaranteed tone execution before the loop evaluates the conditions and repeats.*
**Example**
```function guessnumber(){

let answer;
do {
    answer = prompt('Guess a number between 1-10');
    if(answer != 7){
    alert('try again');}
    
    else{
        alert('you are correct');}
}
    while(answer !=7 );
}```


### **While loop**
>*A while loop executes as long as the condition is true.*
**Example**
```let n = 0;
let x = 0;
while (n < 3) {
  n++;
  x += n;
}```




