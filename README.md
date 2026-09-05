<div align="center">

# Alexander Wiebe

**B.Sc. Computer Science · TU Berlin**

Beginner programmer and software developer. Learning through practical experience.

[![Email](https://img.shields.io/badge/alexanderwiebe.98%40gmail.com-0d1117?style=flat&logo=gmail&logoColor=f85149)](mailto:alexanderwiebe.98@gmail.com)
[![Location](https://img.shields.io/badge/Berlin%2C%20Germany-0d1117?style=flat&logo=googlemaps&logoColor=388bfd)](https://maps.app.goo.gl/Berlin)

</div>

---

## About

I am a Computer Science student at TU Berlin, and fairly early in all of this.
Most of what I actually know, I learned by building something, breaking it, and
then figuring out why it broke.

My bachelor's thesis was a control and testing interface for robot arms in Unity
and ROS 2, designed to work with any manipulator that ships a URDF description and
implemented and tested on the Franka Panda. It covers motion planning with MoveIt 2
and OMPL, trajectory execution, gripper control and a C#/Python bridge, and takes
user-written Python scripts as the workload. I wrote a pick-and-place routine as
the reference example.

These days I mostly build small things, on my own or together with a friend:
interactive 3D scenes with React Three Fiber and Three.js, website templates,
small visualisations of algorithms I wanted to understand properly. The 3D work
turned out to be a nice surprise, because the same problems I met in simulation
(geometry, camera control, level of detail, frame budgets) show up again in the
browser, just with far less performance to spend.

I use AI coding assistants every day, for pair programming, code review and quick
prototyping. I treat generated code the way I treat any other contribution: read
it, verify it, and rewrite whatever does not hold up. It speeds me up, it does not
think for me.

Right now I am generally trying to find my footing in this field.

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

### Forest Road

<div align="center">

[![Forest Road preview](assets/forest-road.gif)](https://3d-forest-road.vercel.app/)

[![Open live demo](https://img.shields.io/badge/OPEN%20LIVE%20DEMO-a371f7?style=for-the-badge&logo=vercel&logoColor=white&labelColor=1f9e7a)](https://3d-forest-road.vercel.app/)

</div>

An interactive night forest scene, built as a 3D site menu. Procedural terrain driven by a height function, 2600 instanced spruce trees rendered in one draw call with a GPU wind shader, positional audio synthesized entirely in the Web Audio API without a single sound file, and a graphics quality switch that scales render resolution and post-processing for weaker machines.

![TypeScript](https://img.shields.io/badge/TypeScript-3178c6?style=flat&logo=typescript&logoColor=white)
![Three.js](https://img.shields.io/badge/Three.js-049ef4?style=flat&logo=threedotjs&logoColor=white)
![React Three Fiber](https://img.shields.io/badge/R3F-61dafb?style=flat&logo=react&logoColor=0d1117)
![GLSL](https://img.shields.io/badge/GLSL-990000?style=flat&logo=webgl&logoColor=white)
![Web Audio](https://img.shields.io/badge/Web%20Audio%20API-f0883e?style=flat&logoColor=white)

### Bachelor's Thesis: Universal Robot Control Interface

![Bachelor's Thesis preview](assets/robotic-simulation.gif)

A control and testing interface for robot arms, built against a manipulator's URDF description rather than against one specific robot, so a new arm can be loaded from its own URDF. Implemented and tested on the Franka Panda. Motion planning through MoveIt 2 and OMPL, full gripper control, and a C#/Python bridge connecting Unity to ROS 2. Tasks are driven by Python scripts on the ROS side; a pick-and-place routine ships as the reference example.

![C#](https://img.shields.io/badge/C%23-512bd4?style=flat&logo=csharp&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776ab?style=flat&logo=python&logoColor=white)
![ROS 2](https://img.shields.io/badge/ROS%202-2f74c0?style=flat&logo=ros&logoColor=white)
![MoveIt 2](https://img.shields.io/badge/MoveIt%202-1f9e7a?style=flat&logoColor=white)
![Unity](https://img.shields.io/badge/Unity-e6edf3?style=flat&logo=unity&logoColor=0d1117)

### Coastal Guesthouse Template

<div align="center">

[![Coastal Guesthouse preview](assets/screenshot-desktop.jpg)](https://coastal-guesthouse-template.vercel.app/)

[![Open live demo](https://img.shields.io/badge/OPEN%20LIVE%20DEMO-a371f7?style=for-the-badge&logo=vercel&logoColor=white&labelColor=3068b7)](https://coastal-guesthouse-template.vercel.app/)

</div>

A bilingual booking site for a small hotel, built as a reusable template. Server-side i18n with next-intl and no locale flash, a custom availability engine that matches guests to room combinations and prices them by season, accessible dialogs and forms validated with Zod.

![TypeScript](https://img.shields.io/badge/TypeScript-3178c6?style=flat&logo=typescript&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-e6edf3?style=flat&logo=nextdotjs&logoColor=0d1117)
![Tailwind](https://img.shields.io/badge/Tailwind-38bdf8?style=flat&logo=tailwindcss&logoColor=0d1117)
![shadcn/ui](https://img.shields.io/badge/shadcn%2Fui-e6edf3?style=flat&logo=shadcnui&logoColor=0d1117)
![next-intl](https://img.shields.io/badge/next--intl-1f9e7a?style=flat&logoColor=white)
![Zod](https://img.shields.io/badge/Zod-3068b7?style=flat&logo=zod&logoColor=white)

<div align="center">

![Lighthouse report](assets/lighthouse.jpg)
<sub>Lighthouse audit, production build via PageSpeed Insights</sub>

</div>

### Algorithms and numerical methods

| Repository                                                                              | What it demonstrates                                                                                                                                                                        |
| --------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [**sorting-algorithms**](https://github.com/wiebe-alexander/sorting-algorithms)         | Bubble, selection, insertion, merge, quick and heap sort in C, with animated GIFs rendered by a Python recorder. The architecture keeps the C algorithms free of any graphics dependencies. |
| [**pathfinding-algorithms**](https://github.com/wiebe-alexander/pathfinding-algorithms) | BFS, Dijkstra, Greedy Best-First and A* on a grid, plus RRT and RRT* in continuous space. Rendered to GIFs using only the JDK. The same family of sampling-based planners that OMPL uses inside MoveIt.    |
| [**numerical-methods**](https://github.com/wiebe-alexander/numerical-methods)           | Interpolation (Runge phenomenon, cubic splines), FFT from scratch against an O(N²) DFT, and gradient descent / Newton on the Rosenbrock function. All verified against NumPy references.    |
