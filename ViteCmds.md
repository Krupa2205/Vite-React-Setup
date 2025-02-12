

# markdown...

# **Step 1:** 
- Check your path using the `ls` command.

# **Reference:**
- Visit [Vite.js Guide](https://vitejs.dev/guide/)

# **Step 2:**
- Run the following command to create a new Vite project:
- Open the terminal using ...
# Ctrl + Shift + ` 

# bash run this ..
# npm create vite@latest


# - Follow the prompts:

  - Enter your project name.
  - Use the same package name.
  - Select `React` and press Enter.
  - Select `JavaScript` and press Enter.
  -After this go to your file using 'cd' command.

# **Step 3:**
- Install dependencies:

# Run this..

# npm install


# **Step 4:** 
- Visit the [TailwindCSS website](https://tailwindcss.com/).

# - Follow these steps to set up TailwindCSS:
  - Select "Framework Guides."
  - Choose "Vite."

# - Run these commands to install TailwindCSS and its dependencies:

# Run this..

# npm install -D tailwindcss@3 postcss autoprefixer

# npx tailwindcss init -p


# - Open the `tailwind.config.js` file and replace the `content` section with the following:

###

content: [
  "./index.html",
  "./src/**/*.{js,ts,jsx,tsx}",
],


# - Open the `index.css` file and replace its content with the following:

###

@tailwind base;
@tailwind components;
@tailwind utilities;


# - Clean up the extra code in the `App.jsx` file and add:

<>
  <h1>Hello React..</h1>
</>


# **Final Steps:**

# npm run dev


Your Vite setup is now complete, and you're ready to start your new project. **Done!**
