# server-mapper-js
Win32 PE mapper written in JavaScript. Map your binary on the server before it ever reaches the client and ensure the client only gets what is needed.

## Note
The code will need to be modified to work with your project. You might also want to consider caching the mapped binary

## Features
- Code virtualizer support (Themida, VMProtect, ..)
- Easily integrated into your Node backend
- Only data necessary data is sent to the client
- Imports are fetched from the client with support for forwarded imports and [API sets](https://learn.microsoft.com/en-us/windows/win32/apiindex/windows-apisets).
- Includes a C++ client example to handle requests from server
- Fixes [relocations](https://0xrick.github.io/win-internals/pe7/)
