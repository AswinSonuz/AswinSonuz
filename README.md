```go
package main

import "fmt"

func main() {
    aswin := Developer{
        Name:        "Aswin TR",
        Degree:      "BTech in Civil Engineering",
        Diploma:     "Civil Engineering",
        TechStack:   []string{"JavaScript", "React", "Python", "Go"},
        CurrentGoal: "Building professional-grade web applications",
    }

    fmt.Println("Welcome to my profile!")
}

type Developer struct {
    Name        string
    Degree      string
    Diploma     string
    TechStack   []string
    CurrentGoal string
}
