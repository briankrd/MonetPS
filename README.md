This small project tries to simulate the color palettes of Google's "Material You" design language used by Android's "Monet" engine in order to be implemented in projects made in Kustom applications such as KWGT, KLWP or KLCK that use the colorization of elements based on the wallpaper.

## MonetPSK for easy implementation

I really wanted to put the code for whoever wanted to do it by themselves but the truth is that it is very tedious and it made me lazy (why lie), so I decided to create a komponent and problem solved 😀👍.

## How to implement MonetPS with MonetPSK

When downloading the komponent from the releases section of this repository, it would be necessary to follow the following steps:

• Move the MonetPSK file to the "komponents" folder which is inside the "Kustom" folder which by default is on the internal storage of the target device.

• Open your project where you want to implement MonetPS.

• At the top right, tap the plus icon (+).

• Search and Add MonetPSK entering to the "Komponents" option.

• Go to the bottom of the list of the main items of your project.

• Open MonetPSK and then go to the "Globals" tab.

• Copy the "monet" folder by selecting the selection box and tapping the copy icon in the top right (or in the drop down menu and then "copy").

• Go back to the root of your project and paste the folder into the "Globals" tab.

> I have no idea how it will happen in your case but in my case, I had to copy the "monet" folder and it is copied empty, which has led me to copy each of the folders and elements within it one by one, given that this is your case, it would be necessary to copy the entire content of the "monet" folder of the component to your project one by one 🫥.

• Then it would be necessary to link the elements that are going to be colored to some palette using the global reference.
