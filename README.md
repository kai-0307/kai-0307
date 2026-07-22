# Hi there 👋

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
	Currently  []string
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

	Currently: []string{
		"Building scalable backend services",
		"Learning cloud architecture",
	},

	Interests: []string{
		"Backend",
		"Cloud",
		"Security",
	},
}
```
