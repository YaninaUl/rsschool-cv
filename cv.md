# Yanina Ulasavets
<img src="https://t3.ftcdn.net/jpg/03/29/36/40/240_F_329364028_wVuGGblS5BxfbbQYiPMZzpzOuAYUBkzx.jpg" alt="avatar" width="150">


## Junior FE Developer 

### Contact information:
**E-mail:** <yulasavets@gmail.com> <br>
**GitHub:** @yaninaul <br>
**Discord:** Yanina(YaninaUl)


### About me
Senior QA Engineer with more than 7 years of experience, looking for new challenges. <br>
Multitasking, hardworking, self-dependence, responsible, team-player.

### Development skills
- HTML5
- CSS (+ Bootstrap framework)
- JavaScript (basic knowledge)
- Java(basic knowledge)
- Version control system - Git
- Editors: Codepen, CodeSandBox, VSCode, Intellij IDEA.

### Code example from Weather appllication from SheCodes course - [GitHub repository](https://github.com/YaninaUl/weather-application)
*Function for showing current date and time:*
```javascript
let now = new Date();
let dayNumber = now.getDay();
let days = [
  "Sunday",
  "Monday",
  "Tuesday",
  "Wednesday",
  "Thursday",
  "Friday",
  "Saturday",
];
let day = days[dayNumber];
let hours = now.getHours();
if (hours < 10) {
  hours = `0${hours}`;
}
let minutes = now.getMinutes();
if (minutes < 10) {
  minutes = `0${minutes}`;
}

let currentDate = document.querySelector("#current-date");

function showDayAndTime(day, hours, minutes) {
  currentDate.innerHTML = `${day} ${hours}:${minutes}`;
}
showDayAndTime(day, hours, minutes);
```
### Experience in dev
- Successfully completed SheCodes Web Development workshop. <br> Link to the final project - [Weather app.](https://endearing-marzipan-6146bd.netlify.app/)
- Minor experience with BDD automation testing.   

### Courses
- **SheCodes** "Web Development" course (completed).<br> [Certificate](https://drive.google.com/file/d/18JmOoOa9SDC9Esl3NLV37QylyS8gXTXX/view?usp=sharing)<br>
- **RedRover** "FrontEnd" course (in progress). <br>
- **RS School** "JavaScript/FrontEnd. Stage 1" course (in progress). 

### Languages
- Russian, Belarusian - Native <br>
- Polish - B1 (certificate) <br>
- English - B2+ (according to the Epam internal certification)
