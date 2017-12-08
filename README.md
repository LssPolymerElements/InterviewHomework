# LSS Interview Homework Skeleton #

## GETTING STARTED ##
* Fork this repo
* Install NodeJs 
* Install polymer-cli globally `npm install -g polymer-cli` 
* Run `npm install`

## DEVELOPMENT ##
* Lint the project: `npm run lint` 
* Serve the project: `npm run serve`
* Compile Typescript on save `npm run watch`

## Instructions: ##

Create a three page Polymer 2 web application starting with a fork of this repo which contains the app skeleton to get you off and running.  Please commit as you go and submit an emailed zipped git repository with the completed project to mike-plumb@leavitt.com.  

Do not spend an excessive amount of time on the project.  If you have spent over four hours in total but are not quite finished, don’t worry! Just submit what you have and we will take a look. 

## Requirements: ##

 - Single page application. 
 - Responsive mobile / desktop design. 
 - Use [Polymer Material Inputs](https://www.webcomponents.org/author/PolymerElements) for [inputs(https://www.webcomponents.org/search/paper-input)] and [buttons(https://www.webcomponents.org/element/PolymerElements/paper-button)] . 
 -  Page should closely follow [mockup](https://app.moqups.com/aaron@aarondrabeck.com/rekW1P2jz8/view).  
	 -  [Page 1 (see mock-up)](https://app.moqups.com/aaron@aarondrabeck.com/rekW1P2jz8/view/page/a2b41c7ff)
	   - Header of the page should contain navigation for the app. Three buttons.  Page 1, Page 2, and Results.
	   - Top half of the page is a simple example of text with an image. (The various font sizes and styling is to help showcase basic CSS knowledge.) 
	   -  Bottom half of the page is a simple form calculator.
	   -  The default calculator has an image, two inputs and a button
	   - Upon clicking the Calculate button
	   - Hide picture, inputs and button
	   - Perform calculation based on inputs. 
	   - Calculate formula: employees * (modification percent/100) * 150
	   - Show result text with a dollar amount and recalculate button (See the mockup and click on the Calculate button to see the results example). 
	   - Recalculate button upon click should:
	    - a. reset the page to the default calculator.
	    - b. Hide the result text and recalculate button.
	    - c. Show initial image, two inputs and  button.
	    - d. Reset entered text in inputs. 
	 - [Page 2 (see-mockup)](https://app.moqups.com/aaron@aarondrabeck.com/rekW1P2jz8/view/page/a1a4f1538)
	 - Calculator with the same functionality as Page 1 should now be
   located at the top of the page. 
   	- The bottom of the page contains text with an image. 
	- The result amount from the calculator on this page should be shown in the bottom text. (This is in addition to showing
   the Calculator results in the top half of the page.) 
	 - [Page 3 (see-mockup)](https://app.moqups.com/aaron@aarondrabeck.com/rekW1P2jz8/view/page/a9a81d7d8) 
	 - This page should contain a simple list of result dollar amounts from anytime a calculator on page one or page two is used.
	 - On Initial Load this list should be empty.  After one calculator submit it should have one result.  After two calculator submits it should have two items in the list and so on. 
   	  -  Do not worry about persisting data on page reload

# Docs
[Polymer](https://www.polymer-project.org/2.0/docs/devguide/feature-overview)

[Web Components](https://www.webcomponents.org)

[Polymer Typescript](https://github.com/LssPolymerElements/polymer2-ts)

[Paper Styles](https://www.webcomponents.org/element/PolymerElements/paper-styles)





