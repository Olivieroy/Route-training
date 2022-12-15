<div align="center">
    <h1> Kit-Starter VueJs </h1>
    <p> A starter template for junior VueJs developper </p>
    <img src="https://cdn.discordapp.com/attachments/954117377593868331/1047879287275012176/kit-starter.png">
</div>

## Table of Contents 👨🏻‍🏫

1. [Table of Contents](#table-of-contents-👨🏻‍🏫)
2. [Browser Support](#browser-support-🌐)
3. [Installation](#installation-📦)
4. [Usage](#usage)
5. [Structure](#structure-🔨)
6. [License](#license-📜)
7. [Autor](#autor)


## Browser Support 🌐
- Chrome
- Firefox
- Safari
- Edge
- Opera

## Installation 📦
First step : clone the repository

```sh
$ git clone https://github.com/Olivieroy/web-starter.git
```

Second step : install the dependencies with npm

```sh
$ npm install sass
```

Third step : run the project.
Good Luck ! 🍀

## Structure 🔨

### Forlder structure

```
├── .vscode 📁 
│   └── extensions.json 📄   # Extensions for Vue in Vscode
│
├── node_modules 📁       # Dependencies
│
├── public 📁             # Public files
│   ├── favicon.ico 📄    # Favicon
│   │
│   ├── css 📁        # Css files
│   │   ├── master.css 📄  # Css file
│   │   │
│   │   ├── remove.css 📄  # Css file for remove
│   │
│   ├── img 📁        # Images
│   │
│   └──  sass 📁                    # SASS folder
│       ├── libs 📁              # Libs folder
│       │   ├── _index.scss 📄        # Index file for libs
│       │   │
│       │   ├── _normalize.scss 📄        # Normalize file
│       │   │
│       │   └──  _reset.scss 📄        # Reset file
│       │
│       └──  master 📄              # SCSS file for the project to compiled 
│
├── src 📁               # Source files
│   ├── components 📁        # Components folder
│   │   └──Button.vue 📄    # Button component
│   │
│   ├── layouts 📁        # Layouts folder
│   │   ├── Header.vue 📄    # Header component
│   │   │
│   │   └──  Footer.vue 📄    # Footer component
│   │
│   ├── pages 📁        # Pages folder
│   │   ├── AboutView.vue 📄    # About page
│   │   │
│   │   ├──  ComponentsView.vue 📄    # Components page
│   │   │
│   │   └──HomeView.vue 📄    # Home page
│   │
│   ├── parts 📁        # Parts folder
│   │   ├── AboutHelp.vue 📄    # Help part
│   │   │
│   │   ├──  AboutProject.vue 📄    # Project part
│   │   │
│   │   └──Congralutation.vue 📄    # Congralutation part
│   │
│   ├── router 📁        # Router folder
│   │   └──index.js 📄    # Router file
│   │
│   ├──  sass 📁                    # SASS folder
│   │  ├── global 📁              # Global folder
│   │  │   ├── _animations.scss 📄        # Animations file
│   │  │   │
│   │  │   ├── _breakpoints.scss 📄        # Breakpoints file
│   │  │   │
│   │  │   ├── _colors.scss 📄        # Colors file
│   │  │   │
│   │  │   ├── _fonts.scss 📄        # Fonts file
│   │  │   │
│   │  │   ├── _functions.scss 📄        # Functions file
│   │  │   │
│   │  │   ├── _icons.scss 📄        # Icons file
│   │  │   │
│   │  │   ├── _index.scss 📄        # Index file for global
│   │  │   │
│   │  │   └──  _mixins.scss 📄        # Mixins file
│   │  │
│   │  └──  master 📄              # SCSS file for the project to compiled in .vue file
│   │
│   ├── App.vue 📄      # App file
│   │
│   └── main.js 📄      # Main file
│
├── .eslintrc.cjs 📄       # Eslint file
│
├── .gitignore 📄       # Gitignore file
│
├── .prettierrc.json 📄       # Prettier file
│
├── index.html 📄              # Index file for the project
│
├── LICENSE 📄              # License file
│
├── package-lock.json 🛠                   # JSON file 
│
├── package.json 🛠                   # JSON file
│
├── README.md 📄              # Readme file
│
└──vite.config.js 📄              # Vite config file
```





## Usage
- `npm run sass` : compile sass to css 
- `npm run dev` : run the project in development mode
<p> You can create another "npm run" command in the package.json file 😎 </p>

## License
[MIT](https://github.com/Olivieroy/web-starter/LICENSE.) 

## Author
[Olivieroy](https://olivieroy.fr) 🧢
