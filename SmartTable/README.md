# Smart Menu
![img](https://i.imgur.com/KMoEQty.gif)

### About
This is your well known standard Html table but on steroids.
It supports resisable columns , sorting columns and editable and read only mode and more to come.
You can use it as a component in blazor and bind your List<object> in it and dynamically change the data on user input.


### RoadMap

- [x] Basic Style and theme
- [x] Automatic Table generation based on the first element of the list given as Data
- [x] Sort each column dynamically and keep it in memory
- [x] Show all standard types of elements
- [x] bind list in table and automatically trigger event OnDataChange
- [x] custom table class choice
- [ ] implement Validation of data for each cell
- [ ] add filters for each column and store to memory
- [ ] implement functionality for clicking row on read only tables
- [ ] implement functionality for clicking  cell on all tables
- [ ] implement functionality to add more rows
- [ ] (Optional) implement SmartDropDown in editable tables for enumerations


### How to add it to your project

Add the cs file in your models folder and use it in the blazor SmartTable component
Copy paste the css file in your css file , or include it 
and whenever you want to add a table in your page simply add
``` <SmartTable Data="mycustomlist" />```

``` <SmartTable Data="mycustomlist" Editable="true"/>```

Enjoy
