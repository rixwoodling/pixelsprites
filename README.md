# Procedural Pixel Sprite Generation

A collection of small Python scripts that progressively build a procedural pixel sprite generator, from random symmetry to DNA-driven character generation.

## Requirements

- Python 3
- Pillow

```bash
pip install pillow
```

## Scripts

| Script | Description |
|--------|-------------|
| `one.py` | Random mirrored sprite generation |
| `four.py` | Introduces sprite DNA (head, body, eyes, horns) |
| `five.py` | Mutation system |
| `six.py` | Two-frame walking animation |
| `seven.py` | Simple species-based generator |
| `eight.py` | Procedural species with DNA and controlled asymmetry |
| `nine.py` | General-purpose procedural character randomizer |
| `ten.py` | Silhouette-first character generator |
| `eleven.py` | Improved silhouette generator with cleaner anatomy |
| `thirteen.py` | Enhanced limb attachment and sprite anatomy |

## Run

```bash
python3 one.py
python3 eight.py
python3 eleven.py
```

Each script generates a PNG in the current directory.

## License

MIT
