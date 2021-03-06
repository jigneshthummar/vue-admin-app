# VueJS+NUXT+Vuetify+Vuex

### prerequisite

- install [NodeJS](https://nodejs.org/en/download/)
- install [VSCode](https://code.visualstudio.com/Download)
- install [VSCode Vue plugin](https://marketplace.visualstudio.com/items?itemName=MadsKristensen.VuejsPack2019)
- install vue cli
```
npm install -g @vue/cli
```

### create project folder
```
mkdir vue-admin-app
cd vue-admin-app
```

### init git repo & add readme
```
git init
echo "# VueJS+NUXT+Vuetify+Vuex" >> README.md
git add .
git commit -m "init git repo & add readme file"
```

### push code to remote repo
```
git branch -M main
git remote add origin https://github.com/jigneshthummar/vue-admin-app.git
git push -u origin main
```

### one click git add, commit & push
Linux
```
 git add . && git commit -m "one click git" && git push
```
Windows
```
 git add . ; git commit -m "one click git" ; git push
```

### NUXT installation
Windows
```
echo '{
  "name": "vue-admin-app",
  "scripts": {
    "dev": "nuxt",
    "build": "nuxt build",
    "generate": "nuxt generate",
    "start": "nuxt start"
  }
}' >> package.json
```
```
npm install nuxt
```
### create page
create folder
```
mkdir pages
```
create page
```
 pages/index.vue
```
add content
```
<template>
  <h1>Hello world!</h1>
</template>
```



