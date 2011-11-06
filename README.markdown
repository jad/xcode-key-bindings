Copy `jad.idekeybindings` into `~/Library/Developer/Xcode/UserData/KeyBindings/`, creating directories as necessary.
Or clone the repo directly into this directory:

    $ cd ~/Library/Developer/Xcode/UserData/
    $ git clone git@github.com:jad/xcode4-key-bindings.git KeyBindings

To see an example of implementing multi-action key bindings look at IDETextKeyBindingsSet.plist.

To use these bindings copy `IDETextKeyBindingsSet.plist` into `/Developer/Library/PrivateFrameworks/IDEKit.framework/Resources/` then open Xcode's Key Bindings preferences and assign a key combination to them.
