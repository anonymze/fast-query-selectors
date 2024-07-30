# Fast Query Selectors (FQS)

Get multiple HTMLElements from the document with one single function.

## Installation

```shell
npx jsr add @ano/fast-query-selectors
```

## Usage

> ```ts
> import { selectors } from "@ano/fast-query-selectors";
> const [div, span, paragraph, nonExistent] = selectors('div', 'span.my-span', '#paragraph', 'non-existent-selector');
> ```
