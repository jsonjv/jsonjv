```typescript
interface Profile {
  pronouns: string[];
  code: string[];
  technologies: {
    frontend: { [key: string]: string[] };
    backend: { [key: string]: string[] };
    databases: string[];
    apis: string[];
    cloud: { [key: string]: string[] };
    misc: string[];
  };
  architectures: string[];
  funFact: string;
}

const jason: Profile = {
  pronouns: ['He', 'Him'],
  code: ['JavaScript', 'Go', 'PHP'],
  technologies: {
    frontend: {
      js: ['TypeScript', 'React', 'Redux'],
      css: ['Tailwind CSS', 'shadcn/ui'],
      testing: ['Jest', 'Cypress'],
    },
    backend: {
      js: ['Node', 'Express'],
      go: ['Revel'],
      php: ['Laravel'],
    },
    databases: ['MySQL', 'MongoDB', 'Amazon DynamoDB'],
    apis: ['REST'],
    cloud: {
      aws: ['Amazon S3', 'AWS Lambda'],
    },
    misc: ['Docker', 'Vim'],
  },
  architectures: ['Microservices', 'Monolithic'],
  funFact: 'There are two ways to write error-free programs; only the third one works. — Alan J. Perlis',
};
```
