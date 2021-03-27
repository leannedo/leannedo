## Hi there 👋 I'm Leanne Do - [The Right Brain Dev](https://www.facebook.com/naophaidicode) 👩‍💻

[![Linkedin: leannedo](https://img.shields.io/badge/-@leanndo-0077B5?style=flat-square&labelColor=0077B5&logo=LinkedIn&link=https://www.linkedin.com/in/leanndo/)](https://www.linkedin.com/in/leanndo/)
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
    computer: ['javascript', 'typescript'],
    human: ['vietnamese', 'english', 'german', 'finnish'],
  },
  technologies: {
    frontEnd: ['react', 'redux', 'gatsby', 'webpack', 'babel', 'css3', 'bootstrap', 'html5'],
    backEnd: ['nodejs', 'graphql'],
    mobileApp: ['react-native'],
    database: ['mongodb', 'postgresql'],
    devOps: ['docker', 'kubernetes'],
    testing: ['jest', 'jasmine'],
    misc: ['git', 'linux', 'heroku', 'netlify' ]
},
  applications: ['single-page', 'jam-stack', 'server-side rendering'],
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
- [What is Internet and How It Works](http://www.therightbraindev.com/how-internet-works)
- [Learning Programming is Never a Straight Road](http://www.therightbraindev.com/no-straight-road-learning-programming)
- [Git and GitHub 123](http://www.therightbraindev.com/git-and-github)
- [It is OK to fail test cases](http://www.therightbraindev.com/ok-to-fail)
- [Code’nLearn 2: Separate UI from logic and the main program](http://www.therightbraindev.com/Java-separation-of-concern)
<!-- BLOG-POST-LIST:END -->

### 📖 My books feast
- The Full Stack Developer by Chris Northwood 🥢
- Frontend Architecture for Design Systems by Micah Godbolt 🥢
- Soft skills - The software developer's life manual by John Z. Sonmez 🥢
- Mastering Modular Javascript by Nicolas Bevacqua 🍲
- Clean Code by Robert C. Martin 🍲
- Programming Typescript by Boris Cherny 🍲

### 🛠️ My toolbox

<a href="#" alt="javascript"><code><img height="25" src="https://github.com/blackcater/blackcater/raw/master/images/logo-javascript.svg"></code></a>
<a href="#" alt="typescript"><code><img height="25" src="https://github.com/blackcater/blackcater/raw/master/images/logo-typescript.svg"></code></a>
<a href="#" alt="nodejs"><code><img height="25" src="https://github.com/blackcater/blackcater/raw/master/images/logo-nodejs.svg"></code></a>
<a href="#" alt="nodejs"><code><img height="25" src="https://raw.githubusercontent.com/leannedo/leannedo/main/images/react.svg"></code></a>
<a href="#" alt="nodejs"><code><img height="25" src="https://raw.githubusercontent.com/leannedo/leannedo/main/images/redux.svg"></code></a>
<a href="#" alt="nodejs"><code><img height="25" src="https://raw.githubusercontent.com/leannedo/leannedo/main/images/graphql.svg"></code></a>
<a href="#" alt="nodejs"><code><img height="25" src="https://raw.githubusercontent.com/leannedo/leannedo/main/images/webpack.svg"></code></a>
<a href="#" alt="nodejs"><code><img height="25" src="https://raw.githubusercontent.com/leannedo/leannedo/main/images/gatsbyjs.svg"></code></a>
<a href="#" alt="nodejs"><code><img height="25" src="https://raw.githubusercontent.com/leannedo/leannedo/main/images/git.svg"></code></a>
<a href="#" alt="nodejs"><code><img height="25" src="https://raw.githubusercontent.com/leannedo/leannedo/main/images/java.svg"></code></a>
<a href="#" alt="nodejs"><code><img height="25" src="https://raw.githubusercontent.com/leannedo/leannedo/main/images/mongodb.svg"></code></a>
<a href="#" alt="nodejs"><code><img height="25" src="https://raw.githubusercontent.com/leannedo/leannedo/main/images/docker.svg"></code></a>






