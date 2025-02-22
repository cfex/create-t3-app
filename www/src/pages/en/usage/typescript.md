---
title: TypeScript
description: Usage of TypeScript
layout: ../../../layouts/docs.astro
---

<blockquote className="w-full relative italic border-l-4 bg-t3-purple-100 dark:text-t3-purple-50 text-slate-900 dark:bg-slate-700 p-2 rounded-md text-sm my-3 border-neutral-500 quote">
  <div className="relative w-fit flex items-center justify-center p-1">
    <p className="mb-4 text-lg md:text-xl">
      <span aria-hidden="true">&quot;</span>Build safety nets, not guard rails<span aria-hidden="true">&quot;</span>
    </p>
  </div>
  <cite className="flex items-center justify-end">
    <img
      alt="Avatar of @t3dotgg"
      className="w-12 mr-4 rounded-full bg-neutral-500"
      src="/images/theo_300x300.webp"
    />
    <div className="flex flex-col items-start">
      <span className="mb-1 text-sm italic font-bold">Theo - creator of the T3 Stack</span>
      <a
        href="https://twitter.com/t3dotgg"
        target="_blank"
        rel="noopener noreferrer"
        className="text-sm"
      >
        @t3dotgg
      </a>
    </div>
  </cite>
</blockquote>

Whether you're a new or seasoned developer, we think that TypeScript is a must have. It can look intimidating at first, but much like a lot of tools, is something that many never look back from after starting to use it.

It provides live feedback as you write your code by defining expected data types, and either provides helpful autocomplete in your code editor, or yells at you with red squiggly lines if you're trying to access a property that doesn't exist or trying to pass a value of the wrong type, which you would otherwise have to debug further down the line.

It is, perhaps, the tool that provides the most productivity to developers; providing documentation of the code you're writing or consuming directly in your editor, and having instant feedback as you inevitably make mistakes is absolutely priceless.

## Type Inference

While many new TypeScript developers are concerned with _writing_ TypeScript, many of its benefits don't actually require you to change your code at all, in particular inference. Inference means that if something is typed, that type will follow it throughout the flow of the application without having to be re-declared in other places. This means that for example once you have defined the types of the arguments that a function takes, the remainder of the function will usually be typesafe without requiring any further TypeScript-specific code. Library developers put a ton of work into maintaining the types for their libraries, which means that we as application developers can benefit from both the inference and the built-in documentation in your code editor that these types provide.

<a
href="https://www.youtube.com/watch?v=RmGHnYUqQ4k"
className="mx-auto"
target="_blank">

  <p align="center">
    <img
      src="/images/ts_thumbnail.webp"
      alt="You might be using TypeScript wrong..."
      width="320"
    />
  </p>
</a>

<a
href="https://www.youtube.com/watch?v=RmGHnYUqQ4k"
className="mx-auto"
target="_blank">

  <p align="center">Watch Theo's overview on Youtube here</p>
</a>

## Powerful uses of type inference

### Zod

[Zod](https://github.com/colinhacks/zod) is a schema validation library that is built on top of TypeScript. Write a schema that represents a single source of truth for your data, and Zod will ensure that your data is valid throughout your application, even across network boundaries and external APIs.

### Tanstack Query

[Tanstack Query](https://tanstack.com/query/v4/) gives you declarative, always-up-to-date auto-managed queries and mutations that directly improve both your developer and user experiences.

## Useful Resources

| Resource                                                  | Link                                                              |
| --------------------------------------------------------- | ----------------------------------------------------------------- |
| TypeScript Handbook                                       | https://www.typescriptlang.org/docs/handbook/                     |
| Beginners TypeScript Tutorial                             | https://github.com/total-typescript/beginners-typescript-tutorial |
| Type Challenges                                           | https://github.com/type-challenges/type-challenges                |
| Rodney Mullen of TypeScript (Matt Pocock) Youtube Channel | https://www.youtube.com/c/MattPocockUk/videos                     |
