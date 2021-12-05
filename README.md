<!DOCTYPE html>
<html lang="en">
    <head> 
        <meta charset="UTF-8">
         <meta http-equiv="X-UA-Compatible" content="IE=edge">
          <meta name="viewport" content="width=device-width, initial-scale=1.0"> 
          <title>Document</title>
        </head>
        <body> 
            <h1 style="text-align: center;">Too see the answer use CONSOLE</h1>
</body>
<script>
  let calc={ 
    Num1:0, 
    Num2:0,
     result:0,
    'sum': function(a ,b){
    this. Num1=a;
     this.Num2=b;
    this. result=this.Num1+this.Num2;
    return this.result;
 },
    'mul': function(c,d){ 
        this.Num1=c; 
        this.Num2=d;
         this.result=this.Num1*this.Num2; 
         return this.result; 
        },
    'div': function(x,y){ 
        this.Num1=x;
         this.Num2=y;
          this.result=this.Num1 / this.Num2;
           return this.result; 
        },
    'mod': function(p,q){
         this.Num1=p;
          this.Num2=q; 
          this.result=this.Num1 % this.Num2; 
          return this.result; 
        },
    'dif': function(i,j){ 
        this.Num1=i;
         this.Num2=j; 
         this.result=this.Num1-this.Num2;
          return this.result;
        },
    };
    document.write("SUM FUNCTION");
    console.log("SUM FUNCTION");
    document.write(calc.sum( 30,2 ));
    console.log(calc.sum( 30,2 ));
    document.write("<br>");
    document.write("MULTIPLY FUNCTION");
    console.log("MULTIPLY FUNCTION");
    document.write(calc.mul( 8,9 ));
    console.log(calc.mul( 8,9 ));
    document.write("<br>");
    document.write("MODULE FUNCTION");
    console.log("MODULE FUNCTION");
    document.write(calc.dif( 1,3 ));
    console.log(calc.dif( 1,3 ));
    document.write("<br>");
    document.write("SUBTRACTION FUNCTION");
    console.log("SUBTRACTION FUNCTION");
    document.write(calc.dif( 27,13 ));
    console.log(calc.dif( 27,13 ));
    document.write("<br>");
     document.write("DIVISION FUNCTION");
    console.log("DIVISION FUNCTION");
    document.write(calc.div( 12,6 ));
    console.log(calc.div( 12,6 ));
    document.write("<br>");
  </script>
  </html>
