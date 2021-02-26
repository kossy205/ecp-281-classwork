# ecp-281-classwork
Imports System.Math
Public Module Program
 Public Sub Main()

  Console.WriteLine("My name is OKOYE KOSISOCHUKWU HILLARY" )
  Console.WriteLine("My matriculation number is ENG1804778")
  Console.WriteLine("My department is the  Department of Computer Engineering of engineering Faculty of the University Of Benin.")
  Console.WriteLine("I am in 200 Level (Second Year).")  

  Dim mat1 as Integer
  Dim mat2 as Integer
  Dim sum as Integer
  Dim result as Double
  Dim exp as Integer

  mat1 = 18
  mat2 = 77
  
  sum = mat1 + mat2
  result = Sqrt(mat1)
  exp = Pow(mat2,3)

  Console.WriteLine("The Two integers are: " & mat1 & "  and " & mat2)
  
  Console.WriteLine("The addition of the two integers is:" & sum)
  Console.WriteLine("The squareroot of the first integer is: " & result)
  Console.WriteLine("The cube of the second integer is: " & exp)
  
 
 End Sub
End Module
