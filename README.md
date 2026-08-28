# Teodor Ungureanu

Senior Software Developer — PHP/Laravel & React. 9+ years building enterprise software, 6 of them leading engineering teams for banking, retail, and industrial clients. Currently at Hyperfy, working on CAVI.

This profile brings together several of my projects, including a few games built in my free time — a hobby that keeps sharpening both my programming and design skills. Feel free to also browse my [repositories](https://github.com/TeodorUngureanu?tab=repositories) — some are public, others are private and previewed below instead.

## Currently Building

### CourtRise — Browser-Based Tennis Career Simulator
A full-stack web app simulating a tennis player's career — not a game project, but a deliberate technical playground to go deep on a modern, enterprise-relevant stack: Laravel as the core application (PHP, `strict_types`, Inertia.js + React + TypeScript, typed routing via Wayfinder), with an isolated NestJS microservice planned to own the point-by-point match simulation engine, called server-to-server.

**Done so far:**
- Full local dev environment containerized end-to-end: Docker Compose (Laravel + MySQL, NestJS + PostgreSQL, Adminer), running through VS Code Dev Containers — no "works on my machine" drift between services.
- Laravel backend live with Inertia.js + React + TypeScript, tested with Pest (48 passing tests) and documented via L5-Swagger (OpenAPI).
- NestJS service scaffolded, running, and reachable server-to-server from Laravel over the internal Docker network.
- Character creation — the first real gameplay feature — implemented and covered by tests.

**Next up:**
- Training with trade-offs, a small equipment system, and the point-by-point match engine itself (NestJS, built around Event Sourcing so match state can be rebuilt from a log of individual points) — implementing real tennis rules: advantage, tiebreaks, full sets.

- **Status:** Private repository — actively in development (Stage 1 / core gameplay loop)

## Personal Projects (Game Jams & Free Time)

These repositories are private too, but here are some screenshots — games I've built during game jams and in my spare time. I also have a few other private game projects not listed here — happy to share more on request.

### The Motion in the Potion
Live the life of a witch in this ultra immersive cauldron spinning simulator.

<img width="240" height="135" alt="2_Quests" src="https://github.com/user-attachments/assets/6cbb1936-0bb0-4339-b4c4-1013cf4f8e84" />
<img width="240" height="135" alt="3_Outside" src="https://github.com/user-attachments/assets/ae83f539-01d2-4b23-a417-fe6a786d9f14" />
<img width="240" height="135" alt="5_To Cauldron" src="https://github.com/user-attachments/assets/9b880528-9c6d-4d6f-aa5f-f981733e2d76" />
<img width="240" height="135" alt="7_Instructions Manual" src="https://github.com/user-attachments/assets/0a7ad45d-7587-4e0d-844a-0260163dea76" />
<img width="240" height="135" alt="9_Create Potion" src="https://github.com/user-attachments/assets/8b9c0aeb-9240-4bdc-81a1-6c402ccfc289" />

### Foranger
You have just been assigned as the ranger in a magical forest. You have to protect it and its inhabitants, while also providing potion ingredients for your clients. Be careful though, for there is evil in this magical world, and it could be spreading throughout your forest next!

<img width="240" height="135" alt="foranger 1" src="https://github.com/user-attachments/assets/37c7a563-8970-4931-8b61-7302dbbe68b3" />
<img width="240" height="135" alt="foranger 2" src="https://github.com/user-attachments/assets/77cb8f61-e18e-4e9e-913f-2dee7f8c48e2" />
<img width="240" height="135" alt="foranger 3" src="https://github.com/user-attachments/assets/84ce592c-33a7-470b-80a4-b84c0998bb06" />
<img width="240" height="135" alt="foranger 4" src="https://github.com/user-attachments/assets/39631bd3-9b16-481f-b427-1a25328c30e4" />
<img width="240" height="135" alt="foranger 5" src="https://github.com/user-attachments/assets/b02ff7c7-7e1e-40c0-a425-c2e0ac507c19" />

### The Day When The World Lost Its Color
A painter is working on a cathedral fresco when a chemical spill damages his eyes, leaving him seeing only in shades of gray. He sets out into the world to get his colors back, solving puzzles and completing quests as the three primary colors — red, green, and blue — gradually return to his sight.

<img width="240" height="135" alt="tdwtwlic 1" src="https://github.com/user-attachments/assets/b22509cd-2798-474e-91c8-00926601bcb7" />
<img width="240" height="135" alt="tdwtwlic 2" src="https://github.com/user-attachments/assets/61790d96-0cad-43d4-92c2-81f670bae795" />
<img width="240" height="135" alt="tdwtwlic 3" src="https://github.com/user-attachments/assets/46d7bab9-0461-4f53-bf57-5132442772b8" />
<img width="240" height="135" alt="tdwtwlic 4" src="https://github.com/user-attachments/assets/2a672ba6-eaee-42a6-925f-409c6a5b9d55" />
<img width="240" height="135" alt="tdwtwlic 5" src="https://github.com/user-attachments/assets/5c15a46d-8b78-45c5-b611-e5669941e0c0" />
<img width="240" height="135" alt="tdwtwlic 6" src="https://github.com/user-attachments/assets/fb412eb7-bae0-48ea-aed6-c3ced1c6ad9f" />
<img width="240" height="135" alt="tdwtwlic 7" src="https://github.com/user-attachments/assets/8ba90f25-ba2e-44a0-b576-96d53c55124a" />
<img width="240" height="135" alt="tdwtwlic 8" src="https://github.com/user-attachments/assets/2384431f-ab87-4c7e-85cd-49b4c54b82db" />
<img width="240" height="135" alt="tdwtwlic 9" src="https://github.com/user-attachments/assets/4786157b-d492-4f55-a5dd-5a6c8391f1fd" />
<img width="240" height="135" alt="tdwtwlic 10" src="https://github.com/user-attachments/assets/40c14a6d-0d90-43d9-aead-d1945c88a63d" />
<img width="240" height="135" alt="tdwtwlic 11" src="https://github.com/user-attachments/assets/970cabcb-e4d1-4ec8-a280-6667e9c0465e" />

### Dauntless Spirit
An evil spirit captures the Seasons, causing chaos and turning the world into a desert. The Fox sets out to save them, first crossing the desert and facing the evil spirit in a final battle — defeating it and forcing it to retreat. The Fox then enters each Season's territory; each one has been corrupted and must be defeated before joining the party. Each Season has one or more unique abilities, and switching between the Fox and a Season shifts the background's color palette to reflect that Season. By the end, the party is made up of the Fox and all four Seasons, who must face the evil spirit once more — having absorbed part of the Seasons' powers in the meantime, it is now far harder to defeat.

[<img src="https://img.youtube.com/vi/cD6cMA5CJwA/0.jpg" width="480">](https://youtu.be/cD6cMA5CJwA)

## Contact

- Email: theodoreungureanu@gmail.com
