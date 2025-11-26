# 🐹 Getting Started With Go (Golang) – A Beginner-Friendly Toolkit

## 🎯 1. Title & Objective

**Technology Chosen:** Go (Golang)  
**Why I Chose It:**  
Go is fast, simple, and widely used in backend systems, cloud infrastructure, APIs, and microservices. It’s beginner-friendly but powerful enough for real-world production applications such as Kubernetes, Docker, and Terraform.

**End Goal:**  
Create a simple runnable Go program (“Hello API”) and understand how to set up, run, and document a Go project.

---

## ⚡ 2. Quick Summary of Go

Go (Golang) is an open-source, compiled programming language created by Google.

### ✔ What Go Is
- A fast, statically typed language  
- Designed for simplicity and concurrency  
- Great for backend systems, APIs, and cloud services  

### ✔ Where It Is Used
- Building REST APIs  
- Cloud platforms (Google Cloud, AWS, Digital Ocean)  
- DevOps and infrastructure tools (Docker, Kubernetes)

### ✔ Real-World Example
**Docker** — the containerization platform — is written in Go.

---

## 🖥️ 3. System Requirements

### Operating System  
- Windows  
- Linux  
- macOS  

### Required Tools  
- Go compiler (https://go.dev/dl/)  
- VS Code or any editor  
- Git (optional but recommended)

### Optional  
- Terminal (PowerShell / WSL / Git Bash / CMD)

---

## ⚙️ 4. Installation & Setup Instructions

### **Step 1 — Install Go**
Download and install Go from the official site:

https://go.dev/dl/

Verify installation:

```sh
go version
```
## Step 2 — Create Your Project Folder
```
mkdir go-capstone
cd go-capstone
```

## Step 3 — Initialize Your Go Module
```
go mod init go-capstone
```
## Step 4 — Create the Main File
```
main.go
```

## Add this inside:

```
package main

import "fmt"

func main() {
    fmt.Println("Hello, Go Developer!")
}
```

## Step 5 — Run the Program

```
go run main.go
```


## 6. AI Prompt Journal
Prompt #1

Prompt:
“Explain how to initialize a Go project and run a simple Hello World program.”

AI Output Summary:
Helped with Go installation, module initialization, and sample code.

Evaluation:
Very helpful.

Prompt #2

Prompt:
“Fix the error: AttributeError: 'int' object has no attribute 'int' in Go.”

AI Output Summary:
Explained that the issue was from Python, not Go, preventing confusion.

Evaluation:
Helpful clarification.

Prompt #3

Prompt:
“Give me a step-by-step guide to write a README for a Go beginners capstone project.”

AI Output Summary:
Provided structure and formatting guidance for documentation.

Evaluation:
Time-saving and effective.

## 🛠️ 7. Common Issues & Fixes
❗ Issue: go: command not found

Fix:
Go not installed or not added to PATH. Reinstall and restart terminal.

❗ Issue: VS Code shows “gopls not installed”

Fix:
Click Install All when prompted.

❗ Issue: go mod init failing

Fix:
Ensure folder is empty or delete old go.mod.

❗ Issue: Terminal not opening after closing VS Code

Fix:
Open manually via:

Windows: PowerShell or CMD

Linux/Mac: Terminal

VS Code: View → Terminal

## 📚 8. References

Official Go Docs – https://go.dev/doc/

Tour of Go – https://go.dev/tour/

Go by Example – https://gobyexample.com/

pkg.go.dev – https://pkg.go.dev/
