# dfalertbox

An alert dialog for flutter aps

## How to use

FloatingActionButton(
  onPressed: () async {
    await CustomAlertBox.displayAlertBox(
        context: context,
        willDisplayWidget: Container(
          child: Text('My custom alert box, used from example!!'),
        ));
  },
  tooltip: 'Show Custom Alert Box',
  child: Icon(Icons.message),
)

#   d f a l e r t b o x  
 