# React-js-Basic-Task.
Introduction To React-JS/ Basic-Fundamental Concept/Task/Ducat/How to use function as a component, how the component depends on each other/ How five component are interconnected to each other.

import { StrictMode } from "react";
import { createRoot } from "react-dom/client";

import App from "./App";

const rootElement = document.getElementById("root");
const root = createRoot(rootElement);

root.render(
  <StrictMode>
    <App />
  </StrictMode>
);
