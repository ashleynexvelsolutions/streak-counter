# `@ashleynexvelsolutions/streak-counter` - a basic streak counter
 
This is a basic streak counter - inspired by Duolingo - written in TypeScript and meant for the browser (uses `localStorage`).

## Install
 
```shell
yarn add @ashleynexvelsolutions/streak-counter
```
 
```shell
npm install @ashleynexvelsolutions/streak-counter
```
 
### Usage
 
```typescript
import { streakCounter } from "@ashleynexvelsolutions/streak-counter";
 
const today = new Date();
const streak = streakCounter(localStorage, today);
// streak returns an object:
// {
//    currentCount: 1,
//    lastLoginDate: "11/11/2021",
//    startDate: "11/11/2021",
// }
```
