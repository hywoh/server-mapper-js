# server-mapper-js
Win32 PE mapper written in JavaScript. Map your binary on the server before it ever reaches the client and ensure the client only gets what is needed.

## Note
The code will need to be modified to work with your project. You might also want to consider caching the mapped binary.

## Features
- Code virtualizer support (Themida, ...)
- Only the necessary data is returned
- Easily integrated into your JS backend
- Removes reloc table
