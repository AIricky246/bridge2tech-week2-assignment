# Week 2 Homework Assignment
## Personal Portfolio Website with Git Workflow

**⏱️ Estimated Time:** 60 minutes maximum  
**🎯 Skills Practiced:** HTML structure, semantic elements, Git commands, GitHub workflow

---

## 📋 Assignment Overview

Create a personal portfolio website using only HTML (no CSS yet) and practice professional Git workflow. You'll need to figure out some HTML elements on your own using the resources provided.

---

## 🚀 Getting Started

### **Step 1: Fork the Repository (5 minutes)**

1. **Go to the assignment repository:**
   - Navigate to: `https://github.com/cpscott1/bridge2tech-html-assignment`
   
2. **Fork the repository:**
   - Click the "Fork" button in the top-right corner
   - This creates a copy under your GitHub account

3. **Clone your forked repository:**
   ```bash
   # Replace YOUR-USERNAME with your actual GitHub username
   git clone https://github.com/YOUR-USERNAME/bridge2tech-html-assignment.git
   cd bridge2tech-html-assignment
   ```

4. **Verify you're in the right place:**
   ```bash
   git remote -v
   # Should show your forked repository URL
   ```

---

## 🏗️ Build Your Portfolio (35 minutes)

### **Start with this basic structure in index.html:**

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Name - Web Developer Portfolio</title>
</head>
<body>
    <header>
        <h1>Your Full Name</h1>
        <!-- Add navigation here -->
    </header>

    <main>
        <!-- Add your content sections here -->
    </main>

    <!-- Add footer here -->
</body>
</html>
```

### **Required Content Sections:**

#### **1. Navigation (Research Required)**
- Create a navigation menu with links to: About, Skills, Goals, Contact
- **Hint:** Look up how to create navigation lists and internal page links
- **Challenge:** Make the links actually work by connecting them to your sections

#### **2. About Me Section**
```html
<section id="about">
    <h2>About Me</h2>
    <!-- Add an image placeholder here - figure out the right element and attributes -->
    
    <p>Write 2-3 sentences introducing yourself.</p>
    
    <!-- Create a list of 3 things about your background -->
    
    <h3>My Story</h3>
    <p>Write about your journey to web development.</p>
</section>
```

#### **3. Skills Section** 
```html
<section id="skills">
    <h2>My Skills & Interests</h2>
    
    <h3>Technical Skills I'm Learning</h3>
    <!-- Create a bulleted list of skills -->
    
    <h3>Other Skills</h3>
    <!-- Create another list of non-programming skills -->
    
    <h3>My Top 5 Hobbies</h3>
    <!-- Research: What HTML element creates numbered lists? -->
</section>
```

#### **4. Goals Section**
```html
<section id="goals">
    <h2>My Goals</h2>
    
    <h3>What I Want to Learn This Year</h3>
    <!-- Add your learning goals as a list -->
    
    <h3>Career Goals</h3>
    <!-- Add your career aspirations -->
    
    <!-- Challenge: Add a subsection about dream projects -->
</section>
```

#### **5. Contact Section (Research Required)**
```html
<section id="contact">
    <h2>Get In Touch</h2>
    
    <!-- Research: What HTML element is used for contact information? -->
    
    <!-- Add links to your email, GitHub, and LinkedIn -->
    <!-- Hint: Look up how to create email links -->
    
</section>
```

#### **6. Footer**
```html
<!-- Add a footer with copyright information -->
```

---

## 🔍 Research Challenges

**You'll need to figure out:**

1. **How to create navigation lists** - What elements make a proper navigation menu?

2. **Internal page links** - How do you make navigation links jump to sections on the same page?

3. **Image elements** - What element displays images and what attributes does it need?

4. **Different list types** - What's the difference between bulleted and numbered lists?

5. **Contact information element** - There's a specific HTML element for contact details - what is it?

6. **Email links** - How do you make a link that opens the user's email program?

**🆘 Resources to help you:**
- **W3Schools:** https://www.w3schools.com/html/
- **MDN Web Docs:** https://developer.mozilla.org/en-US/docs/Web/HTML
- **freeCodeCamp:** https://www.freecodecamp.org/

---

## 📝 Git Workflow Practice (15 minutes)

### **Make 4 Strategic Commits:**

#### **Commit 1: Basic Structure**
```bash
# After creating HTML structure and navigation
git add index.html
git commit -m "Add basic HTML structure and navigation"
git push origin main
```

#### **Commit 2: About & Skills Sections**
```bash
# After completing about and skills sections
git add index.html
git commit -m "Add about me and skills sections"
git push origin main
```

#### **Commit 3: Goals Section**
```bash
# After completing goals section
git add index.html
git commit -m "Add goals section with learning objectives"
git push origin main
```

#### **Commit 4: Contact & Final Polish**
```bash
# After completing contact section and final review
git add index.html
git commit -m "Complete contact section and finalize portfolio"
git push origin main
```

---

## ✅ Requirements Checklist

Your completed portfolio must include:

### **HTML Structure:**
- [ ] Proper `<!DOCTYPE html>` and document structure
- [ ] All required meta tags in `<head>`
- [ ] Semantic HTML5 elements (`<header>`, `<nav>`, `<main>`, `<section>`, `<footer>`)
- [ ] Proper heading hierarchy (only one h1, then h2, h3, etc.)

### **Required Elements (Figure These Out):**
- [ ] Navigation menu with working internal links
- [ ] At least one image with proper attributes
- [ ] Both bulleted and numbered lists
- [ ] Contact information using the correct semantic element
- [ ] At least one email link
- [ ] External links to your GitHub/LinkedIn profiles

### **Content Requirements:**
- [ ] All 6 sections completed with your personal content
- [ ] No placeholder "Lorem ipsum" text
- [ ] Real information about yourself and your goals

### **Git Workflow:**
- [ ] Exactly 4 commits with descriptive messages
- [ ] All commits pushed to GitHub
- [ ] Repository is public

---

## 💡 Problem-Solving Tips

### **When you get stuck:**
1. **Check the class notes** - We covered these elements in Week 1
2. **Use the resources** - W3Schools has great examples
3. **Look at examples** - Search for "HTML navigation menu example"
4. **Test frequently** - Open your HTML file in a browser to see what works

### **For research:**
- Search for: "HTML [element name] example"
- Look for simple, clear examples
- Don't worry about styling - focus on structure
- Copy syntax patterns, but use your own content

### **Common issues:**
- **Links don't work:** Check your `href` attributes
- **Lists look wrong:** Make sure you're using the right list elements
- **Navigation doesn't link to sections:** Verify your `id` attributes match your links

---

## 🎯 What Success Looks Like

**When you're done:**
- You can click navigation links and jump to different sections
- All your lists display correctly (bulleted and numbered)
- Your contact links work (email opens mail program)
- Your HTML validates without errors at https://validator.w3.org/
- Your GitHub repository shows 4 meaningful commits

---

## 🏆 Stretch Goals (If you finish early)

- Add more sections like "Fun Facts" or "Learning Resources"
- Research and add a table showing your weekly schedule
- Figure out how to add more semantic elements like `<article>` or `<aside>`
- Add more external links to your favorite learning resources

---

## 🎓 Learning Outcomes

This assignment tests your ability to:
- ✅ Apply HTML knowledge to solve new problems
- ✅ Research and learn new HTML elements independently
- ✅ Create a complete, functional webpage
- ✅ Use professional Git workflow
- ✅ Problem-solve when you encounter challenges

**Remember:** The goal isn't to memorize every HTML element, but to know how to find and use the right elements for your content. Real developers look things up all the time! 🌟
