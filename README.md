# Arrays

        Dim n(10) As Integer  ' n is an array of 11 integers '
        Dim i, j As Integer
        ' initialize elements of array n '         
        For i = 0 To 10
            n(i) = i + 100 ' set element at location i to i + 100 
        Next i
        ' output each array element's value '
        For j = 0 To 10
            Console.WriteLine("Element({0}) = {1}", j, n(j))
        Next j
        Console.ReadKey()
    
    #Arrays2    
    
    Sub Main()
      Dim marks() As Integer
      ReDim marks(2)
      marks(0) = 85
      marks(1) = 75
      marks(2) = 90
      ReDim Preserve marks(10)
      marks(3) = 80
      marks(4) = 76
      marks(5) = 92
      marks(6) = 99
      marks(7) = 79
      marks(8) = 75
      For i = 0 To 10
          Console.WriteLine(i & vbTab & marks(i))
      Next i
      Console.ReadKey()


