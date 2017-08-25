### Redux + ServiceWorker = Offline React - Zack Argyle - 5:00 PM
Speaker: [Zack Argyle](https://github.com/zackargyle) <br>
Topic: Redux + ServiceWorker = Offline React <br>
Twitter: [@ZackArgyle](https://twitter.com/ZackArgyle) <br>
Presentation: N/A <br>
Local: N/A <br>

**Notes:**
- https://github.com/pinterest/service-workers
- Service workers are essentially the secretary for your app - they'll make requests to servers for you.
- Service Workers
    + Network Proxy
    + Precaching
    + Runtime Caching
    + Push Notifications
    + Background Sync
    + Offline Network Management
- Service Worker Fetch Strategies
    + Prefer cache
    + Cache only
    + Offline only
    + Network only - don't cache anything
    + Race/Fastest - sometimes it takes longer to look up from cache than to request from the server
- How to register a Service Worker:

```
if ('servieWorker' in navigator) {
    navigator.serviceWorker.register('sw.js');
}
```

- App Shell
    + Generic/Cacheable
    + Progressively loads app
    + Fast TTFP
    + **If you care about SEO, continue to server render**