# Design and Styling

This can be used as a reference as we go along with work. I will post it into each and every repo we work on together (and make sure I do that if I forget!). Most of this styling is in reference to Javascript code (JS = Javascript). Remember, Java is not Javascript in any way. They just have almost the same name. They are as different as C and Python (though technically this is not completely true but it is true for our purposes).

Some styling notes that I follow and I think look good:

* two ways to make comments in JS

```
    /* This is a comment that can be multiple lines */
    var foo = "this is code";

    /*
        Everything within the slash and star thingie = commented
        var bar = "so this is commented";
        ...this is all a comment...
    */
    function foo() {
        var bar = 6;

        // here is a single-line comment in a function called foo

        return bar;
    }
```

* no space between function name and <code>()</code>

```
    // For example
    function foo() {
        var bar = 6;
        return bar;
    }

    // Do NOT do this!!!!
    function foo (){
        var bar = 6;
        return bar;}

    /*
        Although the second function technically runs the same...
        I just cannot deal with how weird that looks.
        I hate it! Its crazy looking!

        ...

        but!

        as much as it kills me to say this...
        sometimes you do break style rules.
        They are NOT set in stone
    */
```

* add space on each side of <code>=</code>

* use <code>camelCase</code> and not <code>hyphen-naming</code> for variables, functions, etc

```
    // Make variables look like this
    var thisVariable = 6;

    // ...and not like this
    var not-this-way = 4;
    var and_not_like_this = 3;

    // EXCEPTION! = globals
    var GLOBAL_VAR = "this is a global variable which is special";
```

* I like the idea of dashes for dir names like <code>this-is-a-dir</code> 
