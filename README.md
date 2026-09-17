# Find Your Destiny

Playable build: https://kids-find-your-destiny.vercel.app/

Find Your Destiny is a five-question fantasy personality-style game for children, used in the same children’s-event game family as the other `kids-*` projects.

## Game structure

Each run:

1. randomly selects 5 questions from a bank of 15 fantasy-themed questions;
2. asks the player to answer each question with **YES** or **NO**;
3. counts the number of YES answers;
4. assigns the run to one of three result pools;
5. randomly selects one themed character result from that pool.

The current thresholds are:

- 4–5 YES answers → `super` result pool;
- 2–3 YES answers → `middle` result pool;
- 0–1 YES answers → `quiet` result pool.

Each pool contains three possible fantasy results, so two runs with the same YES count can produce different result names.

## Result framing

The mechanic resembles a light personality quiz: five fantasy prompts lead to a themed character result through the YES-count rule above.

The repository does not present those results as a validated psychological, educational, aptitude, or diagnostic assessment, and it contains no validation study connecting the result labels to measured traits, abilities, or learning outcomes.

## Event-family context

This game was used within the same children’s-event project family as the other `kids-*` games. That event deployment sits within a broader educational-game direction, while this repository implements this single fantasy quiz/result mechanic.

## Implementation

The playable artifact is contained in `index.html`. It uses client-side HTML, JavaScript and Tailwind loaded from a CDN. The repository does not implement user accounts, learner records, curriculum tracking, assessment scoring, or cross-game progression.

`index.html` is preserved as the game artifact. Documentation and discovery files are kept separate so repository cleanup does not change the game’s questions, answer logic, thresholds, result pools, controls, visuals, timing, or runtime behavior.
