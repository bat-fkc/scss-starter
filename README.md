# A quick sass starter architecture
![Sass image](https://miro.medium.com/max/1200/1*miUATuy4zIZlyu5ubWRgIw.png)
Start by install sass
```
npm install
```

Enable the auto saving changes by using the command below and switch to another terminal for you usual activity.
```
npm run compile:sass
```

You can change both the behavior and command in the package.json file
```
{
    ...
    "scripts": {
      "compile:sass": "node-sass sass/main.scss css/style.css -w"
    },
    ...
}
```