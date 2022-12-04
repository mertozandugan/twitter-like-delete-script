# twitter-like-delete-script



https://twitter.com/{username}/likes Açılır
Öğeyi denetle console sekmesi açılır ve aşağıdaki kod yapıştırılır

```
setInterval(() => {
  for (const d of document.querySelectorAll('div[data-testid="unlike"]')) {
    d.click()
  }
  window.scrollTo(0, document.body.scrollHeight)
}, 1000)
```
