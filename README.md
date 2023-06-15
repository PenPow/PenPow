```typescript
export default class PenPow extends Student {
  constructor(config) {
    super(config);
    
    this.languages = ['typescript','python'];
    
    this.projects = {
      Sentry: 'A Discord Moderation Bot',
    }
    
    this.os = 'Windows 11'; // TODO: Migrate to Linux Mint
    this.server = 'Hetzner';
  }
}
```
