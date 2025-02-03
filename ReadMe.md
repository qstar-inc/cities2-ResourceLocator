﻿# Resource Locator
New info view to locate buildings where resources are required, produced, sold, and stored.

# Description
With this info view, you can:
- View where your city's resources are located according to how the resources are being used:  required, produced, sold, and stored.
- View detailed information for each resource, including how it is obtained and how it is used.
- View storage amounts for buildings that require, produce, sell, and store each resource.
- View production/surplus/deficit rates for buildings that produce or consume each resource.
- View individual districts.
- View individual resources.

### District Selector
If your city has districts:
- The District Selector is visible.
- Resource locations are for the Entire City or for buildings in a single selected district.
- Districts are listed alphabetically.
- The default is Entire City every time a game is started.

If your city has no districts:
- The District Selector is hidden.
- Resource locations are for the Entire City.

### Display Option
- The Requires, Produces, Sells, and Stores options show buildings that require, produce, sell, or store a selected resource.
- These options match the game's building information when you click on a building.
- The color of each building indicates that the corresponding selected resource is being used by that building according to the selected Display Option.
- Most resource colors match the resource icon.
- Only one Display Option can be selected at a time.

### Resource Selection
- You can select all or deselect all resources.
- You can select and deselect individual resources.
- To view only one resource, deselect all resources and then select only the one resource you want view.
- The Resource Selections are grouped and ordered the same as on the Production tab of the City Economy view.

### Detailed Resource Information
Hover the cursor over a resource to get detailed information about that resource:
- Where this resource comes from, including other resources required to produce this resource.
- Which other resources are produced from this resource.
- Other uses of this resource (e.g. Electricity, Heating, Upkeep, etc.)
- Whether this resource can be imported/exported or the resource is available only locally.
- Current amount stored in buildings that require, produce, sell, or store this resource.
  Storage is for the selected district.
  If the Options settings are turned on, resources produced in special case buildings are included in: Storage - Produces.
  If the Options settings are turned on, resources stored in special case buildings are included in: Storage - Stores.
- For each Display Option, current amount stored is also shown in an orange bar behind the resource name.
  The resource with the largest amount stored has a full bar and the other bars are sized relative to that one.
- Current production rate and surplus/deficit rate of this resource.
  Rates are for the entire city, even if a district is selected.
- For the Produces Display Option, the production, surplus, and deficit rates are also shown in the blue, green, and red bars behind the resource name.
  The resource with the largest production, surplus, or deficit has a full bar and the other bars are sized relative to that one.
- Most of the above is the same information available on the Production tab of the City Economy view.

### Buildings With A Single Resource
- If a building requires, produces, sells, or stores only one resource, the building color is set according to that resource.
- A building can sell only one resource.

### Buildings With Multiple Resources. 
- Many buildings require more than one resource.
- Most buildings produce only one resource (exception is Recycling Center).
- Most buildings store only one resource (exception is cargo transport buildings).
- If a building requires, produces, or stores more than one resource, the building color is set according to the top selected resource.
  For example, Steel requires both Coal and Metals.
  If the Display Option is Requires and both Coal and Metals resources are selected,
  then a building that produces Steel is colored for Coal because Coal is higher in the list than Metals.
- To view these buildings in their other color(s), deselect the top resource of the building.

### Special Case Buildings
Most buildings that require, produce, sell, and store resources are commercial, industrial, and office companies.
Some resources are produced in buildings other than companies.
Some resources are stored in buildings other than warehouses.

The special case buildings are:
- Recycling Center - Produces from garbage: Metals, Plastics, Textiles, Paper
- Coal Power Plant - Stores for its own use: Coal
- Gas Power Plant - Stores for its own use: Petrochemicals
- Medical Facility - Stores for its own use: Pharmaceuticals
- Emergency Shelter - Stores for its own use: Food
- Cargo Transport Station - Stores multiple resources that can be used by the city and imported/exported.
  Buildings include:  Cargo Train Terminal, Cargo Harbor, Airport with the Cargo Terminal upgrade, and International Airport.

### Excluded Buildings
Abandoned, condemned, deleted, and destroyed buildings are excluded.

# Options
The following settings are available on the Options screen.

### Include Special Case Buildings
You can choose to include or exclude (default) special case buildings.
The special case buildings are listed above.

When a special case building is included:
- Building color is set according to the selected Display Option and selected resources.
- Resources produced at the building are included in Storage - Produces.
- Resources stored at the building are included in Storage - Stores.

# Compatibility
The mod is translated into all the languages supported by the base game.

There are no known compatibility issues with any other mods.

This mod can be safely disabled or unsubscribed at any time.

# Possible Future Enhancements
Here are some possible future enhancements that were thought about during development but not included initially:
- Allow the player to locate buildings for selected resources by showing an icon above each building.
- By default, the game turns on all resources each time the infoview is displayed.
  Save the selected resources to be used the next time the infoview is displayed.
  Possibly do this as a separate mod for all infoviews, not just for the infoview for this mod.

# Acknowledgements
The following mods were used extensively in the development of this mod:
- Scene Explorer by krzychu124
- Extended Tooltip by Mimonsi
