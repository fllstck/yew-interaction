# Yew Interaction

An example web application build with the Yew framework.

It illustrates interactions.

## Counter Component

The counter component displays a number that can be incremented and decremented 
with clicks on two buttons.

## Text Component

The text component is a text-area that updates its own content with upper-case
text on input.

## Prerequisites

- [rustup](https://rustup.rs/)
- [wasm-pack](https://rustwasm.github.io/wasm-pack/)

## Building

    $ wasm-pack build --target web --out-name wasm --out-dir ./static