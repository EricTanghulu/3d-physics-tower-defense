# 3D Physics-Based Tower Defense

This is a Python + Panda3D 3D physics-based tower defense prototype. Towers apply impulses to knock spherical enemies off the path before they reach the goal.

## Project Layout

```
3d-physics-tower-defense/
├── .gitignore
├── README.md
├── requirements.txt
├── src/
│   └── physics_tower_defense_3d.py
└── models/
    └── smiley.egg.pz
```

## Setup

1. Create & activate a virtual environment  
2. Install dependencies:  
   ```bash
   pip install -r requirements.txt
   ```

## Run

```bash
python src/physics_tower_defense_3d.py
```

## Customization

- Tweak spawn interval, forces, paths in the code.  
- Swap or add models under \`models/\`.

## License

MIT © 2025 Eric Tang
