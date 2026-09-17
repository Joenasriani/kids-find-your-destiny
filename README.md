# Find Your Destiny

Play: https://kids-find-your-destiny.vercel.app/

Find Your Destiny is a five-question kids personality-style result game developed as part of a multi-game interactive children’s edutainment activation in the UAE.

## Game structure

Each playthrough selects five imaginative yes/no questions from a larger bank of fifteen questions.

The result is determined from the number of YES answers:

- 4–5 YES answers → `super` result group
- 2–3 YES answers → `middle` result group
- 0–1 YES answers → `quiet` result group

The game then selects one fantasy result at random from the matching group.

Result examples include Grand Sorcerer of Joy, Star-Touched Hero, Magic Potion Maker, Moonlight Dreamer, Keeper of Secret Myths and Wise Crystal Guardian.

## Interaction model

**five randomly selected questions → yes/no choices → YES count → themed result group → one randomly selected fantasy result**

## Activation context

This game belongs to the same `kids-*` game set developed for the multi-game interactive children’s edutainment activation in the UAE.

## Repository scope

This repository contains the standalone Find Your Destiny game. The playable implementation is contained in `index.html`.

The game file is preserved as the playable artifact. Documentation and discovery files sit around it without changing questions, answer logic, result thresholds, result text, controls, visual behavior or runtime behavior.
