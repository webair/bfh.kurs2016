# Segue Example
Add a new ViewController in the Storyboard and set it up to work with the AddBuzzwordViewController. Add Elements to enter a text (TextView with "BorderedTextView" as custom calss), a cancel button and a save button. 

Connect a segue between the ListBuzzwordViewController AddButton and the new AddBuzzwordViewController so that the new AddBuzzwordViewController gets displayed. Make sure that the Buzzword store get set when performing the segue (see "Segues - Passing Data").

Implement the AddBuzzwordViewController so that:

- if the user tappes the cancel button the ViewController gets dismissed
- if the user tappes the save button, the content of the textview gets added to the store, and the viewcontroller gets dismissed

## Perform segue 
Remove the segue from the add button and add a segue between the view controllers. 

Implement the ListBuzzwordViewController so that:

- if user tappes the add button, the segue gets performed programtically

## Without segue 
Remove the segue from the previous example. Add an identifier to the 'AddBuzzwordViewController'. 

Implement the ListBuzzwordViewController so that:

- if user tappes the add button, 'AddBuzzwordViewController' gets initialized from the storyboard and the store presented without the segue. Do not forget to set the store.
 

## Keywords
- Storyboard / Segues
- Custom View Class
- UIButton / IBAction / IBOutlet
- Type Casting


## Inputs
- [Segues - Passing Data](http://jamesleist.com/ios-swift-passing-data-between-viewcontrollers/)
- [Connect the UI to Code](https://developer.apple.com/library/ios/referencelibrary/GettingStarted/DevelopiOSAppsSwift/Lesson3.html)
- [Swift Type Casting](https://developer.apple.com/library/ios/documentation/Swift/Conceptual/Swift_Programming_Language/TypeCasting.html)