# Shokhrukh Sharapov

## Contact me

---

- +1(347)216-4511
- [Email](mailto:shoxruxsharapov@gmail.com)
- [LinkedIn](https://www.linkedin.com/in/shokhrukh-sharapov/)
- [Telegram](https://t.me/shoxruxsharapov)
- [GitHub](https://github.com/sharapovshoxrux)

## About

---

A highly-motivated and hardworking individual. Recently finished Associate Degree in ASA College and completed a Foundation Course in The University of Westminster. Currently student at Western Governors University. Practical work experience in IT company Newmax Technologies.

## Other Information

---

- **Programming skills** | HTML5, CSS3, JavaScript, JQuery, ReactJS, Bootstrap, C#(Basics), MySQL
- **Certificates** | Member of ASIS&T, Member of Phi Theta Kappa, Certificates of Full Stack Development and React Boot-camp
- **Softwares** | Visual Basic, Micorosof Office, Adobe Photoshop, Dreamweaver

## Code Examples

---

```JavaScript
const poll = {
  question: 'What is your favourite programming language?',
  options: ['0: Javascruipt', '1: Python', '2: Rust', '3: C++'],
  answers: new Array(4).fill(0),
  registerNewAnswer() {
    const answer = Number(
      prompt(
        `${this.question}\n ${this.options.join('\n')} \n (Write option number)`
      )
    );
    console.log(answer);

    typeof answer === 'number' &&
      answer < this.answers.length &&
      this.answers[answer]++;

    this.displayResults();
    this.displayResults('string');
  },
  displayResults(type = 'array') {
    if (type === 'array') {
      console.log(this.answers);
    } else if (type === 'string') {
      console.log(`Poll results are ${this.answers.join(', ')}`);
    }
  },
};
```

## Experience

---

**Newmax Technologies** | IT Department

**University Hackathon**

**University Projects**

## Education

---

**University of Westminter** | Foundation Course

**ASA College** | Associate Degree

**Western Governors University** | Bachelors Degree(Current)

## Languases

---

**Uzbek** | Native / Bilingual Proficiency

**Russian** | Native / Bilingual Proficiency

**English** | Full Professional Proficiency
