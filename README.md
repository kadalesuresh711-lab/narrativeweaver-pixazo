# Pixazo Narrative Enhancer

Clone this open source public GitHub repo and build project here fully working.

Make sure add all api keys secure never exposed them



https://github.com/kadalesuresh711-lab/pixazo-narrative-gen.git



I improved the first-attempt image quality, but one piece is still unfinished.



Done:

- Pictures now render at the highest detail setting the image service allows (double the previous), which visibly cleans up faces, hands and composition.

- The instruction sent for each picture is now much shorter and denser. The long version was diluting the actual story moment, which is why images looked nice but showed the wrong thing.

- All "no speech bubbles / no writing / no duplicates" style wording was rewritten as positive descriptions, because this image model cannot understand "no" — naming those things was actually putting them into the pictures.



Unfinished and untested: while checking the final instruction text, I found a real bug — when a character sheet is in use, the app wrongly decides "no people are in this scene", so it drops the character descriptions and even adds "empty location, scenery only" to a scene with two people in it. That alone would explain a large share of your wrong images. I had just located it and had not fixed or retested it when credits ran out.



Continuing that fix, plus a live test run, needs available credits.



Pixazo api key 1

03178ba869a446eba82bce98a79fefc3



Pixazo api key 2

048e52aee2094e24bad1b46a0fb15753



Pixazo api key 3



d004a01679f843e7ba090fa1d88c926d



Pixazo api key 4

9379183b074f4655adc0fa351dd4fa29



Pixazo api key 5

07a04ea573384e7ba4d315ec54614564



Pixazo api key 6

93712b1c39b74b46badcba75086de162



Pixazo api key 7

30d389fc68f14aeb89c0daa9c20052bb



Pixazo api key 8

45a16e9666b0466d87993d6a1a526038



Pixazo api key 9

7aebfdf0e3b1408bb69a7b1baf070ccc



Pixazo api key 10

24f1c82b7a2d4419ba4684105600238f



 Z.ai api key use best and free model only:-

60a6a43db42446c9885c54c1a7ee4f8a.RqGTVeAWBDnUHbjR

This project was built with [Lovable](https://lovable.dev).

## Build with Lovable

Continue developing this project in the [Lovable editor](https://lovable.dev/projects/5f77b26c-a1b0-4318-b038-a914a5b6060a).

- **Ship faster**: describe what you want to build and Lovable handles the code.
- **Stay in sync**: every change made in Lovable is committed straight to this repository.
- **Full ownership**: this code is yours. Push to `main` on GitHub and your changes sync back into Lovable, ready for your next prompt.

## Development

Prefer working locally? You need Node.js and npm — [install with nvm](https://github.com/nvm-sh/nvm#installing-and-updating).

```sh
git clone <this-repository-url>
cd <repository-name>
npm i
npm run dev
```
