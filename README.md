# UserInputEvents
Easily create bindableEvents that correspond to user inputs!
<br>
<br>
<br>
# Quickstart Guide
Step 1: Create a ModuleScript inside StarterPlayer<StarterCharacterScripts. Name it whatever you want. <br> <br>
Step 2: Paste code into ModuleScript. <br> <br>
Step 3: In a separate localscript, require the modulescript. <br> <br>
Step 4: Invoke the init() function in order to create a folder for the events to go inside of. <br> <br>
Step 5: To create a bind, invoke the CreateBind() function like so: local bind = UserInputEvents.CreateBind(Enum.KeyCode.F) <br> <br>
Step 6: To listen for the bind you just created do this: bind.Event:Connect() <br> <br>
