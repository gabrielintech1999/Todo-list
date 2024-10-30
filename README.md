# Todo list


# tasks
- Create github repo
- deploy to vercel
- create basic files
- setup tailwind
- Build the HTML Structure
- Style the App with Tailwind
- Write TypeScript Code (Functionality)
- Configure TypeScript Compilation
- Test the App
- Enhancements (Optional)

























Sure! Here's a **To-Do List** for building the **To-Do List App** itself. You can use this checklist to keep track of your progress.

---

## 📝 **To-Do List for Building the To-Do App**

### 1️⃣ **Setup Project Structure**
- [ ] Create a new folder named `todo-list`.
- [ ] Inside it, create the following files:
  - [ ] `index.html`
  - [ ] `styles.css`
  - [ ] `app.ts`
  - [ ] `tsconfig.json`

---

### 2️⃣ **Build the HTML Structure**
- [ ] Add a `<div>` container for the app layout.
- [ ] Create an **input field** to enter new tasks.
- [ ] Add an **"Add" button** to submit tasks.
- [ ] Include a `<ul>` element to display the task list.

---

### 3️⃣ **Style the App with CSS**
- [ ] Use **flexbox** to align the input section.
- [ ] Style the container with padding and a shadow effect.
- [ ] Add colors and hover effects to buttons.
- [ ] Format the list items to include a delete button.

---

### 4️⃣ **Write TypeScript Code (Functionality)**
- [ ] Create an interface `Todo` for tasks (with `id`, `text`, `completed`).
- [ ] Add event listener to the **"Add" button**:
  - [ ] Create a task object and push it into the `todos` array.
  - [ ] Clear the input field after adding a task.
- [ ] Write a `renderTodos` function to display tasks in the `<ul>`.
- [ ] Write a `deleteTodo` function to remove tasks by `id`.
- [ ] Connect the **delete button** with `deleteTodo` using `onclick`.

---

### 5️⃣ **Configure TypeScript Compilation**
- [ ] Install TypeScript globally (if not already installed):
   ```bash
   npm install -g typescript
   ```
- [ ] Write a `tsconfig.json` file for TypeScript configuration.
- [ ] Compile `app.ts` to `app.js`:
   ```bash
   tsc app.ts
   ```

---

### 6️⃣ **Test the App**
- [ ] Open `index.html` in your browser.
- [ ] Add some tasks to test the **"Add" button**.
- [ ] Test the **delete button** to remove tasks.
- [ ] Check for any console errors or bugs.

---

### 7️⃣ **Enhancements (Optional)**
- [ ] Add **localStorage** to save tasks between page reloads.
- [ ] Add a **strike-through style** for completed tasks.
- [ ] Implement **task editing** feature.
- [ ] Improve the UI with animations or themes.

---

This checklist should guide you step-by-step in building the app. Let me know if you have any questions during the process! 🚀