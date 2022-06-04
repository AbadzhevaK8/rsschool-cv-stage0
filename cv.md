# Abadzheva Ekaterina
## Junior developer
*******
### Contacts

__email__: make.me.loco@gmail.com

__phone__: +7 953 153 28 29

[Github](https://github.com/AbadzhevaK8/)

********
### Summary
I have been working as a project manager from 2014 to 2017.
During this period I gained experience:
* Jira
* designing online stores, corporate websites
* writing technical documentation, specifications
* manual testing of interfaces using our own specs (general experience of such work is 2 years).

Then, for three years I have  been working as a content manager (from April 2017 to December 2019).
While I was working, I began to learn on my own:
* html/css/ChromeDevTools
* git/github/gitkraken
* python/PyPI/django/selenium
* SQL
* statistics (stepik course)
* ubuntu/bash/command line interface
* superficial: kotlin/java/js
* PyCharm/IntelliJ IDEA
Got it and quit. (December 30, 2019)

An epidemic began, and I went to a testing course to systematize knowledge.
On the course, I figured out what normal testing is, how it is built, methods, tools, test design.

Acquired new skills and knowledge:
* basics of API testing (on Postman),
* I wrote tests on Selenium in Java (before only on python Selenium),
* worked in TestRail and YouTrack.
Systematized and supplemented the early testing experience.

Now I'm learning to create a golang backend and a frontend.


*******
### Skills
* HTML / CSS / JS
* python
* golang
* Selenium
* SQL
* git
* jira
* kotlin
*******
### Code example

```
package main

import (
	"bufio"
	"fmt"
	"log"
	"os"
)

func main() {
	file, err := os.Open("data.txt")
	if err != nil {
		log.Fatal(err)
	}
	scanner := bufio.NewScanner(file)
	for scanner.Scan() {
		fmt.Println(scanner.Text())
	}
	err = file.Close()
	if err != nil {
		log.Fatal(err)
	}
	if scanner.Err() != nil {
		log.Fatal(scanner.Err())
	}
}
```
