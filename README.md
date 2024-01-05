# posthtml-extend-bug
isolating an issue with posthtml-extend

To reproduce the error run `npm install && npm start`

![image](https://github.com/jessehattabaugh/parcel-extend-bug/assets/17991/84a8c743-c1f9-457a-b2da-f3b852fa209a)

Note that when `"strict": false` is added to the .posthtmlrc config the `content` block is successfully replaced, but the `title` block is not

![image](https://github.com/jessehattabaugh/parcel-extend-bug/assets/17991/8c52094c-bfb0-4a15-8365-82e7402d63e4)
