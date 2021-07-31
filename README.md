```typescript
export default class PenPow extends Programmer {
  constructor(config) {
    super(config);
    
    this.nerd = true;
    this.goodCode = false;
    
    this.languages = ['typescript','javascript','python'];
    
    this.projects = {
      Signal: 'A Discord bot coded in Javascript (and eventually typescript), that does everything, but terribly',
      Discordo: 'An in development Discord API wrapper',
    }
    
    this.os = 'Ubuntu';
    this.server = 'PC from 2006';
  }
}
```
