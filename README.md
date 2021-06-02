# Restaurant Page - [Odin Project](https://www.theodinproject.com/paths/full-stack-javascript/courses/javascript/lessons/restaurant-page)

Additional steps to take when deploying a subfolder to Github Pages:
1. `git add dist && git commit -m "Initial dist subtree commit"`
2. `git subtree push --prefix dist origin gh-pages`

## Directory Structure

```sh
+---dist
|   |   index.html
|   |   main.js
|   |   style.css
+---node_modules
+---src
|   |   index.js
|   |   module01.js
+---.gitignore
+---package-lock.json
+---package.json
/---webpack.config.js
```