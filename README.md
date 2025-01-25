# JS-Code



var name = "Nureen"
console.log(name);


//string concatenation
var message = "Hello "+name;
console.log(message)


//ES6 - Interpolation
console.log(`My name is ${name}`);




var age = 13;
var weight = 80.3;

var a = 10;
var b = 3;
console.log(a+b);
console.log(a-b);
console.log(a*b);
console.log(a/b);
console.log(a%b);
console.log(a**b);


var hungry = true;
var tired = false;
console.log(hungry && tired);
console.log(hungry || tired);
console.log(!hungry);


var scores = [30,50,70,90,80];
console.log(scores[0]);
console.log(scores[2]);
scores.push(90);
scores.pop();
scores.pop();
console.log(scores);
console.log(scores.length);
scores.splice(2,1);
console.log(scores);

var info = {"name":"Nureen Khaironi","Location":"Bukit Jalil","profession":"Operation"};

console.log(info.name);
console.log(info["location"]);
console.log`My name is ${info["name"]} I am ${info["age"]+7} years old, my weigth is ${Math.round(weight)} kg`;
