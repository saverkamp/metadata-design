### Viewshare Upload Instructions

[http://viewshare.org](http://viewshare.org)

#### DATA

1) Upload data  

2) Choose the correct data type for each element in the "Type" column. Most will be "text," but you should use "date/time" for dc:date, "URL" for local:url, and "location" for local:coordinates.  

3) Extract multiple values:  
- For each field with repeating values, you will need to "extract lists." First, click the +Add button on the header row above your elements.
- Name your field. This is the name that will display in the interface, so give it a user-friendly name, formatted consistently with how you will rename your all of your other elements (ex. "Subject")
- Choose "List" under "View for Field"
- Select the element you wish to extract values from.
- Select the delimiter pattern (if you followed our class schema rules, you should have used semicolon as delimiter).
- Click "Create"
- Click "Augment" in the header row above your elements. You should see a new field at the bottom with individual values listed as bullets.  

4) If you have locations as strings, you can use Viewshare to attach coordinates. Start with the instructions for extracting lists. (If you have repeating location values, you should extract lists first!):  

- Click the +Add button on the header row.
- Name your field.
- Click "Map"
- Select your element with string locations
- Click Create
- Click "Augment" in the header row above your elements. You should see a new field at the bottom with coordinate data.  

5) Rename your elements for display. Click on the pencil icon next to each field to give it a name suitable for display. (Don't worry about renaming elements you've extracted lists from. You'll use the new element you created in step 3 and disable the original.)  

6) When you've finished, click "Save" in the upper left, and enter a Title and Description for your dataset.  

#### VIEWS

1) To add a view into your data. Click "Build" (next to "Save").  

2) Select a layout. (We'll be using two-column for the class dataset)  

3) Add your widgets. Add whichever you'd like, but for class purposes, the minimum you should add is:  
- Search
- Lists (for each, if applicable: Type, Subject, Genre, Creator, Date, Language, Spatial, Temporal)  

4) Add your views:  
- List -- By default you should already have a List view. Give your list a label and drag and drop your elements in the order you wish them to appear in the item display. You may wish to hide certain elements in this view, such as coordinates. 
- Timeline -- If you included dc:date in your data, add a timeline. Select the appropriate time units, depending on the range of dates in your data. Select a Title under "Timeline Lens Settings." Choose the element you would like to see displayed next to the points on your timeline. (Title is usually a good bet.) Check the elements you would like to display in the pop-up when one clicks on a point on your timeline. 
- Map -- If you included coordinates in your data, add a Map view. 
- Pie Chart -- Add a pie chart.  

5) Click "Show Preview" to make sure your views appear the way you like.  

6) Click Save when you've finished.  

Finally, add the URL to your view to the class wiki (click "Share" in upper right to get URL).
