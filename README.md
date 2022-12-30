#   Introduction of Map In scss

##  What is Scss ?

      in map we can declear multiple global variables fro bunch of css properties.  can call global variable by use of 
<code>map.get($globalVarName, "newColor")</code>
      
## How can we enable map in scss ??
> 1. add @use <code>"sass:map";</code in you scss file

> 2. create Global var like

<code>
  backgrounds:(   
      "bg-blue" : blue,
      "bg-green" : green,
      "bg-black" : black,
      "bg-white" : white
  );
</code

> 3. use your global variables by using maping

<code>
      background-color: map.get($backgrounds, "bg-black");
</code>

[For more exploration watch your scss series on youtube](https://www.youtube.com/@programmingashram/)
