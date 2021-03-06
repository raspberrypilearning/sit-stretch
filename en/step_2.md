## Prepare your character

--- task ---

**Online:** open the [starter project](http://rpf.io/relax-stretch-on){:target="_blank"} in Scratch.

**Offline:** open the [project starter file](http://rpf.io/p/en/relax-stretch-go){:target="_blank"} in the Scratch offline editor. If you need to, you can [download and install Scratch here](https://scratch.mit.edu/download){:target="_blank"}.

You should see a character sprite and two arrows: up and down.

![starter project](images/starter_project.png)

--- /task ---

First, you will give **character 1** a name.

--- task ---

Select the **character 1** sprite.

Click on the **dialogue box** that shows the sprite's name. We have named this sprite **Nadia**. Replace `character 1` with the name of your choice.

![select character 1 sprite name](images/select_character1_name2.png)

--- /task ---

Next, you will give the **Nadia** sprite setup blocks such as `position`{:class="block3motion"} on the Stage.

--- task ---

With the **Nadia** sprite still selected, add a `when green flag clicked`{:class="block3events"} block.

Below that, add a `go to x: y:`{:class="block3motion"} block with `x`{:class="block3motion"} set to `70` and `y`{:class="block3motion"} set to `-25`. 

Add a `switch costume to`{:class="block3looks"} block, and set the costume to `at rest`{:class="block3looks"}.

Finally, add a `wait`{:class="block3control"} block and set it to `2` seconds so that the first exercise doesn't begin too suddenly:

![Nadia sprite icon](images/nadia_sprite.png)

```blocks3
when flag clicked
go to x: (70) y: (-25)
switch costume to (at rest v)
wait (2) seconds
```

--- /task ---

--- save ---
