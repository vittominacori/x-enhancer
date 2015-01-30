x-enhancer
================

Custom Polymer element for text enhancement.

## Installation

```
$ cd /your-project-root/
$ git clone https://github.com/vittominacori/x-enhancer.git
$ cd x-enhancer/
$ bower install
```

or install it via bower

```
$ bower install x-enhancer --save
```

## Try it

```
$ cd .. # You'll want to run the web server from the parent directory.
$ python -m SimpleHTTPServer
```

Go to [http://localhost:8000/x-enhancer/demo.html](http://localhost:8000/x-enhancer/demo.html) to see it in action.

## Usage

```
<x-enhancer
    id="element"
    text="Italy"
    title="Hello, I'm &lt;x-enhancer&gt;, a custom Polymer element...">
    <span>And this is my client-provided content!</span>
</x-enhancer>
```

## Note

Current version only find country capital.
More will coming...
