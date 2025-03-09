# mlprewatch-emotes

```javascript
CHANNEL.emotes.filter(e=>!e.image.startsWith('https://firlin')).map(e=>[e.image, e.name, `${'https://firlin123.github.io/mlprewatch-emotes/images/loop3/'+encodeURIComponent(e.name) + '.' + e.image.split('.').pop()}`]).map(e=>[e[0],e[1],`,{"name":"${e[1]}","image":"${e[2]}"}`, `,\n    {\n        "name": "${e[1]}",\n        "image": "${e[2]}"\n    }`].join('\n')).join('\n\n')
```