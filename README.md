# richard-material
Material for Richard LMS

Please make sure any new material is in the format `xx-part/yy-chapter/zz-exercise/*`. Inside the exercise folder, there should be a `README.md` file with the exercise and 2 folders `app-a` and `app-b` with the question and answer respectively. With the Readme.md being the related theory

The approximate layout for the material is as follows:
```tsx
interface Material {
  part: Part; // Ex. idk yet...
  chapter: Topic // Ex. State Management, Routing, etc.
  exercise: Framework // Ex. Svelte, React, Vue, etc.
}
```