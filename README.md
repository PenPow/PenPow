```typescript
export default class PenPow extends Programmer implements BadCode {
  constructor(config) {
    super(config);
    
    this.nerd = true;
    this.goodCode = false;
    
    this.languages = ['typescript','javascript','python'];
    
    this.projects = {
      Signal: 'A Discord bot coded in Javascript (and eventually typescript), that does everything, but terribly',
    }
    
    this.os = 'Ubuntu';
    this.server = 'PC from 2006';
  }
}
```
