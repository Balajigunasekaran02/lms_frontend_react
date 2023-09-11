# LMS Frontend

1. Clone the Project

   ```
       git clone https://github.com/Balajigunasekaran02/lms_frontend_react.git

   ```

2. Move into the directory

   ```
       cd lms_frontend_react

   ```

3. Install dependecies

   ```
       npm install

   ```

4. Run the server

   ```
       npm run dev

   ```

### Setup Tailwind in your project

1. Install tailwind and other dependencies

   ```
       npm install -D tailwindcss postcss autoprefixer

   ```

2. Create the tailwind.config.js file

   ```
       npx tailwindcss init -p

   ```

3. Add the files and extensions to tailwind config in the content property
   ```
   content: [
       "./index.html",
       "./src/**/*.{js,ts,jsx,tsx}",
   ],
   ```
4. Add the tailwind directives on the top of index.css file
   ```
       @tailwind base;
       @tailwind components;
       @tailwind utilities;
   ```
   Run the server,tailwind should be integrated
