```typescript

interface Programmer {
  title     : string;
  alias     : string;
  stack     : string[];
  languages : string[];
}

class Human implements Programmer {
  
  public alias     : string;
  
  constructor(
    public title     : string, 
    public stack     : string[],
    public languages : string[],
  ) 
  { 
    this.title     = title;
    this.stack     = stack;
    this.languages = languages;
  }
  
  
  
  main() {
    console.log("Hello, World");
  }
}

const Programmer = new Programmer();

Programmer.alias = "1x0λ7k/r";

Programmer.title = "Snr. Software Engineer";



Programmer.stack = [
  "React", "React Native", 
  "GraphQL", "Node", "Solidity"
];

Programmer.languages = [
  "Go", "C", "C#", "C++",
  "TypeScript", "Javascript", 
  "lua", "bash", "PHP", "Sql"
];

