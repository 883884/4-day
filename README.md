# 4-day

1.How compare The Json have the same properties without order?

    a.let obj1={ name:"person 1",age:5};
    b.let obj2={age:5, name:"person 1"};

  Const object 1={
        name:'person1',
          age:'5'
       };
 Const object 2={
        age:'5',
      name:'person1'
      };
   JSON.Stringify( object 1)===JSON.Stringfy(object 2)
   // false
   _is Equal ( object 1, object 2)
   // true

2.Use the countries API URL https://restcountries.com/v3.1/all
 and display all the country flags in the console

  Let a=https://restcountries.com/v3.1/all
    
   Const get = async()={

  Const data=await fetch(https://restcountries.com/v3.1/all)
  Const payload=await data.Json

 Console.log("========================");
 Console.log();
 Console.log("=========================");
     
         Let a=" ;
    for(let value of payload) {
        a+=
    <p>${value.name.common}</p>;
   };
   Document.querselector("div").innerHTML=a;
   };
   get();

3.use the same countries and print all countries names, versions, sub-region and populations
  

Let a=https://restcountries.com/v3.1/all
    
   Const get = async()={

  Const data=await fetch(https://restcountries.com/v3.1/all)
  Const payload=await data.Json

 Console.log("========================");
 Console.log();
 Console.log("=========================");
     
         Let a=" ;
    for(let value of payload) {
        a+=
    <p>${value.name.version.common}</p>;
   };
   Document.querselector("div").innerHTML=a;
   };
   get();

   
