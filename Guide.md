# Guide for Vue.js/Nuxt.js web developer

## Setup of the development environment
1. Install and setup Git if not already done
    - Don't forget to configure your git installation correctly, set your username and mail
    - Maybe install a diff/merge tool like [meld](https://meldmerge.org/)
2. Install Node.js current LTS version from [nodejs.org](https://nodejs.org/en/)
3. Install Visual Studio Code from [code.visualstudio.com](https://code.visualstudio.com)
    1. Install following plugins
        - [EditorConfig for VS Code](https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig)
        - [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
        - [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
        - [Vetur](https://marketplace.visualstudio.com/items?itemName=octref.vetur)
        - [vscode-icons](https://marketplace.visualstudio.com/items?itemName=vscode-icons-team.vscode-icons)
        - [Vue VSCode Snippets](https://marketplace.visualstudio.com/items?itemName=sdras.vue-vscode-snippets)
        - [vuetify-vscode](https://marketplace.visualstudio.com/items?itemName=vuetifyjs.vuetify-vscode)
    2. Configure the plugins
        - Add the following settings to your Visual Studio Code's settings.json file
        ```
        "editor.codeActionsOnSave": 
        {
            "source.fixAll.eslint": true
        },
        "editor.formatOnSave": false,
        "editor.tabSize": 2,
        "eslint.alwaysShowStatus": true,
        "files.eol": "\n",
        "git.path": <your path to your git.ext file>,
        "terminal.integrated.shell.windows": "C:\\WINDOWS\\System32\\cmd.exe",
        "vetur.validation.template": false,
        "workbench.iconTheme": "vscode-icons"
        ```
4. Install Chrome if not already done
5. Install the Chrome extension [Vue.js devtools](https://chrome.google.com/webstore/detail/vuejs-devtools/nhdogjmejiglipccpnnnanhbledajbpd?hl=de) for debugging the Vue applications in the browser

## Documentations
We are still using Vue.js 2.x be aware that you don't accidentally read the version 3.x documentations.

### Vue.js Basics
- [Vue.js - Guide & Introduction](https://vuejs.org/v2/guide/)
- [Vue.js - Style Guide](https://vuejs.org/v2/style-guide/)
- [Vue.js - The Cookbook](https://vuejs.org/v2/cookbook/)

### Vuex
- [What is a state management patter](https://vuex.vuejs.org/#what-is-a-state-management-pattern)
- [Vuex - Guide](https://vuex.vuejs.org/guide/)

### Nuxt.js
- [Nuxt.js Documentation](https://nuxtjs.org/docs/2.x/get-started/installation)

### Vuetify
- [Vuetify Documentation](https://vuetifyjs.com/en/introduction/why-vuetify/#guide)

## Video Courses
1. Vue Mastery
    1. [Intro to Vue 2](https://www.vuemastery.com/courses/intro-to-vue-js)
2. Vue School
    1. [Vue.js Fundamentals](https://vueschool.io/courses/vuejs-fundamentals)
    2. [Vue.js Components Fundamentals](https://vueschool.io/courses/vuejs-components-fundamentals)
    3. [Vuex for Everyone](https://vueschool.io/courses/vuex-for-everyone)
    4. [Reusable Vue.js Components with Slots](https://vueschool.io/courses/reusable-vuejs-components-with-slots)
    5. [Nuxt.js Fundamentals](https://vueschool.io/courses/nuxtjs-fundamentals)
    6. [Internationalization with vue-i18n](https://vueschool.io/courses/internationalization-with-vue-i18n)

## Demo example projects
Demo Nuxt web projects which includes some best practices like:
- I18n
- Usage of Cookies
- Calling REST Apis
- Writing unit test
- Customize Vuetify components

### [Nuxt Demo App](https://github.com/Tobias-Doerner/nuxt-demo)
### [Air Pollution Demo App](https://github.com/Tobias-Doerner/Code.Now)

## Additional Ressources
- [Debbie O'Brien - Leave your legacy code behind and go Nuxt](https://youtu.be/FBEOIuDUZh4)
- [Debbie O'Brien - Nuxt.js Youtube Channel](https://www.youtube.com/watch?v=IRKx97XfiYI&list=PLtIMuymsF0jcsFDIAq6fGGU2kuOFrFPSm&index=1)
