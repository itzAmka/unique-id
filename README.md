# unique-id
A helper function that returns a unique id <br>

**License: MIT**

## How to use?
In your working directory create a folder called helpers and add this file(uid.js). <br>
If you're using frameworks you can create something like this

<pre>
|--src
| --helpers
|   --uid.js
 </pre>
 

If you are not using any frameworks, you can still create the helpers folder and add uid.js file. <br>
<pre>
|--helpers
| --uid.js
</pre>

 ```JavaScript
 // src/main.js
import { uid } from './helpers/uid.js';
uid(); // ⇨ 'gP1aKD40g5e11Pe00ZbK'
```



For other reasons if you are not using JavaScript, feel free to convert this logic in your own programming language.
