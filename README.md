# Array
arrayManipulation using Java Script
let Arr=[1,2,2,3,4,5,5,6,5,8];
let outputArray=[];
let count=0;
let start=false;
for(let j=0;j<Arr.length;j++)
  {
    for(let k=0;k<outputArray.length;k++)
      {
        if(Arr[j]==outputArray[k])
        {
          start=true;
          
        }
      }
    count++;
    if(count==1 && start==false){
      outputArray.push(Arr[j]);
      
    }
    start=false;
    count=0;
  }
console.log(outputArray);
