```ts
export class Info {

  name: string = 'Lucas Sampaio';
  age: number = 20;
  nationality: string = 'Brazilian';
  languages: Record<string, string>[] = [{ 'English': 'B1' }, { 'Portuguese': 'native' }];
  occupation: string = 'Full Stack Web Developer at Soon Assistance';
  freetime: string[] = ['Playing video games', 'Watching movies' ,'Reading', 'Hanging out with friends'];

}

export class Programming {

  languages: string[] = ['JavaScript', 'TypeScript', 'Java'];
  frontend: string[] = ['React.js', 'Redux', 'Redux Saga', 'Bootstrap', 'Ant Design'];
  backend: string[] = ['Node.js', 'Express.js', 'Nest.js', 'Spring Boot'];
  testing: string[] = ['Jest', 'React Testing Library', 'Msw', 'Supertest'];
  devops: string[] = ['Docker', 'Kibana', 'Elastic Search', 'Fluentd', 'AWS']
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
