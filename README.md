# typescript-cheat-sheet

### TypeScript: 
TypeScript is an open-source, object-oriented language developed and maintained by Microsoft, licensed under Apache 2 license.

**type / additional feature + javascript = TypeScript**

### How to Setup

#### Download and install node
***check node installed or not:*** node --version

#### Install typescript
***Global:*** npm install -g typescript\
***Local:*** npm install -save-dev typescript\
***Check install or not:*** tsc --version

### How to Run it

***This one will convernt TS to JS:*** tsc fileName.ts\
***If we want to monitor TS change Realtime then:*** tsc fileName.ts --watch

## Variable in TS:

```typescript
let name: string = 'Sumiya Alam Akhi'; //String type
let id: number = 2345;  //Number type
let isValued: boolean = false;  //boolean type
let address: any = 'Dhaka'  //any type
let employeeList: any[] = ['sumiya', 423]; //array any type
let employeeList: (string| number)[] = ['sumiya', 423]; // Unit type

```
## Data Types - user-defined

```typescript
let id: string | number | boolean;

id = 11;  //no error 
id = '11' //no error
id = true  //no error
```

## Function in TS:

```typescript
function add (a: number , b: number){
  console.log (a+b)
}
add(12,13) // 25

add(12,'13') // error

```

## Object in TS:

```typescript
let student: object; 
let student: {name: string, id:number}; 
let student: {name: string, id?:number}; //? sign for keep optional 
let students: object[]; //For store arry of object 

````








