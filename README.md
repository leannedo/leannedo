<h3 style="color:#a5e5b0">Hi there 👋 I'm Leanne Do - The Right Brain Dev 👩‍💻</h3>

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
<h5 style="color:#a5e5b0">My books feast</h5>
<li style="list-style-type: none">The Full Stack Developer by Chris Northwood 🥢</li>
<li style="list-style-type: none">Frontend Architecture for Design Systems by Micah Godbolt 🥢</li>
<li style="list-style-type: none">Soft skills - The software developer's life manual by John Z. Sonmez 🥢</li>
<li style="list-style-type: none">Clean Code by Robert C. Martin 🍲</li>
<li style="list-style-type: none">Programming Typescript by Boris Cherny 🍲</li>







