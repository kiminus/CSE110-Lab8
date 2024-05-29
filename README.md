# Lab8-Starter

zilin liu A17691286

[link to repo](https://github.com/kiminus/CSE110-Lab8)

[link to page ](https://kiminus.github.io/CSE110-Lab8/)


### How are graceful degradation and service workers related? (Answer this after doing the part below)

- when the user client device has limits, for example when the internet speed is limited, we can use service worker to only fetch the resources once and reuse them from the cache. In this way, besides the initial communication overhead, we save a lot of bandwidth on transimitting static images and resources. 

- this is significant to implement local first pattern where the cached data stored by the service workers can cache resources and support offline user experience. In this way, we have more assets to use to support graceful degradation in offline mode. 