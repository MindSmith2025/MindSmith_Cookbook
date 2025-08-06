# 🧠🍳 MindSmith CookBook Vol. 1

Welcome, young chefs and coders! This is a collaborative recipe book built using **HTML** and **GitHub**. Each of you will contribute your own tasty recipe by writing code and submitting it like a true software engineer!

---

## 🚀 How to Contribute

Follow these easy steps to add your recipe:

---

### 1️⃣ Fork the Repository

Click the **Fork** button at the top right corner of this GitHub page to create your own copy of the CookBook project.

---

### 2️⃣ Clone Your Fork

Copy the URL of your forked repository, then open your terminal or Git Bash and type:

```bash
git clone https://github.com/your-username/mindsmith-cookbook.git

Replace `your-username` with your actual GitHub username.

---

### 3️⃣ Create a New Branch

Branches help us keep things organized.

Use this format to name your branch:

```bash
feat/recipe-name
```

✨ **Examples:**

* `feat/jollof-rice`
* `feat/chicken-quasadelas`
* `feat/fried-plantains`

Create your branch like this:

```bash
cd mindsmith-cookbook
git checkout -b feat/your-recipe-name
```

---

### 4️⃣ Create Your Recipe Folder

Inside the `recipes/` folder, create a folder using your name or codename:

```bash
mkdir recipes/your_name
```

Then, add your HTML file inside your folder.

---

### 5️⃣ Write Your Recipe

Use the template below to structure your `index.html` file:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Assignment | MindSmith CookBook</title>
</head>
<body>
    <h1>Recipe Title</h1>
    <h2>Your Name</h2>
    <p>Short description of the recipe.</p>
    
    <img src="images/your-image.jpg" alt="Image of your recipe">
    <p><i>Caption for the image</i></p>

    <h3>Ingredients</h3>
    <ul>
        <li>Ingredient 1</li>
        <li>Ingredient 2</li>
    </ul>

    <h3>Preparation Steps</h3>
    <h5>Step 1</h5>
    <p>Explain step 1</p>

    <h5>Step 2</h5>
    <p>Explain step 2</p>

    <h5>Step 3</h5>
    <p>Explain step 3</p>

    <h5>Step 4</h5>
    <p>Explain step 4</p>

    <h4>Tips</h4>
    <p>Any extra helpful tips or tricks</p>

    <footer>
        <p>Created for MindSmith CookBook</p>
    </footer>
</body>
</html>
```

---

### 6️⃣ Commit Your Changes

Save your work, then run:

```bash
git add recipes/your_name/
git commit -m "Add my recipe: [Recipe Name]"
```

Example:

```bash
git commit -m "Add my recipe: Chicken Quasadelas"
```

---

### 7️⃣ Push Your Branch

Send your branch to your fork on GitHub:

```bash
git push origin feat/your-recipe-name
```

---

### 8️⃣ Open a Pull Request (PR)

1. Go to your forked repo on GitHub.
2. Click **Compare & Pull Request**.
3. Add a short description of your recipe.
4. Submit!

🎉 You’ve contributed to an open source project!

---

## 📁 Sample Folder Structure

```sql
mindsmith-cookbook/
│
├── recipes/
│   ├── Edenian_Knight/
│   │   └── index.html
│   └── Shimmering_Siren/
│       └── index.html
│
└── README.md
```

---

## 🧑‍🍳 Keep in Mind

* Use clean, readable HTML.
* All images must be in `.jpg`, `.png`, or `.gif` format.
* Use proper tag nesting and closing tags.
* Ask your teacher or sidekick (mom/dad) if you're stuck.

---

**Happy Cooking & Coding!**
*\~ The High Code Commander 🛡️*
