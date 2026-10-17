# Gymbro (built app)

The built Gymbro web app, published with GitHub Pages at https://alieb3.github.io/gymbro-app/ so testers can open it. Open it once online; after that it works offline and can be installed to the home screen.

Nothing here is edited by hand. Each publish replaces every file with a fresh build of `main` from the source repository (private):

```
npx tsc -b && npx vite build --base /gymbro-app/ --outDir <this folder>
```

plus an empty `.nojekyll`, so GitHub Pages serves the files as they are.

## Licences

- Body-map art (male and female figures): react-native-body-highlighter, MIT, (c) 2022 ELABBASSI Hicham.
- Anatomy atlas art (`anatomy/`): rendered from Z-Anatomy (CC BY-SA 4.0), built on BodyParts3D, (c) The Database Center for Life Science (CC BY-SA 2.1 JP). These renders are adaptations, shared under CC BY-SA 4.0 with that credit.
- Exercise drawings (`media/guide/`): adapted from Workout Guide by Bryl Lim, partly after Everkinetic, CC BY-SA 4.0. Our adaptations are shared under the same licence (`media/guide/LICENSE.txt`); credits show under each drawing and on the Sources page.
- Fonts via @fontsource (SIL Open Font License).
