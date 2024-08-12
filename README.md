# Background Remover
As straightforward as its name, this program is used for removing background from an image and make it transparent. It's a CLI based program though, so you have to run the command in order to use it. I have already told you in the program the function of each command.

![Overview](overview.png)

The program is developed in Python and runs on two background remover engine.
* "remove.bg" which is an API that use Artificial Intelligence to select the main object and remove the background. This engine is easy to use, and it provide image search from url. The quality of the outcome image is also high as well. However, The number of free uses of this api is rather low (Only 50 uses per month), so I don't quite recommend you to use this engine for now.

* Pillow is another background remover engine that is a module from python. This one is completely free to use, but a bit harder to use. Because you need to input the RGB color code of the background you want to remove, which may make it isn't quite user friendly.

**Here is the example of the image**

![Before](before.png)

Before removing the white background

![After](after.png)

After removing the white background