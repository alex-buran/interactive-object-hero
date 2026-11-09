# MATTER · Interactive Object Hero · Landing Page Concept

**▶ Live demo: https://alex-buran.github.io/interactive-object-hero/**

A landing page concept for a design studio, built around a procedurally
generated 3D object you can pick up and turn. Drag to rotate it, scroll to
pull the camera in. There are no downloaded models and no textures.

## What it does

- **Procedural object.** An icosahedron with every vertex pushed out along
  its normal by layered noise, so it reads as an organic rock or gem rather
  than a perfect solid.
- **Drag with inertia.** Letting go keeps the object spinning and slowing
  down naturally instead of stopping dead.
- **Idle auto-rotate.** It starts turning again a couple of seconds after
  you stop interacting.
- **Scroll-linked camera.** The camera dollies in and the object grows as
  you move down the page.
- **Two-mesh material.** A solid Phong mesh with a slightly larger
  low-opacity wireframe shell, for a faceted, technical look without
  environment maps.
- **Readable by composition.** The object sits off to one side of the frame
  so it never covers the text, with no overlay needed.
- **Interaction details.** Custom cursor with a "drag" label over the
  object, magnetic buttons, staggered section reveals, and a preloader.

## Tech

- One self-contained `index.html`, no build step
- Three.js (r128, from cdnjs): procedural geometry, Phong lighting
- Vanilla HTML / CSS / JavaScript
- Google Fonts (Fraunces, Inter)
- Responsive layout

## Design & build

Designed and built by **[Softburn.tech](https://softburn.tech)**.
