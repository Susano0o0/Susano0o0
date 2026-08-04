<div align="center">

# Alexander Wiebe

**B.Sc. Computer Science · TU Berlin**

Robotics simulation, motion planning and full-stack web development.
Building things at the intersection of ROS 2, Unity and the browser.

[![Email](https://img.shields.io/badge/alexanderwiebe.98%40gmail.com-0d1117?style=flat&logo=gmail&logoColor=f85149)](mailto:alexanderwiebe.98@gmail.com)
[![Location](https://img.shields.io/badge/Berlin%2C%20Germany-0d1117?style=flat&logo=googlemaps&logoColor=388bfd)](https://maps.app.goo.gl/Berlin)

</div>

---

## About

I am a Computer Science B.Sc. student at TU Berlin with a background in robotics simulation and software engineering. My bachelor's thesis was a universal robot control interface in Unity and ROS 2 for pick-and-place automation across three real robot arms (Franka Panda, Kinova Gen3, UR5e), covering the full pipeline from motion planning with MoveIt 2 and OMPL down to gripper control and a C#/Python bridge.

Lately most of my building happens in the browser: interactive 3D scenes with React Three Fiber and Three.js, where the same problems I met in simulation (geometry, camera control, level of detail, frame budgets) show up again, just with a much smaller performance budget.

I work with AI coding assistants as a daily part of my workflow, for pair programming, code review and rapid prototyping. I treat generated code the way I treat any other contribution: read it, verify it, and rewrite whatever does not hold up.

---

## Tech stack

**Robotics and simulation**

![ROS 2](https://img.shields.io/badge/ROS%202-0d1117?style=flat&logo=ros&logoColor=22314E&labelColor=0d1117&color=388bfd)
![MoveIt 2](https://img.shields.io/badge/MoveIt%202-0d1117?style=flat&logoColor=white&color=388bfd)
![Unity](https://img.shields.io/badge/Unity-0d1117?style=flat&logo=unity&logoColor=white&color=388bfd)

**Real-time 3D**

![Three.js](https://img.shields.io/badge/Three.js-0d1117?style=flat&logo=threedotjs&logoColor=white&color=a371f7)
![React Three Fiber](https://img.shields.io/badge/React%20Three%20Fiber-0d1117?style=flat&logo=react&logoColor=white&color=a371f7)
![WebGL](https://img.shields.io/badge/WebGL%20%2F%20GLSL-0d1117?style=flat&logo=webgl&logoColor=white&color=a371f7)

**Languages**

![C](https://img.shields.io/badge/C-0d1117?style=flat&logo=c&logoColor=white&color=3fb950)
![C#](https://img.shields.io/badge/C%23-0d1117?style=flat&logo=csharp&logoColor=white&color=3fb950)
![Java](https://img.shields.io/badge/Java-0d1117?style=flat&logo=openjdk&logoColor=white&color=3fb950)
![Python](https://img.shields.io/badge/Python-0d1117?style=flat&logo=python&logoColor=white&color=3fb950)
![TypeScript](https://img.shields.io/badge/TypeScript-0d1117?style=flat&logo=typescript&logoColor=white&color=3fb950)
![JavaScript](https://img.shields.io/badge/JavaScript-0d1117?style=flat&logo=javascript&logoColor=white&color=3fb950)
![SQL](https://img.shields.io/badge/SQL-0d1117?style=flat&logo=postgresql&logoColor=white&color=3fb950)

**Web and frontend**

![React](https://img.shields.io/badge/React-0d1117?style=flat&logo=react&logoColor=white&color=e3b341)
![Next.js](https://img.shields.io/badge/Next.js-0d1117?style=flat&logo=nextdotjs&logoColor=white&color=e3b341)
![Vue.js](https://img.shields.io/badge/Vue.js-0d1117?style=flat&logo=vuedotjs&logoColor=white&color=e3b341)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-0d1117?style=flat&logo=tailwindcss&logoColor=white&color=e3b341)
![Node.js](https://img.shields.io/badge/Node.js-0d1117?style=flat&logo=nodedotjs&logoColor=white&color=e3b341)

**Tools**

![Linux](https://img.shields.io/badge/Linux-0d1117?style=flat&logo=linux&logoColor=white&color=8b949e)
![Git](https://img.shields.io/badge/Git-0d1117?style=flat&logo=git&logoColor=white&color=8b949e)
![Vite](https://img.shields.io/badge/Vite-0d1117?style=flat&logo=vite&logoColor=white&color=8b949e)
![Vercel](https://img.shields.io/badge/Vercel-0d1117?style=flat&logo=vercel&logoColor=white&color=8b949e)

---

## Projects

### Real-time 3D on the web

|                                                                                                                                                                                                                                                                                                                                                                                                             |                                                  |
| ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------ |
| **Forest Road** · [live demo](https://forest-road.vercel.app)                                                                                                                                                                                                                                                                                                                                               | React Three Fiber + Three.js + TypeScript        |
| An interactive night forest scene used as a 3D site menu. Procedural terrain with a single height function shared by ground, road and props, a road ribbon draped over that terrain, 2600 instanced spruces in one draw call with a GPU wind shader, positional audio synthesized entirely in the Web Audio API (no audio files), and a graphics quality switch that scales resolution and post-processing. | `TypeScript` `Three.js` `R3F` `GLSL` `Web Audio` |

### Robotics

|                                                                                                                                                               |                                          |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------- |
| **Bachelor's Thesis: Universal Robot Control Interface**                                                                                                      | Unity + ROS 2 + MoveIt 2                 |
| Universal pick-and-place interface for Franka Panda, Kinova Gen3 and UR5e. Motion planning via OMPL, full gripper control and a C#/Python Unity-ROS 2 bridge. | `C#` `Python` `ROS 2` `MoveIt 2` `Unity` |

### Algorithms and numerical methods

| Repository                                                                                  | What it demonstrates                                                                                                                                                                    |
| ------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [**sorting-visualizer-c**](https://github.com/Susano0o0/sorting-visualizer-c)               | Bubble, selection, insertion, merge, quick and heap sort in C, with animated GIFs rendered by a Python recorder. Architecture keeps the C algorithms free of any graphics dependencies. |
| [**pathfinding-visualizer-java**](https://github.com/Susano0o0/pathfinding-visualizer-java) | BFS, Dijkstra, Greedy Best-First and A* on a grid, plus RRT and RRT* in continuous space. Rendered to GIFs using only the JDK. Direct connection to the planners inside MoveIt/OMPL.    |
| [**numerical-methods-python**](https://github.com/Susano0o0/numerical-methods-python)       | Interpolation (Runge phenomenon, cubic splines), FFT from scratch vs O(N²) DFT, and gradient descent / Newton on the Rosenbrock function. All verified against NumPy references.        |

---

## What I use most

<div align="center">

![Top languages](https://github-readme-stats.vercel.app/api/top-langs/?username=wiebe-alexander&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=388bfd&text_color=e6edf3&layout=compact&langs_count=8)

</div>

---

## Languages

🇩🇪 German C1 &nbsp; 🇬🇧 English C1 &nbsp; 🇷🇺 Russian Native
