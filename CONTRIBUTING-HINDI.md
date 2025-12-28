# Yogdaan Dene Ke Tareeke (How to Contribute)

## Welcome to Awesome Go - Indian Edition!

Hum aapke yogdaan ka swagat karte hain! Here's how you can help improve this project:

## 1. Fork Kare Repository

```bash
# GitHub par jaao aur fork button press karo
# Or use command:
git clone https://github.com/YOUR-USERNAME/awesome-go-indian-edition.git
cd awesome-go-indian-edition
```

## 2. Branch Banaye

```bash
git checkout -b feature/hindi-docs-library-name
# ya
git checkout -b fix/issue-number
```

## 3. Apne Changes Kare

### Hindi Documentation ke liye:
- Cleaner, more understandable Hindi language use kare
- Examples ko Indian context mein explain kare
- Video links aur tutorials add kare

### New Libraries ke liye:
- Library ke main features likhe
- Use cases mention kare (Indian developers ke liye)
- Link ke saath kuch lines likhe description mein

### Code Examples:
```go
// Example: Gin Web Framework par simple API
package main

import "github.com/gin-gonic/gin"

func main() {
    r := gin.Default()
    
    r.GET("/namaste", func(c *gin.Context) {
        c.JSON(200, gin.H{
            "message": "Namaste! Welcome to Go",
        })
    })
    
    r.Run() // :8080 par chega
}
```

## 4. Commit Kare

```bash
# Good commit messages likhe
git add .
git commit -m "📝 Hindi docs: Add Gin framework guide"
# ya
git commit -m "✨ Feature: Add local Indian tutorials section"
```

### Commit Message Format:
- 🐛 Bug fix
- ✨ New feature
- 📝 Documentation
- 🎨 Styling/Formatting
- 🇮🇳 Hindi content
- 🔧 Configuration

## 5. Pull Request Banaye

```bash
git push origin feature/hindi-docs-library-name
```

GitHub par jaao, create pull request karo aur:
- Kya change kiye ye likhe
- Kyon important hai ye
- Kisne test kiya (aapne hi)

## 6. Review Process

- Maintainers aapke PR ko dekheenge
- Suggestions de sakte hain
- Changes request ho sakti hain
- Approved hone ke baad merge ho jaayega

## Contribution Guidelines

### ✅ Kya Kare:

1. **Hindi Documentation**
   - Clear Hindi language (न हिंदी न अंग्रेजी - दोनों mix kar sakte ho!)
   - Real-world Indian examples
   - Links to Hindi tutorials

2. **Library Descriptions**
   - Brief aur informative
   - Use cases mention kare
   - Performance metrics (agar ho)

3. **Examples**
   - Working code examples
   - Comments in Hindi bhi add kare
   - Indian context use kare

4. **Testing**
   - Code chala ke dekho
   - Links check karo (working ho)
   - Hindi spelling check karo

### ❌ Kya Na Kare:

1. Spam ya promotional content
2. Broken links
3. Poor quality documentation
4. Grammatically incorrect Hindi
5. Copyright content

## Special Focus Areas

Ab hum in areas mein contributions chahte hain:

1. **Hindi Tutorials** - Popular Go libraries ke liye
2. **Indian Dev Stories** - Go use karne wale Indian companies
3. **Performance Tips** - Low-bandwidth environments ke liye
4. **Interview Prep** - Go interview questions (Hindi + English)

## Code of Conduct

- Respectful ho
- Inclusive language use karo
- Disagreements professional tarike se solve karo
- Everyone ka opinion value karo

## Questions?

Agar koi doubt ho:

1. GitHub Issues mein pooch lo
2. Discussions tab mein likho
3. Indian Go community Discord mein join karo

## Helpful Resources

- [Main Awesome Go](https://github.com/avelino/awesome-go)
- [Go Official Docs](https://golang.org/doc/)
- [Effective Go](https://golang.org/doc/effective_go)

---

**Happy Contributing! Khush Rahiye, Coding Karte Rahiye!**

💖 Shukriya for making Awesome Go better for Indian developers!
