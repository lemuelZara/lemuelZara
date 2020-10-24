<img src="https://www.flaticon.com/svg/static/icons/svg/3079/3079112.svg" width="300px" align="right"/>

```typescript
import { Bio, Skills } from '@dev';

const bio = Bio.config({
  name: 'Lemuel Coelho Zara',
  title: 'Desenvolvedor Frontend Jr',
  city: 'Meridiano',
  state: 'São Paulo',
});

const skills = Skills.config({
  languages: ['Javascript'],
  databases: ['PostgreSQL', 'MongoDB'],
  frameworks: ['Node.js', 'React.js'],
  os: ['Linux', 'Windows'],
});
```
