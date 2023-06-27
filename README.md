# eleventy-tailwind-starter
This project is using [eleventy](https://www.11ty.dev/docs/) to build static sites with [Nunjucks](https://mozilla.github.io/nunjucks/) and [tailwind](https://tailwindcss.com/) to use an easy approach for styling.

## How to run
Simply install the relevant packages with `npm i` and run the code with `npm start`.
Eleventy will build the files in the src folder and deploy them to the `_site` folder. Running the command `npm start` will run a development server reacting to changes made and refreshing the build sites.

## How is it working?
Eleventy is a plain and simple page builder. It uses a templating language (I used Nunjucks) and is passing data into that template to build a static HTML file. It uses the `data.json` file and passes it as the data object to the template (it uses the file name to name the object).