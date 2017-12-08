# LSS Interview Homework Skeleton #

## GETTING STARTED ##
* Clone this repo
* Install NodeJs 
* Install polymer-cli globally `npm install -g polymer-cli` 
* Run `npm install`

## DEVELOPMENT ##
* Lint the project: `npm run lint` 
* Serve the project: `npm run serve`
* Compile Typescript on save `npm run watch`

## Instructions: ##

Create a three page Polymer 2 web application by cloning this repo that contains the app skeleton needed to get you started. Please commit as you go and submit an emailed zipped git repository with the completed project to mike-plumb@leavitt.com.

Do not spend an excessive amount of time on the project.  If you have spent over four hours in total but are not quite finished, don’t worry! Just submit what you have and we will take a look.

[You can view the mockup here](https://app.moqups.com/aaron@aarondrabeck.com/rekW1P2jz8/view)

## Requirements: ##

 - Single page application. 
 - Responsive mobile / desktop design. 
 - Use [Polymer Material Elements](https://www.webcomponents.org/author/PolymerElements) for this assignment such as:
     - [paper-input](https://www.webcomponents.org/element/PolymerElements/paper-input)
     - [paper-button](https://www.webcomponents.org/element/PolymerElements/paper-button)
 -  Page should closely follow [mockup](https://app.moqups.com/aaron@aarondrabeck.com/rekW1P2jz8/view).  
	 - [Page 1 (see mock-up)](https://app.moqups.com/aaron@aarondrabeck.com/rekW1P2jz8/view/page/a2b41c7ff)
	     - Has calculator with two states (calculator & results)
	     - Performs calculation based on paper-input values and then switches to the result state. 
	     - Uses this formula to calculate the amount saved: employees * (modification percent/100) * 150
	     - Shows amount saved as a dollar amount on the results state
	     - The recalculate button on the results state should do these things when clicked:
	         - a. Switch from results to the calculator state.
	         - b. Resets the paper-input's values to 0.
	 - [Page 2 (see-mockup)](https://app.moqups.com/aaron@aarondrabeck.com/rekW1P2jz8/view/page/a1a4f1538)
	     - Has calculator with the same functionality as Page 1 that should now be
   located at the top of the page. 
	     - The amount saved from the calculator on this page should additionally be shown in the bottom text.
	 - [Page 3 (see-mockup)](https://app.moqups.com/aaron@aarondrabeck.com/rekW1P2jz8/view/page/a9a81d7d8) 
	     - This page should contain a simple list of the amounts saved from anytime a calculator on page one or page two is used.
	     - On Initial Load this list should be empty.  After one calculator submit it should have one amount saved. After two calculator submits it should have two items in the list and so on.
	     - This page should also recalculate and display the standard deviation of the amounts saved in the list whenever an item is added.
   	     - Do not worry about persisting data on page reload.
	      
## Resources

[Polymer](https://www.polymer-project.org/2.0/docs/devguide/feature-overview)

[Web Components](https://www.webcomponents.org)

[Polymer Typescript](https://github.com/LssPolymerElements/polymer2-ts)

[Paper Styles](https://www.webcomponents.org/element/PolymerElements/paper-styles)

[Flex Layout](https://elements.polymer-project.org/guides/flex-layout)





