```go
\package profile

type Engineer struct {
    Name     string
    Degree   string
    Diploma  string
    Location string
}

func GetAswin() Engineer {
    return Engineer{
        Name:     "Aswin TR",
        Degree:   "BTech in Civil Engineering",
        Diploma:  "Civil Engineering",
        Location: "Kerala, India",
    }
}
