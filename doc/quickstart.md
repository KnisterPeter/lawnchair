Quickstart
----------

Getting started with `lawnchair` is super easy:

1. Include the `lawnchair` js file in your html document.
2. Instantiate a `lawnchair` (you can have as many as you want).
3. There is no step 3! you can start persisting data clientside!

Figure 1: index.html

    <html>

Figure 2: app.js

    
    Lawnchair(function(){
        this.save({msg:'hooray!'})
    })
    


