## Hi there 👋 I'm Leanne Do - [The Right Brain Dev](https://www.facebook.com/naophaidicode) 👩‍💻

[![Linkedin: leannedo](https://img.shields.io/badge/-@leannedo-0077B5?style=flat-square&labelColor=0077B5&logo=LinkedIn&link=https://www.linkedin.com/in/leannengocdo)](https://www.linkedin.com/in/leannengocdo)
[![Facebook: naophaidicode](https://img.shields.io/badge/-@naophaidicode-0077B5?style=social&labelColor=0077B5&logo=facebook&link=https://www.linkedin.com/in/leanndo/)](https://www.facebook.com/naophaidicode)
[![Website: therightbraindev](https://img.shields.io/badge/-therightbraindev-A5E5B0?style=flat-square&amp;labelColor=A5E5B0&amp;logo=gatsby&amp;link=http://www.therightbraindev.com/)](http://www.therightbraindev.com)

<br>

```typescript
interface Me {
  [key: string]: Repertoire |  string[]
}

interface Repertoire {
  [key: string]: string[]
}

const me: Me = {
  language: {
    computer: ['kotlin', 'javascript', 'typescript', 'java'],
    human: ['vietnamese', 'english', 'german', 'finnish'],
  },
  technologies: {
    frontEnd: ['react', 'redux', 'gatsby', 'webpack', 'css3', 'html5'],
    backEnd: ['kotlin', 'nodejs', 'restapi', 'spring', 'spring boot'],
    mobileApp: ['react-native'],
    database: ['postgresql'],
    devOps: ['docker', 'kubernetes'],
    testing: ['kotest', 'junit', 'jest', 'react-testing-library'],
    misc: ['git', 'linux', 'heroku', 'netlify' ]
},
  outside_work: ['hand-lettering', 'writing-blog', 'cat-slave', 'food-addict'],
}

export const getToKnowMe = (repertoire: string) => {
  if (!repertoire) {
    throw new Error('Please specify what you want to know about me!')
  }

  if (!me[repertoire]) {
    throw new Error(`Missing ${repertoire} in my toolbox. Will work on that!`)
  }

  return me[repertoire];
}
```


<h2 style="display: flex; align-items: center;"> A few more facts <img src="https://media.giphy.com/media/cCvWHbfVdn2bm/giphy.gif" width="80" style="margin-left: 30px"></h2> 

### 🍣 I have a thing for salmon 🤤

### 🤟 I love writing!

### 📝 My recent blogs
<!-- BLOG-POST-LIST:START -->
- [Be present and own your work](http://www.therightbraindev.com/be-present-own-your-work)
- [Prep our brain for the coding journey](http://www.therightbraindev.com/prep-brain-for-coding)
- [What do we need to know about slices in Golang?](http://www.therightbraindev.com/slices-golang)
- [What is Internet and How It Works](http://www.therightbraindev.com/how-internet-works)
- [Learning Programming is Never a Straight Road](http://www.therightbraindev.com/no-straight-road-learning-programming)
<!-- BLOG-POST-LIST:END -->

### 📖 My books feast
- The Full Stack Developer by Chris Northwood 🥢
- Frontend Architecture for Design Systems by Micah Godbolt 🥢
- Soft skills - The software developer's life manual by John Z. Sonmez 🥢
- Mastering Modular Javascript by Nicolas Bevacqua 🍲
- Clean Code by Robert C. Martin 🍲
- Programming Typescript by Boris Cherny 🍲

### 🛠️ My toolbox

<a href="#" alt="javascript"><code><img height="25" src="https://raw.githubusercontent.com/leannedo/leannedo/main/images/javascript.png"></code></a>
<a href="#" alt="typescript"><code><img height="25" src="https://raw.githubusercontent.com/leannedo/leannedo/main/images/typescript.png"></code></a>
<a href="#" alt="nodejs"><code><img height="25" src="https://raw.githubusercontent.com/leannedo/leannedo/main/images/node.png"></code></a>
<a href="#" alt="nodejs"><code><img height="25" src="https://raw.githubusercontent.com/leannedo/leannedo/main/images/react.svg"></code></a>
<a href="#" alt="nodejs"><code><img height="25" src="https://raw.githubusercontent.com/leannedo/leannedo/main/images/redux.svg"></code></a>
<a href="#" alt="nodejs"><code><img height="25" src="https://raw.githubusercontent.com/leannedo/leannedo/main/images/graphql.svg"></code></a>
<a href="#" alt="nodejs"><code><img height="25" src="https://raw.githubusercontent.com/leannedo/leannedo/main/images/webpack.svg"></code></a>
<a href="#" alt="nodejs"><code><img height="25" src="https://raw.githubusercontent.com/leannedo/leannedo/main/images/gatsbyjs.svg"></code></a>
<a href="#" alt="nodejs"><code><img height="25" src="https://raw.githubusercontent.com/leannedo/leannedo/main/images/git.svg"></code></a>
<a href="#" alt="nodejs"><code><img height="25" src="https://raw.githubusercontent.com/leannedo/leannedo/main/images/java.svg"></code></a>
<a href="#" alt="nodejs"><code><img height="25" src="https://raw.githubusercontent.com/leannedo/leannedo/main/images/mongodb.svg"></code></a>
<a href="#" alt="nodejs"><code><img height="25" src="https://raw.githubusercontent.com/leannedo/leannedo/main/images/docker.svg"></code></a>






