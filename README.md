# WASM experiments

# Pyodide Package Audit

| type | id | name | version/range | status | notes | extra_info |
| --- | ---: | --- | --- | --- | --- | --- |
| meta | 1 | Audit Ref | Pyodide Package Audit | Master | master reference | emscripten/Pyodide compatibility |
| meta | 2 | Channel Target | Python 3.11 | Info | emscripten-forge/Pyodide channel | compare vs minimal bundle |
| meta | 3 | Minimal Bundle | Python 3.13 | Info | custom minimal bundle | path: `assets/pyodide-minimal/`; target: `pyodide_2025_0_wasm32` |

| type | id | name | version/range | status | notes | extra_info |
| sum | 1 | Stats | Total packages | 201 | aggregate | unique packages audited |
| sum | 2 | Stats | Available in channel | 188 | aggregate | Avail: ✓ |
| sum | 3 | Stats | Not in channel | 13 | aggregate | Avail: ✗ |
| sum | 4 | Stats | Curated set | 44 | aggregate | Curated: Y |
| sum | 5 | Stats | Transitive dep tags | 3 | aggregate | dep/dep? markers |
| sum | 6 | Stats | In minimal bundle | 56 | aggregate | Min: ✓ |

## Packages (201)

| type | id | name | version/range | status | notes | extra_info |
| --- | ---: | --- | --- | --- | --- | --- |
| pkg | 1 | affine | >=2.4.0,<3 | Avail: ✓ | Pure Python | Curated: N; Channel: 2.4.0; Min: ✗ |
| pkg | 2 | aiohttp | >=3.13.2,<4 | Avail: ✓ | Bundled | Curated: Y; Channel: 3.13.3; Min: 3.11.13 |
| pkg | 3 | aiohappyeyeballs | >=2.6.1,<3 | Avail: ✓ | Bundled | Curated: Y; Channel: 2.6.1; Min: 2.6.1 |
| pkg | 4 | aiosignal | >=1.3.2,<2 | Avail: ✓ | Bundled | Curated: Y; Channel: 1.4.0; Min: 1.3.2 |
| pkg | 5 | altair | >=5.5.0,<7 | Avail: ✓ | Bundled | Curated: Y; Channel: 6.0.0; Min: 5.5.0 |
| pkg | 6 | anytree | >=2.13.0,<3 | Avail: ✓ | Pure Python | Curated: N; Channel: 2.13.0; Min: ✗ |
| pkg | 7 | argcomplete | >=3.6.3,<4 | Avail: ✓ | Pure Python | Curated: N; Channel: 3.6.3; Min: ✗ |
| pkg | 8 | arrow | >=1.3.0,<2 | Avail: ✓ | Pure Python | Curated: N; Channel: 1.4.0; Min: ✗ |
| pkg | 9 | asn1crypto | >=1.5.1,<2 | Avail: ✓ | Pure Python | Curated: N; Channel: 1.5.1; Min: ✗ |
| pkg | 10 | asttokens | >=3.0.0,<4 | Avail: ✓ | Pure Python | Curated: N; Channel: 3.0.1; Min: ✗ |
| pkg | 11 | astunparse | >=1.6.3,<2 | Avail: ✓ | Pure Python | Curated: N; Channel: 1.6.3; Min: ✗ |
| pkg | 12 | atomicwrites | >=1.4.1,<2 | Avail: ✓ | Pure Python | Curated: N; Channel: 1.4.1; Min: 1.4.1 |
| pkg | 13 | attrs | >=25.2.0,<26 | Avail: ✓ | Bundled | Curated: Y; Channel: 25.4.0; Min: 25.2.0 |
| pkg | 14 | autocommand | >=2.2.2,<3 | Avail: ✓ | Pure Python | Curated: N; Channel: 2.2.2; Min: ✗ |
| pkg | 15 | autograd | >=1.8.0,<2 | Avail: ✓ | Pure Python | Curated: N; Channel: 1.8.0; Min: ✗ |
| pkg | 16 | babel | >=2.17.0,<3 | Avail: ✓ | Pure Python | Curated: N; Channel: 2.17.0; Min: ✗ |
| pkg | 17 | backoff | >=2.2.1,<3 | Avail: ✓ | Pure Python | Curated: N; Channel: 2.2.1; Min: ✗ |
| pkg | 18 | backrefs | >=6.1,<7 | Avail: ✓ | Pure Python | Curated: N; Channel: 6.1; Min: ✗ |
| pkg | 19 | beartype | >=0.22.2,<0.23 | Avail: ✓ | Pure Python | Curated: N; Channel: 0.22.9; Min: ✗ |
| pkg | 20 | beautifulsoup4 | >=4.14.2,<5 | Avail: ✓ | Bundled | Curated: Y; Channel: 4.14.3; Min: 4.13.3 |
| pkg | 21 | bleach | >=6.2.0,<7 | Avail: ✓ | Pure Python | Curated: N; Channel: 6.3.0; Min: ✗ |
| pkg | 22 | blinker | >=1.9.0,<2 | Avail: ✓ | Pure Python | Curated: N; Channel: 1.9.0; Min: ✗ |
| pkg | 23 | branca | >=0.8.2,<1 | Avail: ✓ | Pure Python | Curated: N; Channel: 0.8.2; folium dep; Min: ✗ |
| pkg | 24 | brotli | >=1.1.0,<2 | Avail: ✓ | C ext; wheel | Curated: N; Channel: 1.1.0; Min: ✗ |
| pkg | 25 | burr | >=0.40.2,<0.41 | Avail: ✗ | Not in channel | Curated: N; Min: ✗ |
| pkg | 26 | bytecode | >=0.17.0,<1 | Avail: ✓ | Pure Python | Curated: N; Channel: 0.17.0; Min: ✗ |
| pkg | 27 | cachetools | >=5.5.2,<6 | Avail: ✓ | Pure Python | Curated: N; Channel: 5.5.2; Min: ✗ |
| pkg | 28 | certifi | >=2025.8.3,<2026 | Avail: ✓ | Bundled | Curated: Y; Channel: 2025.11.12; Min: 2025.8.3 |
| pkg | 29 | cffi | >=1.15.1,<2 | Avail: ✓ | C ext; wheel | Curated: N; Channel: 1.15.1; Min: 1.17.1 |
| pkg | 30 | cftime | >=1.6.2,<2 | Avail: ✓ | C ext; wheel | Curated: N; Channel: 1.6.4; Min: ✗ |
| pkg | 31 | chardet | >=5.2.0,<6 | Avail: ✓ | Pure Python | Curated: N; Channel: 5.2.0; Min: ✗ |
| pkg | 32 | click | >=8.3.0,<9 | Avail: ✓ | Pure Python | Curated: N; Channel: 8.3.1; Min: ✗ |
| pkg | 33 | cligj | >=0.7.2,<1 | Avail: ✓ | Pure Python | Curated: N; Channel: 0.7.2; Min: ✗ |
| pkg | 34 | cloudpickle | >=3.1.1,<4 | Avail: ✓ | Pure Python | Curated: N; Channel: 3.1.2; Min: ✗ |
| pkg | 35 | cmudict | >=1.1.3,<2 | Avail: ✓ | Pure Python | Curated: N; Channel: 1.1.3; Min: ✗ |
| pkg | 36 | colorama | >=0.4.6,<1 | Avail: ✓ | Pure Python | Curated: N; Channel: 0.4.6; Min: ✗ |
| pkg | 37 | coloredlogs | >=15.0.1,<16 | Avail: ✓ | Pure Python | Curated: N; Channel: 15.0.1; Min: ✗ |
| pkg | 38 | comm | >=0.2.3,<1 | Avail: ✓ | Pure Python | Curated: N; Channel: 0.2.3; Min: ✗ |
| pkg | 39 | cons | >=0.4.7,<1 | Avail: ✓ | Pure Python | Curated: N; Channel: 0.4.7; Min: ✗ |
| pkg | 40 | contourpy | >=1.3.1,<2 | Avail: ✓ | Bundled | Curated: Y; Channel: 1.3.1; Min: 1.3.1 |
| pkg | 41 | coverage | >=7.6.12,<8 | Avail: ✓ | C ext; wheel | Curated: N; Channel: 7.13.1; Min: ✗ |
| pkg | 42 | cryptography | >=42.0.2,<47 | Avail: ✓ | Bundled | Curated: Y; Channel: 42.0.2; Min: 46.0.1 |
| pkg | 43 | cssselect2 | >=0.8.0,<1 | Avail: ✓ | Pure Python | Curated: N; Channel: 0.8.0; Min: ✗ |
| pkg | 44 | cycler | >=0.12.1,<1 | Avail: ✓ | Bundled | Curated: Y; Channel: 0.12.1; Min: 0.12.1 |
| pkg | 45 | cython | >=3.2.4,<4 | Avail: ✓ | C ext; wheel | Curated: N; Channel: 3.2.4; Min: ✗ |
| pkg | 46 | decorator | >=5.2.1,<6 | Avail: ✓ | Bundled | Curated: Y; Channel: 5.2.1; Min: 5.2.1 |
| pkg | 47 | deepdiff | >=8.6.1,<9 | Avail: ✓ | Pure Python | Curated: N; Channel: 8.6.1; Min: ✗ |
| pkg | 48 | defusedxml | >=0.7.1,<1 | Avail: ✓ | Pure Python | Curated: N; Channel: 0.7.1; Min: ✗ |
| pkg | 49 | diskcache | >=5.6.3,<6 | Avail: ✓ | Bundled | Curated: Y; Channel: 5.6.3; Min: 5.6.3 |
| pkg | 50 | distro | >=1.9.0,<2 | Avail: ✓ | Pure Python | Curated: N; Channel: 1.9.0; Min: ✗ |
| pkg | 51 | docutils | >=0.21.2,<1 | Avail: ✓ | Pure Python | Curated: N; Channel: 0.22.4; Min: ✗ |
| pkg | 52 | dynaconf | >=3.2.11,<4 | Avail: ✗ | Not in channel | Curated: N; Min: ✗ |
| pkg | 53 | einops | >=0.8.1,<1 | Avail: ✓ | Pure Python | Curated: N; Channel: 0.8.1; Min: ✗ |
| pkg | 54 | etuples | >=0.3.10,<1 | Avail: ✓ | Pure Python | Curated: N; Channel: 0.3.10; Min: ✗ |
| pkg | 55 | exceptiongroup | >=1.2.2,<2 | Avail: ✓ | Bundled | Curated: Y; Channel: 1.3.1; Min: 1.2.2 |
| pkg | 56 | executing | >=2.2.0,<3 | Avail: ✓ | Pure Python | Curated: N; Channel: 2.2.1; Min: ✗ |
| pkg | 57 | fastcore | >=1.8.12,<2 | Avail: ✗ | Not in channel | Curated: N; Min: ✗ |
| pkg | 58 | folium | >=0.20.0,<0.21 | Avail: ✓ | Pure Python | Curated: N; Channel: 0.20.0; Min: ✗ |
| pkg | 59 | fqdn | >=1.5.1,<2 | Avail: ✓ | Pure Python | Curated: N; Channel: 1.5.1; Min: ✗ |
| pkg | 60 | frozenlist | >=1.6.0,<2 | Avail: ✓ | Bundled | Curated: Y; Channel: 1.7.0; Min: 1.6.0 |
| pkg | 61 | fsspec | >=2025.3.2,<2026 | Avail: ✓ | Pure Python | Curated: N; Channel: 2025.12.0; Min: ✗ |
| pkg | 62 | gast | >=0.7.0,<1 | Avail: ✓ | Pure Python | Curated: N; Channel: 0.7.0; Min: ✗ |
| pkg | 63 | geographiclib | >=2.1,<3 | Avail: ✓ | Pure Python | Curated: N; Channel: 2.1; Min: ✗ |
| pkg | 64 | great_tables | *(no ver)* | Avail: ✗ | Not in channel | Curated: N; Min: ✗ |
| pkg | 65 | h11 | >=0.14.0,<1 | Avail: ✓ | Pure Python | Curated: N; Channel: 0.16.0; Min: ✗ |
| pkg | 66 | h2 | >=4.3.0,<5 | Avail: ✓ | Pure Python | Curated: N; Channel: 4.3.0; Min: ✗ |
| pkg | 67 | hpack | >=4.1.0,<5 | Avail: ✓ | Pure Python | Curated: N; Channel: 4.1.0; Min: ✗ |
| pkg | 68 | html5lib | >=1.1,<2 | Avail: ✓ | Pure Python | Curated: N; Channel: 1.1; Min: ✗ |
| pkg | 69 | httpx | >=0.28.1,<1 | Avail: ✓ | Pure Python | Curated: N; Channel: 0.28.1; Min: ✗ |
| pkg | 70 | humanfriendly | >=10.0,<11 | Avail: ✓ | Pure Python | Curated: N; Channel: 10.0; Min: ✗ |
| pkg | 71 | hyperframe | >=6.1.0,<7 | Avail: ✓ | Pure Python | Curated: N; Channel: 6.1.0; Min: ✗ |
| pkg | 72 | idna | >=3.10,<4 | Avail: ✓ | Bundled | Curated: Y; Channel: 3.11; Min: 3.10 |
| pkg | 73 | imageio | >=2.37.0,<3 | Avail: ✓ | Pure Python | Curated: N; Channel: 2.37.0; Min: ✗ |
| pkg | 74 | inflect | >=7.5.0,<8 | Avail: ✓ | Pure Python | Curated: N; Channel: 7.5.0; Min: ✗ |
| pkg | 75 | iniconfig | >=2.1.0,<3 | Avail: ✓ | Bundled | Curated: Y; Channel: 2.3.0; Min: 2.1.0 |
| pkg | 76 | invoke | >=2.2.1,<3 | Avail: ✓ | Pure Python | Curated: N; Channel: 2.2.1; Min: ✗ |
| pkg | 77 | ipywidgets | >=8.1.7,<9 | Avail: ✓ | Available in channel with deps | Curated: N; Channel: 8.1.8; Min: ✗ |
| pkg | 78 | isodate | >=0.7.2,<1 | Avail: ✓ | Pure Python | Curated: N; Channel: 0.7.2; Min: ✗ |
| pkg | 79 | isoduration | >=20.11.0,<21 | Avail: ✓ | Pure Python | Curated: N; Channel: 20.11.0; Min: ✗ |
| pkg | 80 | itsdangerous | >=2.2.0,<3 | Avail: ✓ | Pure Python | Curated: N; Channel: 2.2.0; Min: ✗ |
| pkg | 81 | jedi | >=0.19.2,<1 | Avail: ✓ | Pure Python | Curated: N; Channel: 0.19.2; Min: ✗ |
| pkg | 82 | jinja2 | >=3.1.6,<4 | Avail: ✓ | Bundled | Curated: Y; Channel: 3.1.6; Min: 3.1.6 |
| pkg | 83 | joblib | >=1.4.0,<2 | Avail: ✓ | Browser caveat | Curated: N; Channel: 1.4.0; Min: 1.4.2; multiprocessing limited |
| pkg | 84 | json5 | >=0.12.1,<0.13 | Avail: ✓ | Pure Python | Curated: N; Channel: 0.12.1; Min: ✗ |
| pkg | 85 | jsonpointer | >=3.0.0,<4 | Avail: ✓ | Pure Python | Curated: N; Channel: 3.0.0; Min: ✗ |
| pkg | 86 | jsonschema | >=4.17.3,<5 | Avail: ✓ | Bundled | Curated: Y; Channel: 4.17.3; Min: 4.23.0 |
| pkg | 87 | jupyter_server | *(no ver)* | Avail: ✗ | Server-side; not Pyodide | Curated: N; Min: ✗ |
| pkg | 88 | jupyterlite-core | >=0.7 | Avail: ✗ | Build tool; not Pyodide | Curated: N; Min: ✗ |
| pkg | 89 | jupyterlite-xeus | >=4.3 | Avail: ✗ | Build tool; not Pyodide | Curated: N; Min: ✗ |
| pkg | 90 | jupytext | >=1.18.1,<2 | Avail: ✓ | Pure Python | Curated: N; Channel: 1.19.0; Min: ✗ |
| pkg | 91 | kiwisolver | >=1.3.2,<2 | Avail: ✓ | Bundled | Curated: Y; Channel: 1.3.2; Min: 1.4.8 |
| pkg | 92 | langgraph | >=0.2.28,<0.3 | Avail: ✗ | Not in channel | Curated: N; heavy dep tree |
| pkg | 93 | lark | >=1.3.1,<2 | Avail: ✓ | Pure Python | Curated: N; Channel: 1.3.1; Min: ✗ |
| pkg | 94 | logbook | >=1.6.0,<2 | Avail: ✓ | Pure Python | Curated: N; Channel: 1.6.0; Min: ✗ |
| pkg | 95 | loguru | >=0.7.3,<1 | Avail: ✓ | Pure Python | Curated: N; Channel: 0.7.3; Min: ✗ |
| pkg | 96 | lxml | >=4.9.4,<5 | Avail: ✗ | C ext; no emscripten wheel | Curated: N; Min: ✗ |
| pkg | 97 | markdown2 | >=2.5.4,<3 | Avail: ✓ | Pure Python | Curated: N; Channel: 2.5.4; Min: ✗ |
| pkg | 98 | markupsafe | >=3.0.2,<4 | Avail: ✓ | Transitive via jinja2 | Curated: dep; Channel: 3.0.2; Min: 3.0.2 |
| pkg | 99 | marshmallow | >=3.26.1,<4 | Avail: ✓ | Pure Python | Curated: N; Channel: 3.26.1; Min: ✗ |
| pkg | 100 | matplotlib | >=3.5,<4 | Avail: ✓ | Bundled | Curated: Y; Channel: 3.9.4; Min: 3.8.4 |
| pkg | 101 | mdurl | >=0.1.2,<1 | Avail: ✓ | Pure Python | Curated: N; Channel: 0.1.2; Min: ✗ |
| pkg | 102 | mergedeep | >=1.3.4,<2 | Avail: ✓ | Pure Python | Curated: N; Channel: 1.3.4; Min: ✗ |
| pkg | 103 | mistune | >=3.2.0,<4 | Avail: ✓ | Pure Python | Curated: N; Channel: 3.2.0; Min: ✗ |
| pkg | 104 | mlxtend | >=0.23.4,<0.24 | Avail: ✗ | Not in channel | Curated: N; Min: ✗ |
| pkg | 105 | mock | >=5.2.0,<6 | Avail: ✓ | Pure Python | Curated: N; Channel: 5.2.0; Min: ✗ |
| pkg | 106 | monotonic | >=1.6,<2 | Avail: ✓ | Pure Python | Curated: N; Channel: 1.6; Min: ✗ |
| pkg | 107 | mpmath | >=1.3.0,<2 | Avail: ✓ | Transitive via sympy | Curated: dep; Channel: 1.3.0; Min: 1.3.0 |
| pkg | 108 | multidict | >=6.6.4,<7 | Avail: ✓ | Bundled | Curated: Y; Channel: 6.7.0; Min: 6.6.4 |
| pkg | 109 | munch | >=4.0.0,<5 | Avail: ✓ | Pure Python | Curated: N; Channel: 4.0.0; Min: ✗ |
| pkg | 110 | mutagen | >=1.47.0,<2 | Avail: ✓ | Pure Python | Curated: N; Channel: 1.47.0; Min: ✗ |
| pkg | 111 | narwhals | >=1.46.0,<2 | Avail: ✓ | Bundled | Curated: Y; Channel: 1.48.1; Min: 1.46.0 |
| pkg | 112 | nbformat | >=5.10.4,<6 | Avail: ✓ | Pure Python | Curated: N; Channel: 5.10.4; Min: ✗ |
| pkg | 113 | networkx | >=3.2,<4 | Avail: ✓ | Bundled | Curated: Y; Channel: 3.2; Min: 3.4.2 |
| pkg | 114 | nltk | >=3.9.1,<4 | Avail: ✓ | Browser caveat | Curated: N; needs network for corpora |
| pkg | 115 | notebook | >=7.5 | Avail: ✗ | Server-side; not Pyodide | Curated: N; Min: ✗ |
| pkg | 116 | numpy | >=1,<2 | Avail: ✓ | Bundled | Curated: Y; Channel: 1.25.2; Min: 2.2.5 (conflict) |
| pkg | 117 | oauthlib | >=3.3.1,<4 | Avail: ✓ | Pure Python | Curated: N; Channel: 3.3.1; Min: ✗ |
| pkg | 118 | openpyxl | >=3.0.9,<4 | Avail: ✓ | Pure Python | Curated: N; Channel: 3.0.9; Min: ✗ |
| pkg | 119 | optlang | >=1.8.2,<2 | Avail: ✗ | Not in channel | Curated: N; swiglpk dep available |
| pkg | 120 | orjson | >=3.10.6,<4 | Avail: ✓ | Bundled | Curated: Y; Channel: 3.10.6; Min: 3.10.16 |
| pkg | 121 | overrides | >=7.7.0,<8 | Avail: ✓ | Pure Python | Curated: N; Channel: 7.7.0; Min: ✗ |
| pkg | 122 | packaging | >=24.2,<25 | Avail: ✓ | Bundled | Curated: Y; Channel: 24.2; Min: 24.2 |
| pkg | 123 | paginate | >=0.5.7,<1 | Avail: ✓ | Pure Python | Curated: N; Channel: 0.5.7; Min: ✗ |
| pkg | 124 | pandas | >=1.5.3,<3 | Avail: ✓ | Bundled | Curated: Y; Channel: 1.5.3; Min: 2.3.2 |
| pkg | 125 | pandera | >=0.22.1,<0.23 | Avail: ✓ | Pure Python | Curated: N; Channel: 0.22.1; Min: ✗ |
| pkg | 126 | param | >=2.2.0,<3 | Avail: ✓ | Pure Python | Curated: N; Channel: 2.3.1; Min: ✗ |
| pkg | 127 | parso | >=0.8.4,<1 | Avail: ✓ | Pure Python | Curated: N; Channel: 0.8.5; Min: ✗ |
| pkg | 128 | pathspec | >=0.12.1,<0.13 | Avail: ✓ | Pure Python | Curated: N; Channel: 0.12.1; Min: ✗ |
| pkg | 129 | patsy | >=1.0.1,<2 | Avail: ✓ | Pure Python | Curated: N; Channel: 1.0.1; Min: ✗ |
| pkg | 130 | peewee | >=3.17.3,<4 | Avail: ✓ | Bundled | Curated: Y; Channel: 3.17.3; Min: 3.17.9 |
| pkg | 131 | pexpect | >=4.9.0,<5 | Avail: ✓ | Browser caveat | Curated: N; subprocess broken in browser |
| pkg | 132 | pillow | >=10.3.0,<11 | Avail: ✓ | Bundled | Curated: Y; Channel: 10.3.0; Min: 11.3.0 (conflict) |
| pkg | 133 | pip | *(no ver)* | Avail: ✗ | Pyodide uses micropip | Curated: Y; Min: ✗ |
| pkg | 134 | platformdirs | >=4.3.6,<5 | Avail: ✓ | Pure Python | Curated: N; Channel: 4.5.1; Min: ✗ |
| pkg | 135 | plotly | >=6.3.0,<7 | Avail: ✓ | Pure Python; large | Curated: N; Channel: 6.5.2; Min: ✗ |
| pkg | 136 | pluggy | >=1.5.0,<2 | Avail: ✓ | Bundled | Curated: Y; Channel: 1.6.0; Min: 1.5.0 |
| pkg | 137 | priority | >=2.0.0,<3 | Avail: ✓ | Pure Python | Curated: N; Channel: 2.0.0; Min: ✗ |
| pkg | 138 | propcache | >=0.3.0,<1 | Avail: ✓ | C ext; wheel | Curated: N; Channel: 0.3.1; Min: 0.3.0 |
| pkg | 139 | py | >=1.11.0,<2 | Avail: ✓ | Bundled | Curated: Y; Channel: 1.11.0; Min: 1.11.0 |
| pkg | 140 | pyaml | >=25.7.0,<26 | Avail: ✓ | Pure Python | Curated: N; Channel: 25.7.0; pyyaml wheel available |
| pkg | 141 | pycparser | >=2.22,<3 | Avail: ✓ | Pure Python | Curated: N; Channel: 2.22; Min: 2.22 |
| pkg | 142 | pydantic | >=2.8.2,<3 | Avail: ✓ | Bundled | Curated: Y; Channel: 2.8.2; Min: 2.10.6 |
| pkg | 143 | pyee | >=13.0.0,<14 | Avail: ✓ | Pure Python | Curated: N; Channel: 13.0.0; Min: ✗ |
| pkg | 144 | pygad | >=3.5.0,<4 | Avail: ✓ | Pure Python | Curated: N; Channel: 3.5.0; Min: ✗ |
| pkg | 145 | pyparsing | >=3.2.1,<4 | Avail: ✓ | Pure Python | Curated: N; Channel: 3.3.2; Min: 3.2.1 |
| pkg | 146 | pypdf | >=6.6.0,<7 | Avail: ✓ | Pure Python | Curated: N; Channel: 6.6.0; Min: ✗ |
| pkg | 147 | pyphen | >=0.17.2,<1 | Avail: ✓ | Pure Python | Curated: N; Channel: 0.17.2; Min: ✗ |
| pkg | 148 | pyrsistent | >=0.18.1,<0.21 | Avail: ✓ | C ext; wheel | Curated: dep?; Channel: 0.18.1; Min: 0.20.0 |
| pkg | 149 | pytest | >=8.3.2,<9 | Avail: ✓ | Bundled | Curated: Y; Channel: 8.3.2; Min: 8.3.5 |
| pkg | 150 | pytesseract | >=0.3.13,<1 | Avail: ✓ | Browser caveat | Curated: N; needs Tesseract binary |
| pkg | 151 | python | *(runtime)* | Avail: ✓ | Runtime | Channel: 3.11.3; Min: 3.13 |
| pkg | 152 | pytz | >=2025.2,<2026 | Avail: ✓ | Pure Python | Curated: N; Channel: 2025.2; Min: 2025.2 |
| pkg | 153 | pyxlsb | >=1.0.10,<2 | Avail: ✓ | Pure Python | Curated: N; Channel: 1.0.10; Min: ✗ |
| pkg | 154 | qrcode | >=8.2,<9 | Avail: ✓ | Pure Python | Curated: N; Channel: 8.2; Min: ✗ |
| pkg | 155 | requests | >=2.32.3,<3 | Avail: ✓ | Bundled | Curated: Y; Channel: 2.32.5; Min: 2.32.4 |
| pkg | 156 | rich | >=13.9.4,<15 | Avail: ✓ | Bundled | Curated: Y; Channel: 14.2.0; Min: 13.9.4 |
| pkg | 157 | scikit-learn | >=1.1.1,<2 | Avail: ✓ | Bundled | Curated: Y; Channel: 1.1.3; Min: 1.7.0 |
| pkg | 158 | scipy | >=1.11.1,<2 | Avail: ✓ | Bundled | Curated: Y; Channel: 1.11.1; Min: 1.14.1 |
| pkg | 159 | seaborn | >=0.13.2,<0.14 | Avail: ✓ | Pure Python | Curated: N; Channel: 0.13.2; Min: ✗ |
| pkg | 160 | shapely | >=2.0.7,<3 | Avail: ✓ | C ext; wheel | Curated: N; Channel: 2.1.0; geos included |
| pkg | 161 | shellingham | >=1.5.4,<2 | Avail: ✓ | Browser caveat | Curated: N; shell detect broken |
| pkg | 162 | simpy | >=4.1.1,<5 | Avail: ✓ | Pure Python | Curated: N; Channel: 4.1.1; Min: ✗ |
| pkg | 163 | six | >=1.17.0,<2 | Avail: ✓ | Bundled | Curated: Y; Channel: 1.17.0; Min: 1.17.0 |
| pkg | 164 | sniffio | >=1.3.1,<2 | Avail: ✓ | Pure Python | Curated: N; Channel: 1.3.1; Min: ✗ |
| pkg | 165 | sortedcontainers | >=2.4.0,<3 | Avail: ✓ | Pure Python | Curated: N; Channel: 2.4.0; Min: ✗ |
| pkg | 166 | sqlalchemy | >=2.0.32,<3 | Avail: ✓ | Bundled | Curated: Y; Channel: 2.0.32; Min: 2.0.39 |
| pkg | 167 | sqlglot | >=27.20.0,<29 | Avail: ✓ | Pure Python | Curated: N; Channel: 28.6.0; Min: ✗ |
| pkg | 168 | sqlparse | >=0.5.5,<1 | Avail: ✓ | Pure Python | Curated: N; Channel: 0.5.5; Min: ✗ |
| pkg | 169 | starlette | >=0.47.2,<1 | Avail: ✓ | Browser caveat | Curated: N; server framework; no browser use |
| pkg | 170 | statsmodels | >=0.14.1,<0.15 | Avail: ✓ | C ext; wheel | Curated: N; Channel: 0.14.1; Min: ✗ |
| pkg | 171 | svgwrite | >=1.4.3,<2 | Avail: ✓ | Pure Python | Curated: N; Channel: 1.4.3; Min: ✗ |
| pkg | 172 | swiglpk | >=5.0.10,<6 | Avail: ✓ | C ext; wheel | Curated: N; Channel: 5.0.10; Min: ✗ |
| pkg | 173 | sympy | >=1.13.3,<2 | Avail: ✓ | Bundled | Curated: Y; Channel: 1.14.0; Min: 1.13.3 |
| pkg | 174 | tabulate | >=0.9.0,<1 | Avail: ✓ | Pure Python | Curated: N; Channel: 0.9.0; Min: ✗ |
| pkg | 175 | tenacity | >=9.1.2,<10 | Avail: ✓ | Pure Python | Curated: N; Channel: 9.1.2; Min: ✗ |
| pkg | 176 | termcolor | >=2.5.0,<3 | Avail: ✓ | Pure Python | Curated: N; Channel: 2.5.0; Min: ✗ |
| pkg | 177 | threadpoolctl | >=3.5.0,<4 | Avail: ✓ | Browser caveat | Curated: N; Channel: 3.6.0; Min: 3.5.0 |
| pkg | 178 | tinycss2 | >=1.5.1,<2 | Avail: ✓ | Pure Python | Curated: N; Channel: 1.5.1; Min: ✗ |
| pkg | 179 | toml | >=0.10.2,<1 | Avail: ✓ | Pure Python | Curated: N; Channel: 0.10.2; Min: ✗ |
| pkg | 180 | tomli | >=2.2.1,<3 | Avail: ✓ | Pure Python | Curated: N; Channel: 2.4.0; Min: ✗ |
| pkg | 181 | tomlkit | >=0.14.0,<1 | Avail: ✓ | Pure Python | Curated: N; Channel: 0.14.0; Min: ✗ |
| pkg | 182 | toolz | >=1.0.0,<2 | Avail: ✓ | Bundled | Curated: Y; Channel: 1.1.0; Min: 1.0.0 |
| pkg | 183 | tqdm | >=4.67.1,<5 | Avail: ✓ | Bundled | Curated: Y; Channel: 4.67.1; Min: 4.67.1 |
| pkg | 184 | traitlets | >=5.14.3,<6 | Avail: ✓ | Pure Python | Curated: N; Channel: 5.14.3; Min: ✗ |
| pkg | 185 | traits | >=7.0.2,<8 | Avail: ✓ | C ext; wheel | Curated: N; Channel: 7.0.2; Min: ✗ |
| pkg | 186 | trimesh | >=4.11.1,<5 | Avail: ✓ | Pure Python | Curated: N; Channel: 4.11.1; Min: ✗ |
| pkg | 187 | typeguard | >=4.4.4,<5 | Avail: ✓ | Pure Python | Curated: N; Channel: 4.4.4; Min: ✗ |
| pkg | 188 | typer | >=0.19.2,<1 | Avail: ✓ | Pure Python | Curated: N; Channel: 0.21.1; Min: ✗ |
| pkg | 189 | urllib3 | >=2.2.2,<3 | Avail: ✓ | Bundled | Curated: Y; Channel: 2.2.2; Min: 2.5.0 |
| pkg | 190 | wasabi | >=1.1.3,<2 | Avail: ✓ | Pure Python | Curated: N; Channel: 1.1.3; Min: ✗ |
| pkg | 191 | wcwidth | >=0.2.13,<1 | Avail: ✓ | Pure Python | Curated: N; Channel: 0.2.14; Min: ✗ |
| pkg | 192 | webcolors | >=25.10.0,<26 | Avail: ✓ | Pure Python | Curated: N; Channel: 25.10.0; Min: ✗ |
| pkg | 193 | webencodings | >=0.5.1,<1 | Avail: ✓ | Pure Python | Curated: N; Channel: 0.5.1; Min: ✗ |
| pkg | 194 | wrapt | >=1.17.2,<2 | Avail: ✓ | Bundled | Curated: Y; Channel: 1.17.2; Min: 1.17.2 |
| pkg | 195 | xarray | >=2024.3.0,<2025 | Avail: ✓ | Pure Python | Curated: N; Channel: 2024.3.0; Min: ✗ |
| pkg | 196 | xlrd | >=2.0.1,<3 | Avail: ✓ | Pure Python | Curated: N; Channel: 2.0.2; Min: ✗ |
| pkg | 197 | xlsxwriter | >=3.2.9,<4 | Avail: ✓ | Pure Python | Curated: N; Channel: 3.2.9; Min: ✗ |
| pkg | 198 | xmltodict | >=1.0.2,<2 | Avail: ✓ | Pure Python | Curated: N; Channel: 1.0.2; Min: ✗ |
| pkg | 199 | xyzservices | >=2025.1.0,<2026 | Avail: ✓ | Pure Python | Curated: N; Channel: 2025.11.0; Min: ✗ |
| pkg | 200 | yarl | >=1.18.3,<2 | Avail: ✓ | Bundled | Curated: Y; Channel: 1.22.0; Min: 1.18.3 |
| pkg | 201 | zipp | >=3.23.0,<4 | Avail: ✓ | Pure Python | Curated: N; Channel: 3.23.0; Min: ✗ |

