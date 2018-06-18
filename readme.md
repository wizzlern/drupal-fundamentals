# Drupal Fundamentals training

Drupal Fundamentals is a Drupal training course that covers the major Drupal 8 core features. It is designed to be 
taught by experienced Drupal site builders. It may not contain enough written knowledge to be used for self study.

During the training the participants will create a festival website.

This training is developed by Wizzlern, based on Drupal training experience since 2009. The training materials 
consists of:

- Slides (day1.html, day2.html)
- Drupal composer package (todo)

## Preparation

### Slides
The slides make use of Reveal.js. To prepare:

```bash
cd drupal-fundamentals
npm install --only=production
```

Now open `day1.html` or `day2.html` in your browser.

### Drupal
The training course uses a Drupal installation, which is mostly Drupal core, but with a few additions for a better first
time and course experience.

- Todo: How to set up Drupal using the included composer package.

### Executing the training
The training course is designed to be used in small groups (typically 4 - 6 people). It runs for two
days (2 x 3 hours per day) with one trainer. 

The trainer should have thorough Drupal site building knowledge and experience. Go though all slides and carry out all
exercises to familiarize yourself with the materials and the order of the subjects. Do create pull requests for any
error you encounter or aging of the materials.

## Roadmap for stable release
These training materials are not complete yet. The following tasks are being considered:

- Add Drupal install profile
- Redo wirefames and diagrams in sharable format (svg?)
- Translate images

## Future improvements

- Add speaker notes to slides.
- Add separate document with written exercises and wire frames. Exercises are not part of the slides.
- Add (sales) summary document of the training.
- Make slides printable

## Licence
- The training slides and exercises are licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-sa/4.0/).
- The Drupal package is licensed under a GPL2+ license.
