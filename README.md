# ED Waiting Room: Volunteer Simulator

A playable prototype. You are a patient in an emergency department waiting room and meet three kinds of volunteer: Service, Compassionate Care and First-Aid.

Play it at https://sreepriyap.github.io/waiting-room/ or scan `qr-the-wait.png`.

To run it on your own computer, open `index.html` in a browser. Everything is in that one file.

All patients and scenarios are fictional.

## ED Wait Times: proof of concept

A waiting-room display board and patient text updates driven by prediction models, using synthetic data from a simulated hospital (Riverside General is fictional).

See it at https://sreepriyap.github.io/waiting-room/wait-times/ or scan `qr-wait-times.png`.

- `wait-times/board-replay.html`: the board replaying Sat 28 Nov 2026; every 5 minutes a LightGBM model picks each person's most likely 30-minute window.
- `wait-times/sms-replay.html`: eight patients' text threads, with tests re-estimated every 10 minutes and update texts when a window moves.
- `wait-times/board-concept.html` and `wait-times/sms-generator.html`: the earlier what-if demos.

Every page is a single self-contained file and also works offline.
