![The Silicon Valley](https://wallpapercave.com/wp/wp2022116.jpg)

# Hi Everyone

```go
package main

func main(){
    handler := func(w http.ResponseWriter, r *http.Request) {
		fmt.Fprintln(w, "Hello, World!")
	}

    http.HandleFunc("/", handler)

    port := 8080

	fmt.Printf("Server is running on port %d...\n", port)

	err := http.ListenAndServe(fmt.Sprintf(":%d", port), nil)

	if err != nil {
		fmt.Printf("Error: %v\n", err)
	}
}
```

### A short Intro about myself

My name is Abhishek Jain. I hail from a city called Kota in Rajasthan. I did my bachelors in Economic Sciences with double majors in Computer Science and Engineering from IIT KANPUR. Post that I worked with Oracle India Pvt. Ltd as a Member of Technical Staff for 17 months. After that journey I joined a startup named Masai School which a coding bootcamp where I taught around 500+ students. 

The technologies that attract me -

- Flutter
- Golang
- Data Intensive Applications

