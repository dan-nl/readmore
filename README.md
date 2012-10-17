# readmore

a jQuery plug-in that allows you to load additional content into a page via an XMLHttpRequest based on a read-more link in the content.

```html
<a href="/path-to-next-content-item" id="read-more">Read more</a>
```

```javascript
jQuery('#news-articles').readMore({ read_more_link : '#read-more' });
```