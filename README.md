# build-context
BuildContext is a locator that is used to track each widget in a tree and locate them and their position in the tree. The BuildContext of each widget is passed to their build method. Remember that the build method returns the widget tree a widget renders. Each BuildContext is unique to a widget.
