  
  # Website-> https://tailwindcss.com/docs/installation
  
  1.npm init -y <br/>
  2.npm install -D tailwindcss<br/>
  3.npx tailwindcss init<br/>
  4.tailwind config -> inside content "*html"<br/>
  5. in input css :<br/>
         @tailwind base;<br/>
         @tailwind components;<br/>
         @tailwind utilities;<br/>
  6. create a script in package.json name build -> npx tailwindcss -i ./src/input.css -o ./src/output.css --watch