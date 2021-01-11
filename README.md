# SCSS Starter Files

![Sass](https://img.shields.io/badge/Sass-CC6699?style=for-the-badge&logo=sass&logoColor=white) ![HTML](https://img.shields.io/badge/HTML-239120?style=for-the-badge&logo=html5&logoColor=white) ![Node](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)

These are starter files for installing Sass to your project.

## Installation :gear:

1. From the repo, click the green "Code" button dropdown, adn select download .zip

2. Paste all of the contents of `scss-starter` folder into your project

3. If You Already Have a `package.json` in Your Project:

- Use your original `package.json` and `.gitignore`
- Run `npm install node-sass` dependency
- Copy the following line in the "scripts" section in `package.json`

```json
"sass": "node-sass styles/scss/main.scss -w styles/css/style.css"
```

3. If You Don't Have a `package.json` in Your Project:

- Run `npm i` to install `node-sass` dependency

4. Run `npm run sass` in the terminal

5. Open `html/index.html` in the browser and view colored fonts

6. Change a variable such as a color and save the file

7. Notice if scss compiled successfully

8. Refresh the html and verify it changes

9. Delete `html` directory

10. Import `styles/css/style.css` into your main project file

## Customization :art:

- Update and add variables to `/abstract/_variables.scss`
- Any newly added `.scss` files should be imported into `main.scss`

## Directory Tree :deciduous_tree:

```bash
├─ styles/
│  ├─ sass/
│  │  ├─ abstract/
│  │  │  ├─ _variables.scss
│  │  │  ├─ _mixins.scss
│  │  │  ├─ _animations_.scss
│  │  │  ├─ _mediaqueries_.scss
│  │  ├─ base/
│  │  │  ├─ _base.scss
│  │  │  ├─ _typography.scss
│  │  ├─ layout/
│  │  │  ├─ _header.scss
│  │  │  ├─ _footer.scss
│  │  ├─ components/
│  │  ├─ pages/
│  │  │  ├─ _home.scss
│  │  ├─ main.scss
│  ├─ css/
│  │  ├─ style.css
```

---

## Contact :telephone_receiver:

### Darian Nocera

**Email:** [hello@dariannocera.com](mailto:hello@dariannocera.com)

[![Dev](https://img.shields.io/badge/dev.to-0A0A0A?style=for-the-badge&logo=dev.to&logoColor=white)](https://dev.to/darnocer) [![Github](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https:/.github.com/darnocer) [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/darian-nocera)

---

#### Copyright &copy; 2020 [Darian Nocera](https://www.darnocer.io)
