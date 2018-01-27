# Hivesy Coding Test
------

### Please follow these directions.

##### Note that any direction given is specific and should be followed. Any detail not mentioned is open to you as the developer to make the decision. Any decision is acceptable but the developer should be able to describe their reasoning and will be asked to explain it. Also, if you feel like you won't be able to complete the entire test, please choose which parts to work on, and again be prepared to explain your reasoning. If you have any questions regarding this test, please email me at justin@hivesy.co.

1. Set the primary app color to #42c5f4

2. Calendar Page has 2 issues, please debug and fix
  * The stories underneath the calendar should redirect to the 'Story' view
  * The top left menu icon no longer opens the app drawer

3. Create a new page/view called 'Pictures'
  * Place link underneath 'Timeline' in the App Drawer
  * Use the following API: https://jsonplaceholder.typicode.com/photos to populate 'Pictures' view
  * Place the images in cards from: https://docs.nativebase.io/Components.html#card-image-headref
  * Set the text above the image to the image title
  > If the image title is longer than 12 characters, cut off the ending followed by '...' to show the user the title is shortened
  * Set the text note to 'Hivesy'
  * Set the thumbnail source as thumbnailUrl
  * Set the card image as image
  * When clicking on any card, take the user to a new view showing only the image.
  > This view shouldn't be a modal, but a new page/view
