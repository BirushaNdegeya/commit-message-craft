# Commit Message Craft

A comprehensive guide to writing clear, structured commit messages following conventional commit standards.

## **1. `feat` (Feature)**

Used when adding a **new feature** or functionality.  
💡 **What it means:** You introduced a new capability in the code.

### **Examples:**

✅ `feat(auth): implement user login with JWT` → Added a login feature  
✅ `feat(navbar): add mobile menu toggle` → Introduced a new menu button

---

## **2. `fix` (Bug Fix)**

Used when fixing a **bug** or issue.  
💡 **What it means:** You corrected something that was broken.

### **Examples:**

✅ `fix(form-validation): correct email regex pattern` → Fixed incorrect email validation  
✅ `fix(api): resolve CORS issue in production` → Solved a CORS-related error

---

## **3. `refactor` (Code Refactoring)**

Used when changing the **internal structure** of the code **without** modifying its functionality.  
💡 **What it means:** The code is cleaner or better optimized but works the same way.

### **Examples:**

✅ `refactor(utils): optimize currency conversion function` → Improved the function without changing output  
✅ `refactor(dashboard): simplify state management logic` → Simplified complex logic

---

## **4. `docs` (Documentation)**

Used when modifying **documentation** files.  
💡 **What it means:** You updated README files, API docs, or comments.

### **Examples:**

✅ `docs(readme): update installation instructions` → Updated setup instructions  
✅ `docs(api): add missing endpoint details` → Added API endpoint documentation

---

## **5. `style` (Styling & Formatting)**

Used when modifying **whitespace, indentation, or code style** **without** affecting functionality.  
💡 **What it means:** The code looks better but works the same way.

### **Examples:**

✅ `style(button): update primary button hover effect` → Adjusted button styles  
✅ `style(global): apply new typography and spacing` → Improved UI styling

---

## **6. `perf` (Performance Improvement)**

Used when improving the **speed or efficiency** of the code.  
💡 **What it means:** The code runs faster or uses fewer resources.

### **Examples:**

✅ `perf(image-loading): implement lazy loading for images` → Optimized how images load  
✅ `perf(database): reduce query response time by indexing` → Improved database performance

---

## **7. `chore` (Maintenance Tasks)**

Used for routine **tasks** like updating dependencies, setting up configs, or fixing CI/CD pipelines.  
💡 **What it means:** You did background work, but nothing changed for the user.

### **Examples:**

✅ `chore(deps): update eslint and prettier versions` → Updated dependencies  
✅ `chore(ci): fix GitHub Actions build process` → Fixed an issue in the CI/CD pipeline

---

## **8. `test` (Adding or Updating Tests)**

Used when writing **new tests** or modifying existing tests.  
💡 **What it means:** You ensured the code is covered by tests.

### **Examples:**

✅ `test(utils): add unit tests for currency formatter` → Added new test cases  
✅ `test(api): update integration tests for login endpoint` → Updated API tests

---

## **9. `build` (Build System Changes)**

Used when modifying **build scripts or dependencies** (e.g., Webpack, npm, Yarn).  
💡 **What it means:** You changed how the project is built or packaged.

### **Examples:**

✅ `build(deps): bump next.js version to 14.0.0` → Updated dependencies  
✅ `build(webpack): optimize production bundle size` → Improved how the app is bundled

---

## **10. `ci` (Continuous Integration)**

Used when changing CI/CD **pipeline** configuration (GitHub Actions, Travis, Jenkins).  
💡 **What it means:** You modified how the project is tested or deployed.

### **Examples:**

✅ `ci(github-actions): fix workflow for deployment` → Fixed GitHub Actions workflow  
✅ `ci(travis): update Node.js version in CI config` → Changed CI environment

---

## **11. `revert` (Reverting a Commit)**

Used when **undoing** a previous commit.  
💡 **What it means:** You made a mistake and are rolling back changes.

### **Examples:**

✅ `revert: feat(navbar): add mobile menu toggle` → Undoes a feature  
✅ `revert: fix(form-validation): correct email regex` → Reverts a bug fix

---

## **Which One Should You Use?**

- Adding something new? → **`feat`**
- Fixing something broken? → **`fix`**
- Cleaning up code? → **`refactor`**
- Updating docs? → **`docs`**
- Changing styles? → **`style`**
- Improving speed? → **`perf`**
- Doing maintenance? → **`chore`**
- Updating tests? → **`test`**
- Changing build system? → **`build`**
- Fixing CI/CD? → **`ci`**
- Undoing something? → **`revert`**
