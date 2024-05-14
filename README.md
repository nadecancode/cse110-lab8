# Lab8-Starter

- Name: Allen Zhang
- URL: [here](https://lab8.cse110.ucsd.nade.me)
- Graceful Degradation w/ Service Workers: Since we have cached the requests once users first visited the app, even when they are disconnected and because service workers reside outside of the web application, they will be able to take over the `fetch` responses and use cached responses instead of actually making an internet request. This can be used to implement graceful degradation as we will still be able to maintain a proper style and content layout for HTML, CSS, etc. since service worker can respond these contents. We now can display fallback contents properly to users who have lost their internet connections! This is the definition of graceful degradation.


![](pwa.png)