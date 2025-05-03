## Hi there 👋
![Logo](https://raw.githubusercontent.com/HuynhND22/HuynhND22/refs/heads/main/huynhnd.gif)

```javascript
const Self = Object.freeze({
    name: "Nguyen Duc Huynh",
    dob: new Date("2002-01-22"),
    passions: Object.freeze([
        "🎸 Playing the guitar and crafting melodies",
        "🎱 Mastering the art of billiards",
        "🎮 Immersing in the world of games"
    ]),
    profession: "Developer"
});

const introduceSelf = ({ name, dob, passions, profession }) => {
    return `
    🌟 Hello, world! I am ${name}.
    🗓️ Born on ${dob.toDateString()}.
    🎨 Passions:
    ${passions.map((p, i) => `   ${i + 1}. ${p}`).join("\n")}

    🏛️ Current Role: ${profession}.
    `;
};

const epicStory = introduceSelf(Self);
console.log(epicStory);

```
<!-- <picture>
  <source
    media="(prefers-color-scheme: dark)"
    srcset="https://raw.githubusercontent.com/platane/snk/output/github-contribution-grid-snake-dark.svg"
  />
  <source
    media="(prefers-color-scheme: light)"
    srcset="https://raw.githubusercontent.com/platane/snk/output/github-contribution-grid-snake.svg"
  />
  <img
    alt="github contribution grid snake animation"
    src="https://raw.githubusercontent.com/platane/snk/output/github-contribution-grid-snake.svg"
  />
</picture> -->
