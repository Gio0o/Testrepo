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
