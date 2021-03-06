# bills-api

## A Basic Bills-Tracking RESTful API

Starting to track my bills a little more closely seemed like a
kind of not useless thing to do. :stuck_out_tongue:

### Criteria

* Uses JWT authentication
* [Hunchentoot Web Server](https://edicl.github.io/hunchentoot/)
* Postgres using [Postmodern](https://marijnhaverbeke.nl/postmodern/) 

Endpoints:
| Method      | URL           | 
| ------------- |:--------------| 
| Post   | /authorize/   | 
| Get     | /userId/bills      | 
| Get| /userId/bills/billId| 
| Put    |/userId/bills/billId   | 
| Post   |  /userId/bills  | 
| Delete   |/userId/bills/billId   | 
## License

MIT License

Copyright (c) 2021 Brian Beegan

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

