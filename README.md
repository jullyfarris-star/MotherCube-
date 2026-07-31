# ## Repository Structure

mothercube/
│
├── AI/                # [AIEngine](ca://s?q=MotherCube_AIEngine) — логіка обробки сигналів
├── Character/         # [CharacterEngine](ca://s?q=MotherCube_CharacterEngine) — NPC та їхні дії
├── Scene/             # [SceneEngine](ca://s?q=MotherCube_SceneEngine) — опис середовищ
├── Context/           # [ContextEngine](ca://s?q=MotherCube_ContextEngine) — час, погода, умови
├── World/             # [WorldEngine](ca://s?q=MotherCube_WorldEngine) — стан світу
├── Core/              # [CoreEngine](ca://s?q=MotherCube_CoreEngine) — центральне ядро
│
├── Animals/           # [AnimalsEngine](ca://s?q=MotherCube_AnimalsEngine) — модуль тварин
├── Garden/            # [GardenEngine](ca://s?q=MotherCube_GardenEngine) — сад/парк, ріст рослин
│
├── MotherCube/        # головний оркестратор
│   ├── mother_cube_unified.py
│   └── __main__.py
│
├── react-app/         # [React UI](ca://s?q=MotherCube_React_client)
│
├── data/              # [SQLite база](ca://s?q=MotherCube_SQLite_logging)
│   └── mutations.db
│
├── physics.jl         # [Julia physics](ca://s?q=MotherCube_Julia_physics)
├── docker-compose.yml # [Docker запуск](ca://s?q=MotherCube_Docker_запуск)
├── requirements.txt   # Python залежності
└── README.md

Пояснення 

Блоки (AI, Character, Scene, Context, World, Core) — основні двигуни симуляції.

Animals/Garden — додаткові модулі для екосистеми.

MotherCube/ — головний Python‑файл, який збирає все докупи

react-app/ — фронтенд для взаємодії

data/ — база даних для логування мутацій.

physics.jl — фізика на Julia.

docker-compose.yml — контейнеризація.


