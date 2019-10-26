### Touch Emulator
---
https://github.com/hammerjs/touchemulator


```js
// tests/web-platform-tests/resources/tesharnessreport.js

var metadata_generator = {
  
  currentMetadata: {},
  cachedMetadata: false,
  metadataProperties: ['help', 'assert', 'author'],
  
  error: function(message) {
    var messageElement = document.createElement('p');
    messageElement.setAttribute('class', 'error');
    this.appendText(messageElement, message);
    
    var summary = document.getElementById('summary');
    if (summary) {
      summary.parentNode.insertBefore(messageElement, summary);
    }
    else {
      document.body.appendChild(messageElement);
    }
  },
  
  
};
```

```
```

```
```


