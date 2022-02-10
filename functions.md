[Home](README.md)
[*Growth Mindset*](GrowthMindset.md)  
[*Coder's computer*](codersComputer.md)    
[*Git*](GitNotes.md)  
[*Html*](HtmlStructures.md)  
[*CSS*](cssnotes.md)  
[*Javascript*](javascriptnotes.md)  
[*Functions*](functions.md)  
[*loops*](loops.md)   

# **Functions in Javascript**  
>*Functions ae building block in java script they allow us to call upon and reuse blocks of code.*  

## **Function declaration**  
>*A function is declared by usingthe name of the function, parmeters of the  fuction(if any),nad ther statements that are performed in the function.*  
### Example    

```
function ageguess() {
    let guess = prompt('Guess how old Duke is!');

    let message1;

    if (guess <= 10) {

        message1 = 'Too low!';
    }

    else if (guess > 11) {

        message1 = 'Too high';
    }

    else if (guess == 11) {

        message1 = 'you got it!';
    }

    return message1;

}
```

## **Invoking a function**  
>*Invokinmg the function runs that block of code  in the place it was invoked. To invoke a function parentheses are used.* 
## **Example**
```
<script>document.write(ageguess())</script>
```
