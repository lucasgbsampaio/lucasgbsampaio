```ts
export class Info {

  name: string = 'Lucas Sampaio';
  age: number = 19;
  nationality: string = 'Brazilian';
  languages: Record<string, string>[] = [{ 'English': 'B1' }, { 'Portuguese': 'native' }];
  occupation: string = 'Full Stack Web Developer at Soon Assistance';
  freetime: string[] = ['Playing video games', 'Watching movies' ,'Reading', 'Hanging out with friends'];

}

export class Programming {

  languages: string[] = ['JavaScript', 'TypeScript'];
  frontend: string[] = ['React.js', 'Redux', 'Redux Saga', 'Bootstrap', 'Ant Design'];
  backend: string[] = ['Node.js', 'Express.js', 'Nest.js', 'TypeORM', 'Sequelize'];
  testing: string[] = ['Jest', 'React Testing Library', 'Msw', 'Supertest'];
  infra: string[] = ['Serverless', 'AWS'];
  databases: string[] = ['PostgreSQL', 'MongoDB'];

}

export class Social {

  github: string = 'lucasgbsampaio';
  twitter: string = 'lucasgbsampaio';
  linkedin: string = 'lucasgbsampaio';
  discord: string = 'lucasgbsampaio#6231';
  email: string = 'lucasgbsampaio@outlook.com';

}
```
