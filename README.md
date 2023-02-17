# Angular1.2
LifeCycle Hooks

Sure, let's try some easy examples with Toffie, a friendly dog!

ngOnChanges: Suppose you have a component that displays Toffie's age, and you pass Toffie's age as an input property to the component. Whenever the age input changes, you can use ngOnChanges to update the displayed age. For example, if the input age changes from 3 to 4, ngOnChanges will be called and you can update the displayed age to 4.

ngOnInit: Suppose you have a component that displays Toffie's picture and you want to fetch Toffie's picture from a server. You can use ngOnInit to fetch the picture from the server when the component is first initialized. For example, you might use an HTTP request to get Toffie's picture, and then set it as the component's background image.

ngDoCheck: Suppose you have a component that allows users to add Toffie's favorite toys to a list. You can use ngDoCheck to check if a new toy has been added to the list and then perform some custom logic, such as sorting the list of toys or displaying a message. For example, you might use ngDoCheck to check if the list of Toffie's toys has changed and then update a displayed message if the list is empty.

ngAfterContentInit: Suppose you have a component that displays Toffie's pictures in a slideshow. You can use ngAfterContentInit to initialize the slideshow with all of Toffie's pictures. For example, you might use ngAfterContentInit to initialize a variable with an array of Toffie's pictures, and then use ngDoCheck to update the displayed picture when the user clicks the next or previous button.

ngAfterContentChecked: Suppose you have a component that displays Toffie's picture and allows the user to rotate the picture by clicking a button. You can use ngAfterContentChecked to check if the picture has been rotated and then perform some custom logic, such as displaying a message or updating Toffie's profile. For example, you might use ngAfterContentChecked to check if the picture has been rotated and then update Toffie's profile with the new picture.

ngAfterViewInit: Suppose you have a component that displays a picture of Toffie and allows the user to zoom in on the picture. You can use ngAfterViewInit to initialize the zoom library and render the zoomed-in picture. For example, you might use ngAfterViewInit to initialize the zoom library, set the zoom level to 1, and then render the picture with the zoom level applied.

ngAfterViewChecked: Suppose you have a component that displays Toffie's picture and allows the user to add a caption to the picture. You can use ngAfterViewChecked to check if the caption has been added and then perform some custom logic, such as displaying the caption or updating Toffie's profile. For example, you might use ngAfterViewChecked to check if the caption has been added and then update Toffie's profile with the new caption.

ngOnDestroy: Suppose you have a component that subscribes to Toffie's feed and displays new posts as they arrive. You can use ngOnDestroy to unsubscribe from Toffie's feed when the component is destroyed, to prevent memory leaks. For example, you might use ngOnDestroy to unsubscribe from Toffie's feed when the user navigates away from the page or closes the browser.
