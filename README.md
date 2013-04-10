pesima-node
===========

Aplikasi ini membuatkan template projek dengan pantas seperti landing page, documentation page menggunakan Twitter Bootstrap dan Node.js (pada masa ini hanya support express template)

## Pemasangan (Buat masa ini sila buat pemasangan melalui Git - Kaedah 2)

Kaedah 1:

  `$ npm install -g https://github.com/pesima/pesima/tree/pembangunan`
  
Kaedah 2:

  1. `$ git clone https://github.com/pesima/pesima.git`
  2. `cd pesima && git checkout pembangunan`
  3. `npm install`
  
## Panduan Penggunaan

Membuat projek (Default enjin css adalah `less`, dan enjin template adalah `jade`):

    $ pesima-node projek
    $ cd projek
    $ npm install
    $ node app.js

Layari `http://localhost:3000`

## Teknikel

 * Port: sama dengan default port ExpressJs