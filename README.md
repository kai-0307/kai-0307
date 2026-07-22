
```go
package github

type Engineer struct {
	Name       string
	Role       string
	Location   string
	Languages  []string
	Frameworks []string
	Cloud      []string
	Database   []string
	Interests  []string
}

var Kai = Engineer{
	Name:     "Kai Nakao",
	Role:     "Software Engineer",
	Location: "Tokyo, Japan",

	Languages: []string{
		"Go",
		"TypeScript",
		"Python",
		"Ruby",
	},

	Frameworks: []string{
		"Gin",
		"Echo",
		"Next.js",
		"React",
		"Ruby on Rails",
	},

	Cloud: []string{
		"AWS",
	},

	Database: []string{
		"MySQL",
		"PostgreSQL",
	},

	Interests: []string{
		"Backend",
		"Cloud",
		"Security",
	},
}
```
