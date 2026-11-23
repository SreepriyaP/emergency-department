# Emergency Department: waiting room prototypes

Three prototypes about waiting in an emergency department.

Start at https://sreepriyap.github.io/emergency-department/ or scan `qr-emergency-department.png`.

| Page | What it is |
|---|---|
| `index.html` | Landing page: choose a prototype |
| `volunteer.html` | **Volunteer mode.** You are a patient in an ED waiting room and meet three kinds of volunteer: Service, Compassionate Care and First-Aid. |
| `sms-replay.html` | **Text updates.** Eight patients' text threads from a simulated Saturday: tests are re-estimated every 10 minutes and patients get an update text when their expected time moves. Best on a phone. |
| `board-replay.html` | **Wait-time board.** The waiting-room screen replaying Sat 28 Nov 2026; every 5 minutes a LightGBM model picks each person's most likely 30-minute window. Best on a laptop or a phone turned sideways. |
| `board-concept.html` | What-if board: press buttons for an ambulance arrival, a free room or an extra clinician. |
| `sms-generator.html` | Text message builder with SMS length and safety checks. |

Every page is a single self-contained file: to run it on your own computer, open it in a browser (it also works offline).

All patients, hospitals and data are fictional. The wait-time models were trained on synthetic data from a simulated hospital (Riverside General).
