//let age = prompt('Your age');
//alert('Your age - ' + age);

/*
let animals = ["cat", "dog", "my class",];

animals.push("racoon"); //добавить в конец массива
animals.unshift("houre"); //добавить в начало массива
animals.pop(); //удаляет последнией элемент в массиве
animals.shift(); //удаляет первый элемент в массиве

alert(animals.indexof("cat"));
alert(animals);
*/

let food = ["candy", "banana"];
let q1 = prompt('Your food');
food.push(q1);
alert(food);
let q2 = prompt("Your food or delete one food (in start or in end)")
if (q2 == "delete in start"){
  food.shift()
} else if (q2 == "delete in end"){
  food.pop()
}else{
  food.push(q2)
}
alert(food);
let q3 = prompt("Which element to remove (by index)?");
delete food[q3];
alert(food);
