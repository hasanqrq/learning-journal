# comparasion operators 
## evaulating contitions

when comparing two valuse the answer will be true or false 
the singn == comares two valuse even if they are numbers or strings so 100 == '100'
but the === is a strict method it will return 100 === '100' to *false*

and we ha != which mean not equal like 100 != '100' will return false but the strict method !== will retrun 100!=='100' *true*.

### We have also the greater than > and less than < as a comparasion operators.

# logical operators

## The logical operators allow you to compare the results of more than one comparion operator.
### *((5<2) && (2>=3))*
### we have && for and , || for or and ! for Not .

## the loop check a condition if return true  a code will run and will check again until the condition become false , it will stop and break the loop

### We have *For* and we use it if we know the times of repeatition and we have *while* if we don not know how many times will the code be executed , and we have *DO WHILE* the same as *while* but it will run the statement at least one even if the condition *false.

for example :
for (var i =0; i<10; i++){
    document.write(i);
}

## Here is an example of awhile loop. It writes out the 5 times table. Each time the loop is run, another calculation is written into the variable called msg.

## This loop will continue to run for as long as the condition in the parentheses is true. That condition is a counter indicating that, as long as the variable i remains less than 10, the statements in the subsequent code block should run.

var i = l ;
var msg = ' ' ;
II Set counter to 1
II Message
II Store 5 times tabl e in a variable
while (i < 10) {
msg += i + ' x 5 = ' + (i * 5) + '<br I>';
i++;
document .getEl ementByid( ' answer') . innerHTML = msg;


## In this example, the condition specifies that the code should run nine times. A more typical use of awhi le loop would be when you do not know how many times you want the code to run. It should continue to run as long as a condition is met.