# tp-eslint-git

C:\Users\Nani\tp-eslint-git>npx eslint --fix .

C:\Users\Nani\tp-eslint-git\app.js 2:1 warning Unexpected console statement no-console 4:3 warning Unexpected console statement no-console

C:\Users\Nani\tp-eslint-git\utils.js 2:1 warning Unexpected console statement no-console 4:3 warning Unexpected console statement no-console

✖ 4 problems (0 errors, 4 warnings)

C:\Users\Nani\tp-eslint-git\app.js 2:1 warning Unexpected console statement no-console 4:1 warning Unexpected console statement no-console 4:1 error Expected indentation of 2 spaces but found 0 indent

✖ 3 problems (1 error, 2 warnings) 1 error and 0 warnings potentially fixable with the --fix option.

C:\Users\Nani\tp-eslint-git>npx eslint --fix app.js

C:\Users\Nani\tp-eslint-git\app.js 2:1 warning Unexpected console statement no-console 4:3 warning Unexpected console statement no-console

✖ 2 problems (0 errors, 2 warnings)

C:\Users\Nani\tp-eslint-git>npx eslint --fix .

C:\Users\Nani\tp-eslint-git\app.js
  2:1  warning  Unexpected console statement  no-console
  4:3  warning  Unexpected console statement  no-console

C:\Users\Nani\tp-eslint-git>npx eslint --fix index.js

C:\Users\Nani\tp-eslint-git\index.js
   3:3  warning  Unexpected console statement  no-console
  11:5  warning  Unexpected console statement  no-console
  17:1  warning  Unexpected console statement  no-console
  22:3  warning  Unexpected console statement  no-console
  33:3  warning  Unexpected console statement  no-console
  37:3  warning  Unexpected console statement  no-console
  48:3  warning  Unexpected console statement  no-console
  49:3  warning  Unexpected console statement  no-console
  53:3  warning  Unexpected console statement  no-console

✖ 9 problems (0 errors, 9 warnings)