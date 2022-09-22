```typescript
export default class PenPow extends Programmer {
  constructor(config) {
    super(config);
    
    this.languages = ['typescript','nim','python'];
    
    this.projects = {
      Sentry: 'A sort of abandoned moderation bot i was working on',
    }
    
    this.os = ['Ubuntu', 'Windows 11'];
    this.server = 'OVH Dedicated Server ✨';
  }
}
```
