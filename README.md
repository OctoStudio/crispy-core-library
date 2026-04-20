# CrispyCore Library

Official workout programs for [CrispyCore](https://crispy-core.com) — an iOS workout player and timer that imports programs directly from public GitHub repositories.

## Programs

| Folder | Program |
|--------|---------|
| `calimove-level-1` | Calimove – Level 1 |
| `calimove-level-2` | Calimove – Level 2 |
| `calimove-level-3` | Calimove – Level 3 |
| `knee-ability-zero` | Knee Ability Zero |
| `posture-balance` | Posture & Balance |

Browse and import these programs from the [CrispyCore Library](https://crispy-core.com/library.html).

## Importing into the app

1. Open CrispyCore on your iPhone
2. Tap **Import**
3. Paste a URL — either this repo's root (`https://github.com/OctoStudio/crispy-core-library`) or a direct link to any folder inside it

The app fetches the JSON files, validates them, and installs the program. When a new version is pushed, the app can detect and pull the update automatically.

## Program format

Each program is a folder containing:

```
my-program/
├── program.json       # Program definition (required)
├── workouts/
│   ├── 1A.json
│   └── 1B.json
└── exercises.json     # Exercise info (optional)
```

Full format documentation: [crispy-core.com/docs.html](https://crispy-core.com/docs.html)

You can also build your own programs visually using the [Program Builder](https://crispy-core.com/builder.html).
