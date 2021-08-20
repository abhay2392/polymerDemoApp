# Your first Polymer element


## Running the codelab without Chrome Dev Editor

If you're not using CDE, you'll need to install some command-line tools to manage
dependencies and to run the demo.

1.  Download and install Node from [https://nodejs.org/](https://nodejs.org/). Node includes the node package manager command, `npm`.

2.  Install `bower` and `polyserve`:

        npm install -g bower polyserve

3.  Clone this repo:
        
        
4.  Change directory to your local repo and install dependencies with `bower`:

        cd polymer-first-elements
        bower install
        
5.  To preview your element, run `polyserve` from the repo directory:

        polymer serve
        
    Open `localhost:8080/components/icon-toggle/demo/` 
