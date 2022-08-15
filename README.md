```typescript

interface Programmer {
  title : string;
  alias : string;
  stack : string[];
}

class Human implements Programmer {
  constructor(
    public title     : string, 
    public alias     : string, 
    public stack     : string[],
    public languages : string[],
  ) 
  { 
    this.title     = title;
    this.alias     = alias;
    this.stack     = stack;
    this.languages = languages;
  }
  
  main() {
    console.log("Hello, World");
  }
}

const Programmer = new Programmer();

Programmer.title = "Snr. Software Engineer";

Programmer.alias = "1x0λ7k/r";

Programmer.stack = [
  "React", "React Native", 
  "GraphQL", "Node", "Solidity"
];

Programmer.languages = [
  "Go", "C", "C#", "C++",
  "TypeScript", "Javascript", 
  "lua", "bash", "PHP", "Sql"
];
