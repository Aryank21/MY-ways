function sumArray(array) {
  var sum = 0;

  array.forEach(item => {
    sum += item;
  });

  console.log(sum);
  return sum;
}

var sum=sumArray([1, 4, 0, 9, 5]);

for(var i=1;i<=sum;i++)
    {
        if(i%3==0)
        {
            console.log("buzz ");
        }
        else if(i%4==0)
        {
            console.log("fizz ");
            
        }

        else if(i%3==0 && i%4==0)
        {
            console.log("fizz BUZZ");
        }
        else(
            console.log(i)
        )
    }
