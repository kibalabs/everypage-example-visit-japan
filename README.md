# Everypage-Example-Visit-Japan
[*Travel to Japan*](https://hardcore-feynman-92bd24.netlify.app/) is a example site made using an open source library [EveryPage](https://www.everypagehq.com/). Using EveryPage, anyone having experience in JSON and CSS can create a website with ease.

# Project Setup
1. In the project directory, install [`@kibalabs/everypage`](https://github.com/kibalabs/everypage), `@kibalabs/everypage-cli` :
```
  npm i @kibalabs/everypage @kibalabs/everypage-cli
```
2. Create a folder `site` and then create `content.json` and `theme.json` in the folder.

3. Add the build script to `package.json` :
```
  "build": "everypage build --clean --directory ./site --output-directory ./dist"
```
4. After completing your site, build the site using `npm run build` command.


# Tips
You can use the EveryPage [canvas](https://console.everypagehq.com/canvas) to create your website. This is completely optional but you can use the canvas features to create your website real quick and it helps you focus more on your site's content.


![image](https://user-images.githubusercontent.com/42097538/110957197-6725b680-8371-11eb-84e9-61329fe6a531.png)


Use the [`ui-react docs`](https://ui-react-docs.kibalabs.com/) for reference on creating custom theme for your site.

And when you are done, just copy the content JSON & paste inside the `content.json` file and the theme JSON inside & paste inside the `theme.json` file.
