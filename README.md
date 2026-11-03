# Jih Bin Luo

CS at Purdue University Northwest, AI concentration, Statistics minor. Expected May 2027. Hammond, IN.

I build software that has to work on real hardware: a camera that reads a chess game off a real board, a delivery robot, an offline shop register, a bedside e-ink screen, and a printer you can run from a phone.

[Email](mailto:jihbin.luo@gmail.com) · [LinkedIn](https://www.linkedin.com/in/jihbinluo/)

## Selected work

| | |
|---|---|
| [**Chess Vision Board**](https://github.com/FortakenJay/chess-yolo-vision) | Reads a game played on a normal board through a dim ESP32 camera and writes the PGN. The trained YOLO piece model found only 9–15 of 32 pieces on this camera, so moves come from what changed on the board plus the rules of chess. 0 wrong positions across 2,176 still frames in 5 recorded games; 51 tests. |
| [**Pawnder**](https://github.com/FortakenJay/pawnder) | A coach that watches that board while you play. Stockfish judges every move, Nemotron only puts the engine's facts into words, and the advice shows on an e-paper screen next to the board. Built at the Nebius × NVIDIA hackathon. |
| [**ShelfPOS**](https://github.com/FortakenJay/ShelfPOS) | Offline-first Windows register. Checkout is one SQLite transaction; a separate Windows service syncs to the cloud after the sale. 4 stores across 2 clients, version 1.8, Playwright and Vitest in CI. [Owner dashboard](https://github.com/FortakenJay/ShelfPOS-Dashboard) is live at [shelfpos.net](https://shelfpos.net). |
| [**Waggle**](https://github.com/FortakenJay/Waggle) | Turns software requests heard by a Bee wearable into GitHub issues. Any quote the model can't trace back to the transcript goes to a review inbox instead of a guess. |
| [**E-ink dashboard**](https://github.com/FortakenJay/e-ink-dashboard) | ESP32 + 7.5" e-paper by the bed: today's blocks, deadlines, the week, and the weather, from Google Calendar through an Apps Script backend, with a Gemini brief of the day. Partial refresh, deep sleep, offline cache. |
| [**LEAK**](https://github.com/FortakenJay/Chess-Website) | Chess training around a Chess.com account. Stockfish scores the games in the browser and the drill hides the engine line until you move. [Live](https://chess.jihbinluo.com). |
| [**Elegoo / Handy3D**](https://github.com/FortakenJay/elegoo-printer-work) | Vendor-agnostic printer control: one machine model in front of Elegoo, Bambu Lab, and Creality, and a React Native app for status, files, camera, and filament. Poster at PNW Days of Discovery. |
| [**BowlPOS**](https://github.com/FortakenJay/bowlpos-case-study) | Cloud restaurant POS in 3 restaurants, about 200–300 orders a day. Summer 2026 software engineer: multi-floor table layouts and menu-demand dashboards in the admin panel. Source stays private. |
| [**ASME PNW**](https://github.com/asmePNW/main-website) · [**ARCADE**](https://github.com/PNWArcade/main-website) | Club sites and officer dashboards (web developer). Events from the university feed post to Discord. [asmepnw.com](https://asmepnw.com) · [arcadepnw.com](https://arcadepnw.com) |

## Also

Leading an 8-student team on a campus food-delivery robot. I own perception (LiDAR + camera, SLAM) and wrote a spec checker that generates the CAD layout and caught undersized drive motors. Code is not public yet.

Perception for PipeCleaner, a drain-pipe inspection robot for LaPorte County: a YOLO model that flags cracks and faults. Just started.

Undergraduate Lab Assistant at PNW's NEXIS Lab.

## Stack

Python, TypeScript, JavaScript, C#, Java, SQL. OpenCV, PyTorch, Ultralytics YOLO. React, Next.js, TanStack Start, React Native, Electron, FastAPI, Flask. Postgres, SQLite, Supabase. ESP32 / Arduino. Playwright, Vitest, pytest, Docker.

Spanish, English, Mandarin.
