<div align="center">
  <h1>Egor Romanov (Junior Frontend Dev) CV</h1>
</div>

## Personal Information
*Name*: **Egor Romanov**  
*Date of birth:* **24.04.1997**  
### *Contacts:*  
* ***Telegram***: https://t.me/EgoRomanoff  
* ***E-mail***: egoromanoff@mail.ru  
* ***Discord***: Egor Romanov (@EgoRomanoff)

## About myself
I'm Junior Frontend Dev.  
I have been in this field for about 2 years. I manly study independently, so I have **no problems with mastering new technologies**. I am **plodding**, **punctual** and **try to obtain the best result of my work**.

I have no commercial developing experience, but I strive to learn all the subtleties of frontend in order to become a qualified specialist.

## Special Skills
* *JavaScript (ES6+)*
* *React.js*
* *HTML (HTML5)*
* *CSS (CSS3)*
* *SASS (SCSS)*
* *Git*
* *BEM*
* *Figma*
## Code Example
CodeWars kata [***'Hidden "Cubic" numbers'***](https://www.codewars.com/kata/55031bba8cba40ada90011c4)
```javascript
function isSumOfCubes(s) {

  let cubicNumbers = s
    .match(/\d{1,3}/g)
    .filter(elem => {
      return (
        elem.split('').reduce((res, cur) => {
          return (res += Math.pow(+cur, 3))
        }, 0) === +elem
      )
    })
    .map(n => +n)

  let sumOfCubicNumbers = cubicNumbers
    .reduce((prev, cur) => (prev += cur), 0)

  return cubicNumbers.length === 0 ?
    `Unlucky` :
    `${cubicNumbers.join(' ')} ${sumOfCubicNumbers} Lucky`
}
```
## Work experience
* [**I Must Do (React.js)**](https://github.com/EgoRomanoff/i-must-do-react) - simple Web TODO-application.  
**Stack**: *JavaScript, React.js, CSS(SCSS)*
* [**Web Calc**](https://github.com/EgoRomanoff/web-calc) - non-framework simple Web calculator with unique design.  
* **Stack**: *HTML, CSS(SCSS), JavaScript*
* [**Grow Be**](https://github.com/EgoRomanoff/growbe_landing) - adaptive cross-browser landing-page.  
* **Stack**: *HTML, CSS(SCSS), JavaScript*
* [**Greenfield**](https://github.com/EgoRomanoff/volga-it)- promo site, task of the qualifying stage of the online Olympiad "Volga-IT'20"  
* **Stack**: *HTML, CSS(SCSS), JavaScript (jQuery)*
## Education
* ***Bunin Yelets State University***  
Institute of Mathematics, natural sciences and technology  
**Bachelor's degree** in *Computer Science and Computer Engineering*  
(2017-2021)
* ***"Udemy" online-platform***  
Course *"JavaScript 2021 - A Complete Guide from Scratch to the Pros"*  
(2021)
## Languages
* *Russian* - **native**
* *English* - **B1 (pre-intermidiate)**