## Version Range Conflicts / Drifts

| type | id | name | version/range | status | notes | extra_info |
| --- | ---: | --- | --- | --- | --- | --- |
| conf | 1 | numpy | >=1,<2 | Range Error | Major bump | Min=2.2.5; update to >=1,<3 or pin |
| conf | 2 | pillow | >=10.3.0,<11 | Range Error | Major bump | Min=11.3.0; update upper bound <12 |
| conf | 3 | pandas | >=1.5.3,<3 | Drift | Min newer than channel | Min=2.3.2 vs channel 1.5.3 |
| conf | 4 | scikit-learn | >=1.1.1,<2 | Drift | Min newer than channel | Min=1.7.0 vs channel 1.1.3 |
| conf | 5 | scipy | >=1.11.1,<2 | Drift | Min newer than channel | Min=1.14.1 vs channel 1.11.1 |
| conf | 6 | cryptography | >=42.0.2,<47 | Drift | Min much newer than channel | Min=46.0.1 vs channel 42.0.2 |

## Minimal Bundle Transitives (not in 201)

| type | id | name | version/range | status | notes | extra_info |
| --- | ---: | --- | --- | --- | --- | --- |
| tran | 1 | annotated_types | 0.7.0 | Min: ✓ | pydantic dep | transitive |
| tran | 2 | async_timeout | 5.0.1 | Min: ✓ | aiohttp dep | transitive |
| tran | 3 | charset_normalizer | 3.4.3 | Min: ✓ | requests dep | transitive |
| tran | 4 | fonttools | 4.56.0 | Min: ✓ | matplotlib dep | transitive |
| tran | 5 | hashlib | 1.0.0 | Min: ✓ | Pyodide core module | transitive |
| tran | 6 | jsonschema_specifications | 2024.10.1 | Min: ✓ | jsonschema dep | transitive |
| tran | 7 | lzma | 1.0.0 | Min: ✓ | Pyodide core module | transitive |
| tran | 8 | micropip | 0.11.0 | Min: ✓ | package installer | transitive |
| tran | 9 | more_itertools | 10.6.0 | Min: ✓ | utility dep | transitive |
| tran | 10 | pydantic_core | 2.27.2 | Min: ✓ | pydantic dep | transitive |
| tran | 11 | pyodide_http | 0.2.2 | Min: ✓ | Pyodide HTTP adapter | transitive |
| tran | 12 | python_dateutil | 2.9.0 | Min: ✓ | pandas dep | transitive |
| tran | 13 | referencing | 0.36.2 | Min: ✓ | jsonschema dep | transitive |
| tran | 14 | rpds_py | 0.27.0 | Min: ✓ | jsonschema dep | transitive |
| tran | 15 | setuptools | 76.0.0 | Min: ✓ | core packaging | transitive |
| tran | 16 | soupsieve | 2.6 | Min: ✓ | beautifulsoup4 dep | transitive |
| tran | 17 | sqlite3 | 1.0.0 | Min: ✓ | Pyodide core module | transitive |
| tran | 18 | ssl | 1.0.0 | Min: ✓ | Pyodide core module | transitive |
| tran | 19 | tblib | 3.0.0 | Min: ✓ | exception serialization | transitive |
| tran | 20 | typing_extensions | 4.15.0 | Min: ✓ | backport dep | transitive |

