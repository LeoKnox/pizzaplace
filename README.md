# pizzaplace
blazor pizza ordering app

Summary:
A pizza ordering app, allowing users to order one or more pizzas. This
will incorporate the Blazor technology allowing for the creation of a
single page app without the use of a javascript front end. This is useful
for the ability to create apps using the same technology one the front end
as well as the backend. Such technologies are also important for the
creation of progressive web apps. In which your web app can be run from
the web or packaged into a window app for an offline experience. Blazor
however because of its basis on c# and dotnet can be run using xamarin
for mobile and cross platform devices. Microsoft has also given demonstrations
using electron to create apps that run on a variety of platforms.

Since Blazor is a new and experimental technology it is not well supported
and not recommended for production. The technology does have Microsoft
supporting it and I believe they intend provide a lot of support to make
this technology viable. Also Blazor is based on WebAssembly which is being
produced by Mozilla another company with a desire to see this succeed.

WebAssembly currently ships with all major browsers and evergreen browsers
which self update support webassembly making it a very widely used package.

Feature List:
-p0 Be able to add pizzas a display them on page without update.
-p0 Total the price of all the Pizzas you have selected.
-p0 Remove pizzas from the shopping cart of pizzas you have.
-p1 Allow user to enter Name and Address for delivery.
-p1 Remove extra task bars to make page work better on mobile.
-p1 Use graphical images for spiciness of Pizza.
-p2 Set up debug mode to allow debugging in browser.
-p2 Demo exporting pizza list in excel document with 'pie' chart.

Technical considerations
c# for front end and server scripting.
Blazor a webassembly package allowing the use of c# to run in html page
