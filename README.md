# onlycss
Modern CSS framework built ONLY with pure css. No bullshit!


**NPM Installation**
```sh
npm install --save onlycss
```

**USAGE**

You can use any one of the below methods to import the core framework or any part of it.

> 1. Import through Javascript
```js
import "~onlycss/variables.css";
import "~onlycss/only.css";
```

> 2. Import through CSS
```css
@import "~onlycss/variables.css";
@import "~onlycss/only.css";
```
### Structure
```
Sizes: xs, sm, md, lg, xl, xxl
Colors: default, alpha, beta, gamma
```

The css is dynamic which means same set of classes can have different effects based on the other classes they are used with. But they will always mean the same thing i.e. `alpha` will always represent color whereas `lg` will always represent size.

Examples: 
1. `lg` class on a text will increase the font size whereas when `lg` class is used in combination with `btn` then it will increase both the button size as well as the font size.
2. `alpha` will change the color of text but when used with `btn`, it will change the colors of button.

### Features
| Feature       | We Say        
|:------------- |:----------------------------------------------------------------------------- |
| Modular       | Just import what you want.                                                    |
| Flexbox Based | Isn't it normal? Yes, we also use flexbox. Everybody does.                    |
| Customizable  | Only using pure css variables. We are not being **sass**y about it ;)           |


### Ideology

* We **do not** support no code movement. We think everyone should know how to write css if they are working with frontend.
* The purpose of the core framework is to provide you with only the **usual** css required to build a complete website from scratch.
* For special cases that depends on site to site, we recommend writing your own css classes. Framework is fully customizable so overriding the variables for the respective custom class should do the trick in most cases.
* The concept of CSS variables is used in such a way that you can customize the entire framework by just configuring a few variables.