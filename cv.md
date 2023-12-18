# MASLENKOV  VLADIMIR
---
## CONTACTS INFO
* __Location:__ Almaty, Kazakhstan
* __E-Mail:__ maslenkov.vladimir@gmail.com
* __Phone Number:__ +7 (747) 403-92-65
* __Discord:__ Volodya13 #7432
* __GitHub:__ @Volodya13
  
---
## ABOUT ME
Hello everyone! My name's Vladimir and I'm 38. I like music, pets and kind pleasant people. I've been   working as a screen-printer for the last 8 years and now I'm working on full-stack(junior) position in at the local web-applications developing studio. Also I am continue my self-study to improve my skills. Because I'm going to get advanced level for this. I live in Kazakhstan, Almaty city. I'm taking several courses such as "RSSchool Frontend Dev." and "Udemy: WEB-Dev and Java Script + React" to become a strong and confident front-end developer. I'd like to work to create something unusual(for example I have the serveral ideas to create web-apps for pets and right now we're working on conception for this with my muse). And I really sure that I'll have been reached for my aim definitely.
---
## MY EDUCATION
* Accounting a finance (unfinished college)
* RSSchool Front-end Dev. (in progress)
* Udemy: WEB-Dev and Java Script + React (in progress)
---
## SKILLS
###### Soft Skills:
* Sociability
* Creativity
* Perseverance
* Team Work
* Time Management
* Optimization of workflow
###### Hard Skills(Basic):
* HTML
* CSS(Stylus, Sass, Scss)
* Bootstrap,Tailwind(are basically)
* JavaScript
* CMS: "Bitrix: Site Management"
* GULP
* Web-pack
* JQuery, React(are basically)
* PHP (1S: Site Management, Bitrix Framework(basically))
* Git / GitHUB
* Figma
* CorelDRAW
* Adobe PhotoShop
---
## CODE EXAMPLE
```JavaScript
//used class to construct the componentns by menu-card template
class MenuCard {
        constructor(src, name, description, price, parentName, className) {
            this.name = name;
            this.src = src;
            this.description = description;
            this.price = price;
            this.parent = document.querySelector(parentName);
            this.className = className;
        }

        render() {
            const menuCard = document.createElement('div');

            menuCard.classList.add('menu_card');
            menuCard.innerHTML = `
                <div class="menu_card-img">
                    <img src=${this.src} alt="menu-card-pic">
                </div>
                <div class="menu_card-descr">
                    <h3 class="menu_card-title">${this.name}</h3>
                    <div class="menu_card-text">${this.description}</div>
                    <div class="menu_card-price">$${this.price}</div>
                </div>`;

            this.parent.append(menuCard);
            return menuCard;
        }
    }
```
---
## LANGUAGES
* __English:__ A2 (Pre-Intermediate)
* __Russian:__ Native
* __Kyrgyz:__ Elementary
* __Kazakh:__ Beginner
---
