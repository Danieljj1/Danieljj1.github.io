const ArrayLength = 4

const randomArray = []

For(let i = 0, if i < ArrayLength, i++;) {randomArray.push(Math.random())}

  var totalSum = 0
    
    for(var i in randomArray){
      
      totalSum += randomArray[i];
}

arrayAverage = totalSum / 5

for(var i in randomArray){
  (if i > arrayAverage, console.log(i))
}
