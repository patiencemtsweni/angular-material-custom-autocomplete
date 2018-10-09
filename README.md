# CustomAutocomplete

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 6.2.2.

This is a custom component which wraps the exisiting angular material autocomplete component and adds the following:

  * A loader
  * A clear button to clear the user's input
  
## Inputs

@Input()
displayWith: string
Used to set the value (@Input() displayWith) in angular material autocomplete component

@Input()
loaderColor: string
Used to set the loader's color

@Input()
options:[]
An array of the options that must be displayed for the user to select

@Output()
beginSearch(): EventEmitter()
Used to fire the filter/search method from the calling component

@Output()
optionSelected: Eventemitter()
Used to emit the event that must take place when the user selects an option 

