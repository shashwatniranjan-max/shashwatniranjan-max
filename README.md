```javascript
const developer = {
  name: "Your Name",
  role: "Aspiring Full Stack Web Developer",
  focus: ["Node.js", "Express.js", "MongoDB", "React", "TypeScript"],
  primaryGoal: "Google Summer of Code 2026"
};

function main() {
  console.log(`Hello, I'm ${developer.name}.`);
  console.log(`I am currently mastering: ${developer.focus.join(', ')}.`);
  console.log(`My next major milestone is ${developer.primaryGoal}!`);
}

main();

