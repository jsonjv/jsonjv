```typescript
interface Profile {
  pronouns: string;
  code: string[];
  technologies: {
    frontend: { [key: string]: string[] };
    backend: { [key: string]: string[] };
    databases: string[];
    serverless: string[];
    misc: string[];
  };
  architecture: string[];
  funFact: string;
}

const jason: Profile = {
  pronouns: 'He' || 'Him',
  code: ['JavaScript', 'Go', 'PHP', 'Python'],
  technologies: {
    frontend: {
      js: ['TypeScript', 'React', 'Redux', 'Redux-Saga'],
      css: ['Tailwind CSS', 'Bootstrap'],
    },
    backend: {
      js: ['Node', 'Express'],
      go: ['Revel'],
      php: ['Laravel'],
      python: ['Flask'],
    },
    databases: ['MySQL', 'MongoDB', 'Amazon DynamoDB'],
    serverless: ['Amazon S3', 'AWS Lambda'],
    misc: ['Docker', 'Vim'],
  },
  architecture: ['MVC', 'Single-Page Application'],
  funFact: 'There are two ways to write error-free programs; only the third one works',
};
```
