# Steps
- Create a utils folder and add createPassword.js & savePassword.js.
- Have a node_modules folder
- Run the `index.js` file with `node index.js`

# Available options
```
'- l, --length <number>', 'password length', '8 (default)'
'-s, --save', 'save password to passwords.txt'
'-nn, --no-numbers', 'remove numbers'
'-ns, --no-symbols', 'remove symbols'
```

# Examples
- `node index.js` => Generated password: 0cKR9TH1

- `node index.js -l 6 -s -nn -ns` => Generated password: qQcwkp
The password has been copied to the clipboard.
Password saved in passwords.txt
