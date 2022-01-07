
# EDTS-TRACKER

Web tracker for passed analytics to data team.




## Code Usage/Examples

```javascript
npm install @adreansyah/edts-tracker --save
```

```javascript
import { 
    trackcheck, 
    getCookie, 
    setCookie 
} from '@adreansyah/edts-tracker';
setCookie({ 
    keyname: "session_id",
    keyvalue: `${UUIDjs.create(4).toString()}`,
    minutes: 5 //example expiry 
})
cont cookie = getCookie('session_id')
trackcheck({
    types: "page_view_web",
    link_label: null,
    pageName: "home",
    url: '/api/tracker',
})
```


## Acknowledgements

 - [Lerna.js](https://lerna.js.org/)
 <!-- - [Awesome README](https://github.com/matiassingers/awesome-readme)
 - [How to write a Good readme](https://bulldogjob.com/news/449-how-to-write-a-good-readme-for-your-github-project) -->


## Authors

- [@sg-edts](https://sg-edts.com/)

