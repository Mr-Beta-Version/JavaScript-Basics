# JavaScript-Basics

# Variable Define
```
let name = "Walid";
const age = 99;

let use for define a variable for later use, that long script code can catch error that name variable can't use another time. only value can updated.

const use for permanent value it cannot be modify or changes anything.
```
# Template Literals
```
let name = 'Walid';
let stringMixData = `Hello ${name} .\nYou know 1+1 = ${1+1}`;
console.log(stringMixData);

```

# Type Check
```
typeof variablename;
```

# length check
```
variablename.length;
```
# Strings methods
```
let name = "    Md WAlid       ";
console.log(name.toUpperCase());
console.log(name.toLowerCase());
console.log(name.trim());
```
cuting
```
let phone = "+88013xxxxxxxx";
let countryCode = phone.slice(0,4);
console.log(countryCode); // +880
```
join
```
let first = "Muhammad";
let last = "Walid";
let name = first.concat(last);
console.log(name); // MuhammadWalid
// ALT WAY
console.log(first+last);
```
Get Char
```
let name = "Walid";
let charStart = name.charAt(0);
console.log(charStart); // W
// ALT WAY
console.log(name[0]); // W
```

replace
```
let name = "Muhammad Walid";
let shortName = name.replace("Muhammad","MD");
console.log(shortName); // MD Walid
```

# Comments
```
// this is single line comment

/* This is
Multiline Comments */
```

# Condition 
If Only
```
if(a===b) {
console.log("A and B equal");
}
```
If Else
```
if(a===b) {
console.log("A and B equal");
}else{
console.log("A not equal B");
}
```

If , else If ,else
```
if(a===b) {
console.log("A and B equal");
}else if(a===c) {
console.log("A and C equal");
}else{
console.log("No Equal Match");
}
```

Ternary Operator
```
condition ? true_output:false_output;
```

```
let age=29;
let voter = age>17 ? "yes voter":"no child";
console.log("Output",voter);

```

Pop-up message and Input
```
alert("Hello this is a Message");
let name = prompt("Hey Enter Your Name");
console.log("Welcome",name);
```





# Loop 

for loop
```
for(var, condition for execute,changes after execute){
    body

}
```
```
for(let i=1;i<=5;i++){
    console.log("Hello World");
}
```

While Loop
```
let i=1;
while(i<=10){
    console.log(i," While Loop");
    i++;
}
```

Do While Loop
```
let j=1;
do{
    console.log(j," Print First Check Condition Later")
    j++;
}while(j<=10)
```

for of loop
```
let word = "Walid";
for(let char of word){
    console.log(char);
}
```

for in loop
```
let data = {
    name : "Walid",
    age : 56,
    phone : "+8801457866999"
}

for(let key in data){
    console.log(key); // its return name, age, phone
    console.log(data[key]); // its return the value
}
```

Arrays and Arrays Loop
```
let boy_name = ["Walid","Navid","Rafat","Siam"];
for(let i=0;boy_name.length>i;i++){
    console.log(boy_name[i]);
}
```

