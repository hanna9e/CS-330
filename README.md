# CS 330: Computational Graphics and Visualization

My final project for CS 330 at SNHU is a C++/OpenGL 3D scene recreating a 2D reference photo with basic shapes, textures, lighting, and camera navigation.

**Contents:** 3D Scene ZIP (full Visual Studio project) and the Design Decisions document.

## Reflection

### How do I approach designing software?

This project taught me to design by decomposition. I broke my reference image into simple shapes, like a [mug] as a cylinder plus a torus, which turned an overwhelming scene into small tasks. I planned in Milestone One, proved the plan with one complex object in Milestone Two, then layered on textures, lighting, and controls. Planning first and validating one piece before scaling up is something I already use at work and will keep using.

### How do I approach developing programs?

I built the scene incrementally inside the `SceneManager` class, separating textures, materials, lighting, and rendering so adding an object took only a few lines. Iteration drove everything: adjust a value, run, look, repeat. Lighting took the most rounds. [Add one specific fix here.] By the end, I could predict results before running them because I understood transformation order and the coordinate system, and I committed working versions before risky changes.

### How can computer science help me in reaching my goals?

This course made the linear algebra from MAT 350 practical. That will help in future courses and in my interest in biomedical informatics, where visualizing data like 3D medical imaging matters. Professionally, understanding the rendering pipeline gives me better intuition about what the browser does in my Firefox work, and visualization skills carry over to building clear dashboards for experiment data.
