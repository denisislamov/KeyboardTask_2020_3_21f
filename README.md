# KeyboardTask_2020_3_21f

## - The Keyboard Task --

We have prepared a project template with several buttons and one input field.
Please check scene called "Scene" in the root of the Assets.

Try pressing A, B or C buttons. This will add a character to the end of the input field.
Then it reactivates the input field, and this will select and highlight all the text.
This is the wrong behavior.

The challenge is to create a new class that will implement the InputField.
The new extended class (MyInputField) should make the InputField work with the UI buttons in the same way as manual input does.

- [X] Focus should remain on the input field when the user interface buttons are pressed. 
      PS: Lost focus have a bit different behaviour.
- [X] Caret must remain in last position.
- [X] Pressing UI button when the text is selected should replace it with corresponding character.
- [X] Selection should dissapear, the caret should move to the position after this symbol.
- [X] Backspace, Left and Right buttons should be implemented. Left and Right buttons should move the cursor over the input field.
- [X] Virtual keyboard must be consistent and should not interfere with manual input from a real keyboard,
- [X] The bonus is to implement multiple keystrokes on the button hold, as on a real keyboard.

* Try not to change the base InputField (Original) class, or make as few changes as possible.

In this project you will also find InputFieldOriginal class, which is just a copy of regular InputField class from the Internet.
You can use either this class to check what is happening inside, or use the usual from the Unity package.
