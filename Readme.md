# **Remove an Element on Html using JS.**

We can remove an element on HTML code from javascript.


We´ve an example of element:

    <body>
        <div class="chat">Charlemos un rato</div>
    </body>

We can remove it using the next syntax:

    <script>

        const removeElement = document.querySelectorAll('.chat');
        removeElement.forEach(el => el.remove());
    
    </script>

## **Why this construction code??**

**First**

We create a variable where we store the part of the element on the DOM that we need to remove.

    const removeElement = document.querySelectorAll('.chat');

**Second**

We indicate to the variable, in this case "removeElement", that we want to remove it.

    removeElement.forEach(el => el.remove());

As we are used _**"querySelectorAll"**_, we´ve used on the remove code the loop function _**"forEach(el => el.remove())"**_.
