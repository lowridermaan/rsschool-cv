# **Alexander Kharckevich**

---

### _Contacts_

---

1. [GitHub](https://lowridermaan.github.io)
2. [Codewars](https://www.codewars.com/users/lowridermaan)

---

### _About Me_

---

_Aspiring web developer, self-studying JavaScript, TypeScript, and Next.js while balancing with a primary job. Proactively advancing my programming skills, tackling challenges independently, and eager to join a team to work on an engaging project that will deepen my knowledge and strengthen my teamwork abilities._

---

#### _Skills_

---

JS, TS, Next.js, React, TanStack, CSS (SCSS, tailwind, etc.), HTML, have a basic understanding of backend development.

---

##### Code Examples

> # Task from codewars. You live in the city of Cartesia where all roads are laid out in a perfect grid. You arrived ten minutes too early to an appointment, so you decided to take the opportunity to go for a short walk. The city provides its citizens with a Walk Generating App on their phones -- everytime you press the button it sends you an array of one-letter strings representing directions to walk (eg. ['n', 's', 'w', 'e']). You always walk only a single block for each letter (direction) and you know it takes you one minute to traverse one city block, so create a function that will return true if the walk the app gives you will take you exactly ten minutes (you don't want to be early or late!) and will, of course, return you to your starting point. Return false otherwise.

```
function isValidWalk(walk) {

  let blocks = {
    n:0,
    s:0,
    w:0,
    e:0
  }

  if(walk.length===10){
      walk.forEach(w=> {
      blocks[w]++
  })

    return blocks.n - blocks.s === 0 && blocks.w - blocks.e === 0 ? true : false
  }

  return false

}

```
