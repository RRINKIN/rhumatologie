# rhumatologie
Website for the doctor Ch. Rinkin

# rebuilding css with tailwind
This website doesn't uses the CDN but builds the css via a npm commando 
npx tailwindcss -i ./global.css -o ./output.css --watch
It tales input from global.css and creates a new file called output.css
To be run into the terminal
The system will watch for any changes and rebuild the .css on the fly