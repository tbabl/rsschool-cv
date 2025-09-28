# Tamari Bablidze

<br> **_Email:_** tamari.bablidze@gmail.com
<br> **_Phone_:** +995598277209
<br> **_GitHub:_** [github.com/tbabl](https://github.com/tbabl)

<br>

## 👩‍💻 Self-introduction

Motivated and detail-oriented **Junior Frontend Developer** with strong foundations in HTML, CSS (SCSS/Bootstrap/TailwindCSS), and JavaScript, who wants to create something useful with professionalism, creativity, and passion. In the future, I plan to deepen my knowledge of frontend development with Angular, and on the backend, I am interested in learning Node.js and Python. I am also passionate about web design. I believe that my skills—such as quick learning, determination, diligence, and curiosity—will help me achieve a high level of proficiency in these areas.

<br>

## 🛠 Skills

- **Languages:** JavaScript (ES6+), HTML5, CSS3 (SASS/SCSS)
- **Frameworks & Libraries:** Bootstrap, TailwindCSS, jQuery
- **Version Control:** Git, GitHub
- **Tools & Workflow:** VS Code, Chrome DevTools, npm

<br>

## 💻 Code Examples

```js
/**
 * TASK: Given an unsorted array of 3 positive integers [ n1, n2, n3 ], determine if it is possible to form a Pythagorean Triple using those 3 integers.
 * NOTE: A Pythagorean Triple satisfies: a² + b² = c²
 *
 * TODO: implement the isPythagoreanTriple function:
 * @param {number[]} arr - Array of 3 positive integers
 * @returns {boolean} - true if a Pythagorean Triple can be formed, otherwise - false
 */

function isPythagoreanTriple(integers) {
  // Validate input
  if (!Array.isArray(integers) || integers.length !== 3) {
    throw new TypeError(
      "isPythagoreanTriple function requires an array of exactly 3 elements"
    );
  }

  // Check if all elements are positive integers
  if (
    integers.some(
      (num) =>
        typeof num !== "number" ||
        !Number.isInteger(num) ||
        !Number.isFinite(num) ||
        num <= 0
    )
  ) {
    throw new TypeError(
      "isPythagoreanTriple requires an array of 3 positive integers"
    );
  }

  // Sort the array to ensure c is the largest
  const [a, b, c] = integers.sort((x, y) => x - y);

  // Check if a² + b² = c²
  return a * a + b * b === c * c;
}
```

<br>

## 💼 Work Experience

At this stage, my work experience in programming is limited to several small projects and three complex projects completed during my learning process. You will soon be able to explore these projects on my existing
[GitHub account](https://github.com/tbabl). In addition, I'm actively planning several personal projects to further enhance my skills and portfolio.

## 🎓 Education

- **_MSc in Business Administration (Major - ICT Management, academic leave)_** – Ivane Javakhishvili Tbilisi State University, 2019–present

- **_BSc in Business Administration_** – Ivane Javakhishvili Tbilisi State University, 2019

### 👩‍💻 Courses & Training:

- _CS50's Introduction to Computer Science_ – HarvardX (ongoing)
- _Front-end web programming_– IT Academy STEP Georgia, 2022 April–October

<br>

## 🌍 English Language

- **Level:** B1+ (Intermediate)
- **Practice:**
  - Daily technical documentation reading.
  - Practice speaking skills on learning platforms.
  - Search, analyze and write summaries about every field of my interests.
