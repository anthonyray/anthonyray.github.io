# Online Presence

## Styling
I want to experiment with "functional" css, and decided to use [Tailwind](https://tailwindcss.com/docs/what-is-tailwind/) for this project. 
Tailwind is configured with a configuration file (found in `styles/tailwind.js`). 

The CSS stylesheets are generated with the following process : 
- The Tailwind CLI generates an output css stylesheet that is stored in the : `styles/output.css` file. It takes the tailwind config file (`styles/tailwind.js`) and the `styles/style.css` stylesheet as input. 
- The `styles/output.css` is then used by the website. 

The following process is done with this command : 
```
./node_modules/tailwindcss/lib/cli.js build styles/styles.css -o styles/output.css -c styles/tailwind.js
```


