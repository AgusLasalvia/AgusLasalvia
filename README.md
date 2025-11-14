
```go
package main

import "fmt"

// Developer struct
type Developer struct {
    Name       string
    Age        int
    Languages  []string
    Role       string
    University string
    Email      string
    LinkedIn   string
    Instagram  string
	Status	   string
}


// Greet method
func (a *Developer) Greet() {
    fmt.Println("Hello There! :)")
}

// main function
func main() {
	agustin := Developer{
		Name:       "Agustin Lasalvia",
		Age:        24,
		Languages:  []string{"Spanish", "English"},
		Role:       "IT Support Technician",
		University: "ORT University",
		Email:      "agus.blumenfeld13@gmail.com",
		LinkedIn:   "https://www.linkedin.com/in/agustin-lasalvia",
		Instagram:  "https://www.instagram.com/agustin.lasalvia",
		Status:		"Searching for a Junior Developer Position"
	}

	agustin.Greet()
}
