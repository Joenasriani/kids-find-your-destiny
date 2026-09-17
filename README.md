# Find Your Destiny

Play: https://kids-find-your-destiny.vercel.app/

Find Your Destiny is a five-question kids personality-style result game created for the UAE children’s event project.

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

## Event context

This game belongs to the `kids-*` set created for the same UAE children’s event project.

## Repository scope

This repository contains the standalone Find Your Destiny game. The playable implementation is contained in `index.html`.

The game file is preserved as the playable artifact. Documentation and discovery files sit around it without changing questions, answer logic, result thresholds, result text, controls, visual behavior or runtime behavior.
