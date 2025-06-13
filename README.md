# naqs_devices_TektronixTDS

## Directory structure

```text

└── naqs_devices_TektronixTDS/
    ├── .gitignore
    ├── pyproject.toml
    ├── README.md
    ├── LICENSE.txt
    ├── CITATION.cff
    ├── docs/
    │   ├── conf.py
    │   ├── make.bat
    │   ├── Makefile
    │   └── index.rst
    └── src/naqs_devices/ # note: must be same as in the parent naqs_devices repo to be in the same namespace
        └── TektronixTDS/
            ├── __init__.py
            ├── blacs_tabs.py
            ├── blacs_workers.py
            ├── labscript_devices.py
            └── register_classes.py

```

## How to document your device

To work within the labscript paradigm, we enforce that you write all
specification related documentation in the top-level README.md (here). Then,
any API related documentation should go in the `docs/index.rst`.
