# Data for io games

There are now hundreds of "io games" — simple browser MMOs that allow you to play with one click. There are also a lot of portals that refer traffic to these games. Developers have a hard time keeping track of all these portals, and submitting their games. This is a way for portal owners, game developers and interested players to access and contribute to open-source data about io games.

## Using

You can clone or download this repository, and access the data in `data.json`. It contains an array of objects with data about io games such as name, URL and thumbnail.

## Format

Each game is a JSON-object with this structure:

 - `name`: string, Example.io
 - `url`: string, https://example.io/
 - `synopsis`: string, short description
 - `description`: string, extended description
 - `thumbnail`: string, image URL
 - `published`: string, yyyy/mm/dd
 - `secure`: boolean, HTTPS connection
 - `developer`: object
   - `name`: string, Developer
   - `twitter`: string, handle

## Contributing

Simply submit a pull request to add, edit or remove your game. Do not make changes to games that you don't own (verification may be required).

## License

MIT License

Copyright (c) 2018

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
