## About
A simple jekyll page which list some Web Frameworks for Node.js

## How to add a Node web framework?

Fork this repository and just include a file on the `_includes` directory.

The file must follow the code below:

``` html
<section class="box">
    <header class="box__header js-toggle-header">
        <h1>MODULE NAME</h1>
    </header>
    <div class="box__main js-toggle-github" data-github="/github-user/module-repository">
        {% include content.ext %}
    </div>
</section>
```

Look this example:

``` html
<section class="box">
    <header class="box__header js-toggle-header">
        <h1>Connect</h1>
    </header>
    <div class="box__main js-toggle-github" data-github="/senchalabs/Connect">
        {% include content.ext %}
    </div>
</section>
```

Create a printscreen of your landing page module, put it in the `images` directory in PNG format and 220x160 size.
The last step is adding your module in the `index.html` using the command: `{% include my_module.ext %}

All data is consumed from Github API - <http://developer.github.com>

## Rules

Only web frameworks for node.js will be allowed.

## Author

Caio Ribeiro Pereira <caio.ribeiro.pereira@gmail.com>

Twitter: <http://twitter.com/crp_underground>

Blog: <http://udgwebdev.com> or <http://udglinux.com>

## License

The MIT License (MIT)

Copyright (c) 2013 Caio R. Pereira

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
