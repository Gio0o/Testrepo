# Testrepo

## Here is a header

#### Subheader 1

I am not sure if you know markdown - it is like a text language. Github automatically readers any file with the extension <code>.md</code> as markdown. It allows you to do cool stuff like these headers, subheaders, and code:

```
    # Function to visualize GPS
    function vizGPS(data) {
        var foo = "This is a tmp variable in JS";
        var bar = "Here is another...foo and bar are conventions for fake variable names";
        return foo;
    }
```

<strong>NOTE:</strong> a README file (and other markdown files) are often just to describe / document / provide info.

#### Subheader 2

Wow - if you want to see how I wrote all of this you can click on this file in Github and go to "raw" or "code".


## To Do

1. Pull my changes to your local machine: <code>git pull origin master</code>
2. Make some changes on your local machine
3. Save changes: <code>git add README.md</code>
4. Queue changes: <code>git commit -m "Changed README to XXX"</code>
5. Push changes to <strong>master branch</strong>: <code>git push origin master</code>


### Helpful info

* <strong>origin</strong> is a reference to your local machine
* all folders on your computer = directories
* I often just say <strong>dir</strong> for directories
* Remember: git is all about pulling others' changes (pull), adding changes (add), queue the snapshot of all changes (commit), and pushing (push).

#### Git structure

* Git uses a tree structure
* You always have the <strong>master branch</strong>
* They are called <strong>branches</strong> because it is a tree structure and they are funny!
* Branches are nice because you and I can be on the same repo but have our own branches while we work on different components (or the same) of the same repo - but then we would want to incorporate the changes on both of our branches into the main (e.g. master) branch...
* If and when we are ready to incorporate a branch into another branch (e.g. development branch into master branch) we do a <strong>merge</strong>
* If we are currently on the master branch and want to merge in the <strong>dev-branch</strong>: <code>git merge dev-branch</code>

<strong>NOTE: </strong> we will get into branches etc with time. Do not stress about a ton of information all at once.

#### Command Line Interface (CLI)

* Terminal = command line interface = CLI (for OS X)

```
    pwd                 # print working directory (your current location on your machine)
    ls                  # list all directories / files in your current location
                        # if Testrepo appears when you ls...
    cd Testrepo         # change directory into Testrepo
    git status          # see status of current repo that is in current dir
```
# Hey Oliver

#### I am just making some changes to the readme

```
    this stuff is so much fun
    See you soon,
    Gio
```

# Hey Gio

#### Great work bud

```
    so awesome you are getting this down!
    I tend to tab (4 spaces) with code like you can see here.
    Tabbing in this way is just a style - not a right or wrong
    However! it is a good idea to be one the same page
    about certain styling conventions when collaborating...
    so read below...
```

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
