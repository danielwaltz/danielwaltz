```typescript
const getLanguages = () => [
  'CSS',
  'GraphQL',
  'HTML',
  'JavaScript',
  'TypeScript',
];

const getFrameworks = () => [
  'React',
  'React Native',
  'Next.js',
  'Svelte',
  'Vue',
];
  
const getHobbies = () => [
  'Coffee',
  'Music',
  'Programming',
  'Video Games',
];

const createProfile = (name: string) => {  
  const languages = getLanguages();
  const frameworks = getFrameworks();
  const hobbies = getHobbies();
  
  return {
    name,
    languages,
    frameworks,
    hobbies,
  }
};

export const daniel = createProfile('Daniel Waltz');
```

<a href="https://github-readme-stats.vercel.app/api?username=loftwah&theme=tokyonight&show_icons=true">
  <img align="left" src="https://github-readme-stats.vercel.app/api?username=danielwaltz&theme=tokyonight&show_icons=true" />
</a>

<a href="https://github-readme-stats.vercel.app/api/top-langs/?username=loftwah&theme=tokyonight">
  <img align="left" src="https://github-readme-stats.vercel.app/api/top-langs/?username=danielwaltz&theme=tokyonight" />
</a>
