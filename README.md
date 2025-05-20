#  simple minecraft





# 🧱Minecraft-Style Block Builder (Python + Ursina)

A simple first-person block builder game inspired by Minecraft, built using the [Ursina game engine](https://www.ursinaengine.org/). Move freely in a 3D environment, place and destroy blocks, and shape your own terrain!

---

##  Features

-  20x20 base world made of grassy cubes
-  First-person movement with mouse and keyboard
-  Place blocks using left-click
-  Destroy blocks using right-click
-  Skybox added for visual depth

---

##  Controls

| Key / Mouse          | Action                |
|----------------------|-----------------------|
| `W` / `A` / `S` / `D`| Move forward/left/back/right |
| `Mouse`              | Look around           |
| `Spacebar`           | Jump                  |
| `Left Mouse Button`  | Place a block         |
| `Right Mouse Button` | Destroy a block       |
| `Esc`                | Exit game             |

---

##  Requirements

- Python 3.x
- Ursina game engine

---

##  Installation & Running

### 1. Install Ursina

```bash
pip install ursina
````

### 2. Save the Game Code

Save the provided Python code in a file, e.g., `main.py`.

### 3. Run the Game

```bash
python main.py
```

---

##  Project Structure

```
/block-builder
├── main.py         # Game logic
├── grass.png       # Block texture (optional)
└── README.md       # You're reading it!
```

> Make sure the `grass.png` file is in the same folder as `main.py`. You can use any 64x64 grass texture image.

---

##  How It Works

* The game creates a 20x20 grid of cubes using nested loops.
* `FirstPersonController` allows free movement in first-person.
* The `input()` function checks if a block is hovered when clicking:

  * Left-click adds a new cube in the clicked direction.
  * Right-click removes the hovered cube.

---

screenshot: ![Image](https://github.com/user-attachments/assets/43a3e55f-01ed-4765-881c-cf09b4a5678a)


