/**scala-addition-in-eclipse
* created by priyatham
**//


object addition {                         //defined object
  def main(args: Array[String]) {         //the method define by main with arguments having no return value that is unit
    println("Enter the 2  numbers :")
    val a=scala.io.StdIn.readDouble()     // reading the input value a
    println("The value of a is: "+ a)
    val b=scala.io.StdIn.readDouble()     // reading the input value b
    println("The value of b is: "+ b)
    val Sum:Double= a+b                   // definig the function sum
    println(Sum)
  }
}
