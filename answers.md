
## Introductions

1. I am SENDHIL KUMAR S  with 3+ year of experience as a Front end developer. With the expertise in react Js and flutter using (HTML, CSS, Javascript),I like building mobile application for android and Ios using flutter. Along with windows application and web application using ReactJs and Flutter.
2. Yes, I have my own Pc with good internet connection, 
   RAM - 8.00 GB, 
3. Yes, I would like to share my linkedin Portfolio - www.linkedin.com/in/sendhil-kumar-3b986a195 
4. No
5.  1.Dart,Javascript,Typescript,C,C++ 
    2. Windows
    3. Visual Studio Code
6. Front-end Developer    
7. Yes, Interested in ML
8. Currently Leaning  c# 

   

//First Program

const  givenData = 'The quick brown fox jumped over the lazy dog'
function longValue(value) {
  const  splitData = value.split(' ');
  var  newData = ''; 

  for (var i = 0; i < splitData.length; i++) {
    if (splitData[i].length > newData.length) {
      newData = splitData[i]; 
    }
  }
  return newData;
}
console.log(longValue(givenData));



// Second Program
const inputValue='abc'
let repeatedString = "";

function repeatedValue(string, times) {
  while (times > 0) {
    repeatedString += string;
    times--;
  }
  return repeatedString;
}
console.log(repeatedValue(inputValue, 3))



//Third Program 

const givenNumberArray = [1, 20, 3, 1, 3, 3]
function removeDuplicate(value) {
  return value.filter((item,
      index) => value.indexOf(item) === index);
}
console.log(removeDuplicate(givenNumberArray));

//Fourth Program 

const givenArray = [42, "everything", "", 2, false, "everything"];
const outputValue = givenArray.filter(Boolean);
console.log(outputValue);


//Fifth Program

const givenString = "Absolute victory";
function truncate(value, i) {
  if (value.length <= i) {
    return value
  }
  
  return value.slice(0, i) + '...'
}

console.log(truncate( givenString,3));