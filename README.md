### Hi there 👋

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
