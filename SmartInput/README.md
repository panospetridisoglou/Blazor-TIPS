# SmartInput
![img](https://i.imgur.com/i2WJ0zf.gif)
### About
This is a custom blazor component made for DropDown + Input field.
Very usefull in terms of data entry and user experience

### RoadMap

- [x] Support Custom Dictionary<String,List<String>> so that it can support categories
- [x] Add button to force open dropdown
- [x] Validate data typed according to the ValidationType parameter
- [ ] Hint in the Input field for the first possible answer
- [ ] Add functionality for more than one selection
- [ ] (Optional) add image on items in dropdown

### Examples
  ```
  <h3>Smart Dropdown</h3>
  <BlazorApp2.Client.Components.SmartInput Validate="true" ValidationType="SmartInput_ValidationTypes.Type_inList" Dropdown_List="countries" Input="@input1" isValid="@valid1" />

  {
  Dictionary<String, List<String>> countries = new Dictionary<String, List<String>>();
    private static List<String> greece = new List<String>() { "Athens", "Thessaloniki", "Crete", "Piraeus", "Sparta" };
    private static List<String> france = new List<String>() { "Paris", "Lyon" };
    private static List<String> spain = new List<String>() { "Madrid", "Barcelona", "Seville" };
    countries.Add("Greece", greece);
    countries.Add("France", france);
    countries.Add("Spain", spain);
  }
  ```
  ```
  <h3>Smart Email</h3>
<BlazorApp2.Client.Components.SmartInput Validate="true" ValidationType="SmartInput_ValidationTypes.Type_Email" Input="@input2" isValid="@valid2" />

  ```
