# Golang

### Go Data Types: 

    var a bool = true     // Boolean
    var b int = 5         // Integer
    var c float32 = 3.14  // Floating point number
    var d string = "Hi!"

### Defining Variables:

    1. var a = "initial"
    2. var b, c int = 1, 2
    3. var d = true
    4. var e int => e will be equal 0
    5. f := "apple"
    
### Defining Pointers:

    1. x *int
    2. xPtr := new(int)
    - To get the vqalue of a pointer:
    *pointerName
    - To a pointer to a var location:
    pointerName = &var

### Condetionnal Statements:

    if x == 50 {
		fmt.Println("Germany")
	} else if x == 100 {
		fmt.Println("Japan")
	} else {
		fmt.Println("Canada")
	}
  
