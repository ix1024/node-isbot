# node-isbot

### install

    npm install node-isbot --save

### usage

    
    
    const isbot = require('node-isbot');
    isbot(req.headers['user-agent'])

    isbot("Googlebot/2.1 (+http://www.google.com/bot.html)") // true
    isbot("Googlebot") // true
    isbot("yahoo") // true
    isbot("Sogou Pic Spider") // true
    isbot("PHP") // true
    isbot("Baiduspider") // true
    isbot("360Spider") // true
    isbot("java/") // true

    isbot("Mozilla/5.0 (Windows NT 6.1; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/60.0.3112.90 Safari/537.36") // false

