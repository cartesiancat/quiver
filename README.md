# quiver
A graphical editor for commutative diagrams that exports to tikz-cd.

## Features
- An intuitive graphical interface for creating and modifying commutative diagrams.
- Support for objects, morphisms, natural transformations.
- tikz-cd (LaTeX) export.
- Shareable links.
- Smart label alignment and edge offset.
- Parallel (shifted) arrows.
- Arrow styles, including:
    - Dashed and dotted edges.
    - Maps to arrows.
    - Monomorphisms and epimorphisms.
    - Inclusions.
    - Pullbacks and pushouts.
    - Adjunctions.
    - Equality.
    - Harpoons.
    - Squiggly arrows.
- Multiple selection.
- A history system with undo and redo.
- Panning.

## Building
Make sure you have [installed yarn](https://yarnpkg.com/lang/en/docs/install/).

Clone the repository. Run:
```
make
```
Open `src/index.html` in your favourite web browser.

If that doesn't work, [open an
issue](https://github.com/varkor/quiver/issues/new) detailing the problem.

<blockquote>
<details>
<summary>__Common errors:__ "There are no scenarios; must have at least one."</summary>

__Solution:__ [uninstall `cmdtest`](https://yarnpkg.com/lang/en/docs/install/#debian-stable).
</details>
</blockquote>

## Screenshots
The interface:

![image](https://user-images.githubusercontent.com/3943692/50499043-fd45be80-0a3d-11e9-8fdf-fabeb5476334.png)

Parallel arrows:

![image](https://user-images.githubusercontent.com/3943692/50520129-7aad1580-0ab6-11e9-93f8-3981af4f5e37.png)

Natural transformations:

![image](https://user-images.githubusercontent.com/3943692/50520158-a7f9c380-0ab6-11e9-932e-08d22bd8f125.png)

Adjunctions:

![image](https://user-images.githubusercontent.com/3943692/50531538-7c50fa80-0b03-11e9-9d94-f859395e340f.png)
