# Golang

### Go Data Types: 

    var a bool = true     // Boolean
    var b int = 5         // Integer
    var c float32 = 3.14  // Floating point number
    var d string = "Hi!"

### Defining Variables:

    var a = "initial"
    var b, c int = 1, 2
    var d = true
    var e int => e will be equal 0
    f := "apple"
    
### Defining Pointers:

    x *int
    xPtr := new(int)
    // To get the vqalue of a pointer:
    *pointerName
    // To a pointer to a var location:
    pointerName = &var

### Condetionnal Statements:

    if x == 50 {
		fmt.Println("Germany")
	} else if x == 100 {
		fmt.Println("Japan")
	} else {
		fmt.Println("Canada")
	}
	
 ### Data structures:
 
 	var studentsAge [10]int
	studentsAge := [10]int{1, 2, 3, 4, 5, 6, 7, 8, 9, 10}
	// Accessing data in arrays:
	studentsAge[0] = 5
	// creating slices from arrays
	fiveStudents := studentsAge[0:5]
	fmt.Println(fiveStudents) // [1 2 3 4 5]
	a := []string{"John", "Paul"}
	b := []string{"George", "Ringo", "Pete"}
	a = append(a, b...) // equivalent to "append(a, b[0], b[1], b[2])"
	// a == []string{"John", "Paul", "George", "Ringo", "Pete"}
	
	// A map is a data structure that assigns keys to its values (key-value pairs).
	// It is similar to Objects in JavaScript, HashMap in Java, and Dictionaries in Python.
	// The zero value of a map is nil.
	var studentsAge map[string]int
	// Maps must be initialized with make after their creation before assigning values to them.
	studentsAge = make(map[string]int)
	studentsAge := map[string]int{
	  "solomon": 19,
	  "john":    20,
	  "janet":   15,
	  "daniel":  16,
	  "mary":    18,
	}
	// adding values to the map
	studentsAge["solomon"] = 19
	
