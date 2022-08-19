>" If You want to make an omlate,
> 
>    keep a chicken nearby.
>   
>    Consider a pan. "

```typescript

interface Programmer 
{
  title     : string;
  stack     : string[];
  languages : string[];
}

class Human implements Programmer 
{
  
  public alias       : string;
  
  constructor (
    public title     : string, 
    public stack     : string[],
    public languages : string[]
  ) 
  { 
    this.title     = title;
    this.stack     = stack;
    this.languages = languages;
  }
 
  main(): string {
    return "Hello, World";
  }
  
};

const Programmer = new Programmer();

Programmer.alias = "1x0λ7k/r";

Programmer.title = "Snr. Software Engineer";

Programmer.stack = [
  "Solidity", 
  "GraphQL", "Node", 
  "React Native", "React",
];

Programmer.languages = [
  "bash", "C", "C#", "C++",
  "lua", "PHP", "Sql", "Go",
  "TypeScript", "Javascript"
];