## MicroPython Equivalents

| type | id | name | version/range | status | notes | extra_info |
| --- | ---: | --- | --- | --- | --- | --- |
| micr | 1 | numpy | ulab | mpy-equiv | FFT, linalg, ndarray | repo: v923z/micropython-ulab |
| micr | 2 | pandas | lontras | mpy-equiv | tiny DataFrame pattern | repo: luxedo/lontras |
| micr | 3 | scipy | ulab + focused helpers | mpy-equiv | FFT/filters/linalg | repo: v923z/micropython-ulab |
| micr | 4 | scikit-learn | emlearn-micropython | mpy-equiv | train off-device | repo: emlearn/emlearn-micropython |
| micr | 5 | altair | tempe/microplot | mpy-equiv | lightweight plotting | repo: unital/tempe; romilly/microplot |
| micr | 6 | requests | urequests/mrequests | mpy-equiv | HTTP client | repo: SpotlightKid/mrequests |
| micr | 7 | aiohttp | uaiohttpclient | mpy-equiv | async HTTP | repo: micropython/micropython-lib |
| micr | 8 | tqdm | serial/OLED bars | mpy-equiv | progress display | repo: follower46/micropython-oled-progressbars |
| micr | 9 | rich | ulogger-like | mpy-equiv | minimal ANSI/logging | repo: majoson-chen/micropython-ulogger |
| micr | 10 | toolz | itertools/functools | mpy-equiv | built-ins + utils | repo: micropython/micropython |
| micr | 11 | jsonschema | hand-rolled validators | mpy-equiv | full schema off-device | repo: pattern only |
| micr | 12 | pydantic | explicit model classes | mpy-equiv | lightweight validation | repo: pattern only |
| micr | 13 | orjson | ujson/json | mpy-equiv | fast JSON path | repo: micropython/micropython |
| micr | 14 | pytz | utime + offsets | mpy-equiv | timezone approximation | repo: micropython/micropython |
| micr | 15 | beautifulsoup4 | off-device parsing | mpy-equiv | parse tiny known fragments only | repo: pattern only |
| micr | 16 | jinja2 | utemplate | mpy-equiv | micro-templating | repo: pfalcon/utemplate |
| micr | 17 | cffi | USER_C_MODULES/viper | mpy-equiv | native extension pattern | repo: micropython/micropython |
| micr | 18 | cryptography | ucryptolib/ucrypto | mpy-equiv | crypto primitives | repo: dmazzella/ucrypto; Carglglz/mpy-mbedtls |
| micr | 19 | joblib | uasyncio + local cache | mpy-equiv | concurrency/cache pattern | repo: armanghobadi/unosql |
| micr | 20 | logbook | ulogging family | mpy-equiv | lightweight logs | repo: iabdalkader/micropython-ulogging |
| micr | 21 | markupsafe | html.escape helper | mpy-equiv | tiny escape utility | repo: built-ins |
| micr | 22 | peewee | usqlite/NoSQL | mpy-equiv | lightweight persistence | repo: spatialdude/usqlite |
| micr | 23 | pyrsistent | tuples/namedtuple | mpy-equiv | immutable discipline | repo: core types |
| micr | 24 | sqlalchemy | usqlite/unosql | mpy-equiv | keep ORM server-side | repo: spatialdude/usqlite; armanghobadi/unosql |
| micr | 25 | diskcache | unosql/JSON DB | mpy-equiv | local K/V caching | repo: armanghobadi/unosql; sungkhum/MicroPyDatabase |
| micr | 26 | httpx | mrequests + async client | mpy-equiv | sync/async HTTP pattern | repo: same as requests/aiohttp |
| micr | 27 | websockets | uwebsockets | mpy-equiv | async ws wrappers | repo: danni/uwebsockets; Basch3000/micropython-websocket |
| micr | 28 | paho-mqtt | micropython-mqtt | mpy-equiv | async MQTT | repo: peterhinch/micropython-mqtt |
| micr | 29 | pytest | unittest port | mpy-equiv | test pattern | repo: micropython/micropython-lib |
| micr | 30 | argparse | micropython-argparse | mpy-equiv | CLI parser pattern | repo: pfalcon/pycopy-lib |
| micr | 31 | asyncio | uasyncio | mpy-equiv | built-in async runtime | repo: micropython/micropython |
