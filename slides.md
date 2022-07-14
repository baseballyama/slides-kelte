---
theme: seriph
background: https://source.unsplash.com/collection/94734566/1920x1080
highlighter: shiki
favicon: "assets/favicon.svg"
lineNumbers: true
info: |
  ## Slides of Kvelte
  The fastest way to build UI with Svelte for Kotlin users.

  Learn more at [GitHub](https://github.com/baseballyama/kvelte)
drawings:
  persist: false
title: Kvelte ~ Use Svelte From Kotlin ~
---

# Kvelte

## ~ Use Svelte From Kotlin ~

baseballyama

<div class="abs-br m-6 flex gap-2">
  <a href="https://github.com/baseballyama" target="_blank" alt="GitHub"
    class="text-xl icon-btn opacity-50 !border-none !hover:text-white">
    <carbon-logo-github />
  </a>
</div>
---

<div class="flex items-center justify-center h-1/1">
  <h1>History of Web Frameworks</h1>
</div>
---

# History of Web Frameworks

<p>
  199x - Everything started from here
</p>

<div class="flex gap w-1/1">
  <div class="w-7/10">
  <h2>The Beginning of the World</h2>
  <br />

- <logos-html5 /> 1993 - First version of HTML released.
- <logos-css3 /> 1994 - published the first draft of the CSS.
- <logos-javascript /> 1995 - published the new scripting language called Mocha, which eventually became known as JavaScript.

</div>
  <div class="w-3/10 flex flex-col items-center !opacity-70">
    <img class="w-1/1 h-9/10" src="/assets/html.jpg" />
    <span class="mt-2">Tim Berners-Lee</span>
  </div>
</div>

<p class="!mt-0">
  <a class="text-xs" target="_blank" rel="noopener noreferrer" href="https://devdojo.com/tnylea/a-brief-history-of-web-development">
    https://devdojo.com/tnylea/a-brief-history-of-web-development
  </a>
</p>
---

# History of Web Frameworks

<p>
  200x - Building dynamic HTML on server side
</p>
  
<div class="flex gap w-1/1">
  <div class="w-7/10 pr-4">
  <h2>Server Side Rendering</h2>
  <br />

- <logos-php /> 1995 - PHP. Personal Home Page.
- <logos-java /> 1996 - Java Servlet is released. In 1999, JSP is released.
- <logos-java /> 2001 - Apache Struts is released. / 2002 - Spring is released.
- <logos-ruby /> 2005 - Ruby is an interpreted, high-level, general-purpose programming language.
- <logos-python /> 2005 - Django was rising in popularity.
- <logos-go /> 2009 - Go is a statically typed, compiled programming language designed at Google by Robert Griesemer, Rob Pike, and Ken Thompson.
- <logos-laravel /> 2011 - Taylor Otwell released Laravel
- <logos-kotlin-icon /> 2011 - Kotlin. Sometimes called better Java.

</div>
<div class="w-3/10 flex flex-col items-center !opacity-70">
  <img class="w-1/1 h-9/10" src="/assets/ror.jpg" />
  <span class="mt-2">David Heinemeier Hansson</span>
</div>
</div>

<span class="!mt-0 mr-4">
  <a class="text-xs" target="_blank" rel="noopener noreferrer" href="https://devdojo.com/tnylea/a-brief-history-of-web-development">
    https://devdojo.com/tnylea/a-brief-history-of-web-development
  </a>
</span>
<span class="!mt-0">
  <a class="text-xs" target="_blank" rel="noopener noreferrer" href="https://speakerdeck.com/michaelisvy/web-frameworks-in-java-10-years-of-history">
    https://speakerdeck.com/michaelisvy/web-frameworks-in-java-10-years-of-history
  </a>
</span>
---

# History of Web Frameworks

<p>
  201x - Faster transitions that make the website feel more like a native app
</p>
  
<div class="flex gap w-1/1">
  <div class="w-7/10 pr-4">
  <h2>SPA / V-DOM / Declarative UI</h2>
  <br />

- <logos-angular-icon /> 2012 - Google released AngularJS.
- <logos-react /> 2013 - Meta released React.
- <logos-vue /> 2014 - Evan You released Vue.js.
- <logos-preact /> 2015 - Jason Miller released Preact.

</div>
<div class="w-3/10 flex flex-col items-center !opacity-70">
  <img class="w-1/1 h-9/10" src="/assets/vue.jpg" />
  <span class="mt-2">Evan You</span>
</div>
</div>
---

# History of Web Frameworks

<p>
  201x - Node.js has significantly developed the JavaScript ecosystem
</p>
  
<div class="flex gap w-1/1">
  <div class="w-7/10 pr-4">
  <h2>JavaScript Ecosystems</h2>
  <br />

- <logos-nodejs /> 2009 - Node.js is an open-source, cross-platform, back-end JavaScript runtime environment.
- <logos-express /> 2010 - express. Fast, unopinionated, minimalist web framework for node.
- <logos-typescript-icon /> 2012 - TypeScript is a programming language developed and maintained by Microsoft.
- <logos-babel /> 2014 - Babel is a free and open-source JavaScript transcompiler.
- <logos-webpack /> 2014 - Webpack. Free and open-source module bundler for JavaScript.
- <logos-nextjs-icon /> 2016 - Next.js. Hybrid static & server rendering, TypeScript support, smart bundling, route pre-fetching, and more.
- <logos-nuxt-icon /> 2016 - Build your next Vue.js application with confidence using Nuxt.

</div>
<div class="w-3/10 flex flex-col items-center !opacity-70">
  <img class="w-1/1 h-9/10" src="/assets/nodejs.jpg" />
  <span class="mt-2">Ryan Dahl</span>
</div>
</div>
---

# History of Web Frameworks

<p>
  202x - More powerful ecosystem / Virtual DOM is pure overhead
</p>
  
<div class="flex gap w-1/1">
  <div class="w-7/10 pr-4">
    <h2>JavaScript Ecosystems</h2>
    <br />

- <logos-svelte-icon /> 2016 - <logos-typescript-icon /> Svelte is a new way to build web applications.
- <logos-deno /> 2018 - <logos-rust /> Deno. A modern runtime for JavaScript and TypeScript.
- <logos-swc /> 2020 - <logos-rust /> SWC is an extensible Rust-based platform for the next generation of fast developer tools.
- <logos-esbuild /> 2020 - <logos-go /> esbuild. An extremely fast JavaScript bundler.
- <logos-vitejs /> 2020 - <logos-typescript-icon /> Vite. Next Generation Frontend Tooling.
- <logos-svelte-icon /> 2020 - <logos-typescript-icon /> SvelteKit is a framework for building web applications of all sizes.
- <logos-solidjs-icon /> 2021 - <logos-typescript-icon /> Solid is a declarative JavaScript library for creating user interfaces.

</div>
<div class="w-3/10 flex flex-col items-center !opacity-70">
  <img class="w-1/1 h-9/10" src="/assets/rich.jpg" />
  <span class="mt-2">RIch Harris</span>
</div>
</div>

---

<div class="flex items-center justify-center h-1/1">
  <h1>Rethinking Best Tech Stack for Web App</h1>
</div>
---

# Backend development

<p>
  My choice is Kotlin
</p>

- Node.js / Deno / Bun will continue to grow.
- However, the performance of JS / TS is currently not as fast as server-side languages e.g. Rust / C / Go / Kotlin.
- JS / TS has relatively few stable libraries due to its short history.
- Kotlin has many stable libraries that have been built up since the Java era.
- Go is popular now, but it is still a young language and may risky to use, especially for startups.
- RonR? / Python? / PHP? -> I love static typing language.

---

# Frontend development

<p>
  I am against all existing options
</p>

### ❌ Template Engine (e.g. JSP)

Template engines can be difficult to develop a rich UX like native apps.

### ❌ SPA ✖️ API

SPA is outdated. Initial loading costs are too high.
<br />
Current best practice is between SPA and MPA.

### ❌ (Next.js / Nuxt / etc) ✖️ API

Communicate with Kotlin via HTTP using Next.js / Nuxt / etc.<br />
I will make more issues. (e.g. how to get interface consistency between them.) <br />
Infrastructure management cost is also heavy. (e.g. How to manage version consistency between them.)

---

<div class="flex items-center justify-center h-1/1">
  <h1>My Choice is Svelte and Kotlin</h1>
</div>

---

<div class="flex items-center justify-center h-1/1">
  <div class="flex flex-col items-center mb-12">
    <h1>This is </h1><br />
    <h1 class="kvelte">Kvelte</h1>
  </div>
</div>

<style>
  .kvelte {
    line-height:1em;
    font-size: 100px;
  }
</style>

---

<section class="flex flex-col items-center justify-center h-1/1">
  <div class="flex flex-col items-center h-1/1 mb-4">
    <div class="w-1/5">
      <img class="rounded-1/2" src="/assets/baseballyama.jpg" />
    </div>
    <span class="text-3xl mt-4 text-xl">baseballyama</span>
  </div>
  <div class="flex w-1/1">
    <div class="w-1/2">
      <img src="/assets/flyle.png"/>
    </div>
    <div class="w-1/2 ml-12">
      <ul>
        <li>Software Engineer <a href="https://flyle.io/jp" target="_blank" rel="noopener noreferrer">@Flyle</a></li>
        <li>Maintainer / Team member of <a href="https://svelte.dev/" target="_blank" rel="noopener noreferrer">Svelte.js</a></li>
        <li>Kotlin / Spring Boot / Vue.js / MySQL</li>
        <li><a href="https://twitter.com/baseballyama_" target="_blank" rel="noopener noreferrer">Twitter</a></li>
        <li><a href="https://github.com/baseballyama" target="_blank" rel="noopener noreferrer">GitHub</a></li>
      </ul>
    </div>
  </div>
</section>

---

<section class="flex flex-col items-center justify-center h-1/1">
  <img src="https://prcdn.freetls.fastly.net/release_image/76399/9/76399-9-669d361ecf751e31e59c63a0179adaeb-2400x1260.png?format=jpeg&auto=webp&quality=85%2C65&width=1950&height=1350&fit=bounds" />
  <a class="mt-4" href="https://prtimes.jp/main/html/rd/p/000000009.000076399.html" target="_blank" rel="noopener noreferrer">https://prtimes.jp/main/html/rd/p/000000009.000076399.html</a>
</section>

---

<section class="flex flex-col items-center justify-center h-1/1">
  <img src="https://images.microcms-assets.io/assets/fabc5768811c4ee6b51dc6342205ca70/05e849206a8942a4b54f4feca6591522/UratotsUFlyle.png" />
  <a class="mt-4" href="https://meety.net/articles/t2--gbwkahaqv6" target="_blank" rel="noopener noreferrer">https://meety.net/articles/t2--gbwkahaqv6</a>
</section>

---

<div class="flex flex-col items-center justify-center h-1/1">
  <h1>Kvelte - Demo</h1>
  <a href="https://kvelte.baseballyama.tokyo/" target="_blank" rel="noopener noreferrer">https://kvelte.baseballyama.tokyo/</a>
</div>

---

# Why Svelte

<div class="flex">
  <div class="w-1/2">
    <h3>1. No Virtual DOM</h3>
    <p>Virtual DOM increases runtime size and less performance.</p>
    <h3>2. Easy to learn (No JSX!)</h3>
    <p>
      Svelte has awesome leaning platform.
      <br/>
      We have no time to learn JSX.
    </p>
    <h3>3. Built-in transitions / animations</h3>
```ts {all|2|6}
<script>
	import { fade } from 'svelte/transition';
</script>

{#if condition}
<div transition:fade="{{delay: 250, duration: 300}}">
fades in and out
</div>
{/if}

```
  </div>
  <div class="w-1/2 flex flex-col items-center">
    <h3>The State of JS 2021</h3>
    <img class="w-1/1" src="/assets/jsstate.png" />
  </div>
</div>
---

<iframe src="https://svelte.dev/examples/transition"
  height="150%"
  width="150%"
  style="transform:scale(0.67);-o-transform:scale(0.67);-webkit-transform:scale(0.67);-moz-transform:scale(0.67);-ms-transform:scale(0.67);transform-origin:0 0;-o-transform-origin:0 0;-webkit-transform-origin:0 0;-moz-transform-origin:0 0;-ms-transform-origin:0 0;"
></iframe>

---

# What is Kvelte

### Kvelte is a way to use Svelte as a template engine for Kotlin users.

- 💡 Framework independent

<p>You can also use Kvelte for only one page of your existing app.</p>

- 🚀 High performance

SSR + Hydration and pre-rendering approach.

- ⚡️ Built-in HMR

One of the major problems of existing template engines is inadequate HMR support.

- <logos-typescript-icon /> Built-in TypeScript support

We love types 💜

- 🤝 Type Safety between Kotlin and Svelte (under development)

One of the major problems of existing template engines is no type safety between templates and program.

<style>
  h3 {
    margin-bottom: 8px;
  }
  li {
    font-size: 24px;
  }
  p {
    margin: 8px 0 !important;
    padding-left: 32px;
    font-size: 16px;
  }
</style>

---

# For More Details

<div class="flex items-center justify-center" style="height: calc(100% - 148.5px)">
  <h2>Go <h1><a href="https://github.com/baseballyama/kvelte" target="_blank" rel="noopener noreferrer">GitHub</a></h1> for more details</h2>
</div>

---

# Want to talk more?

<div class="flex flex-col items-center justify-center" style="height: calc(100% - 50px)">
  <div>Please send DM on </div>
  <h1><a href="https://twitter.com/baseballyama_" target="_blank" rel="noopener noreferrer">Twitter</a></h1>
  <br />
  <div>Or register casual talk on</div>
  <h1><a href="https://meety.net/matches/RMgoYMWNGosd" target="_blank" rel="noopener noreferrer">Meety</a></h1>
</div>

<style>
  div {
    font-size: 32px;
  }

</style>