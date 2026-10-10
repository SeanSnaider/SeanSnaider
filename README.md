# Hey, I'm Sean 👋

I'm a junior studying CS (Software Engineering concentration) at Northeastern University, currently on co-op at Vertex Pharmaceuticals building data migration tooling. I like building things that come out of my actual interests: I've been speedcubing for over a decade (6.14s single) and I play progressive and math rock guitar, and both keep turning into engineering projects.

## What I've Built

🎸 **[BellyDSP](https://github.com/SeanSnaider/BellyDSP)**: A free, open-source guitar amp simulator for Mac and Windows ([bellydsp.com](https://bellydsp.com)). Neural amp models, a cab with movable mics, a full pedalboard, and Match Tone, which separates the guitar from a song with Demucs and searches the app's own gear to get close to that tone. I hand-built a Rust prototype, then directed Claude Code agents to rebuild it in C++20 under strict rules: the audio thread never allocates memory or waits on locks (a test checks every feature), about 7,200 automated tests, and a 50-case benchmark that decides which tone-matching changes ship. Built with C++20, JUCE, Neural Amp Modeler, Python, CMake, and GitHub Actions.

🧊 **[Rubik's Cube Solver](https://github.com/SeanSnaider/RubiksCubeProject)**: Solves any scramble in 20 moves or fewer in under a second, using Kociemba's two-phase algorithm implemented from the papers. Includes a CSS 3D cube and a WCA-style timer, and it's used by 10+ peers for timed solves. Started as a Pygame capstone built with **TheCubicle.com**, then rebuilt as a full-stack web app with React, TypeScript, FastAPI, and MongoDB.

🎼 **[Guitar Learning Tool](https://github.com/SeanSnaider/Guitar-Scale-Tool)**: An interactive fretboard trainer with under 10ms audio latency via the Web Audio API, 40+ scale patterns (modes, pentatonics, jazz), and three adaptive practice modes. Built with React, TypeScript, Zustand, and Tailwind.

🏛️ **Student Government Association: Internal Tools**: Replaced spreadsheet-based attendance and voting with a full-stack web app used by 50+ members across 20+ meetings per semester. Built with Next.js, TypeScript, Prisma, and PostgreSQL.

## What I'm Working On Now

🎛️ **BellyDSP v0.2**: Eight amps, about 4x lower CPU use, and a tone matcher that cut its error 31% on a held-out benchmark.

🧩 **Optimal Rubik's cube solver in Rust**: Korf's algorithm (IDA* with pattern databases), written entirely by hand.

## Links

- 🌐 [seansnaider.com](https://seansnaider.com)
- 💼 [LinkedIn](https://linkedin.com/in/seansnaider)
- 📫 <sean@snaider.com>
