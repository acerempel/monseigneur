<template>
    <main>
        <article>
            <h1>{{ $page.title }}</h1>
            <Content/>
        </article>
    </main>
</template>

<style>
    main {
        max-width: 60ch; width: 87.5vw;
        margin: 0 auto;
    }
    h1 { font-size: 2rem; font-weight: bold }
    body { font-family: apple-system, BlinkMacSystemFont, sans-serif }
</style>