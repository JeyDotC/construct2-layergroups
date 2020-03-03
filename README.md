# Layer Groups

Allows to create groups layers with these benefits: 

1. Collisions for layers in a group will be completely isolated from the ones of other groups. 
2. You will be able to perform operations on groups of layers, allowing to change properties like opacity or visibility of all layers in a group at once.

# ACES

## Actions

| Name | Description | Params |
|------|-------------|--------|
| **Add layer to group** | Add a layer to the a group | **Layer:** Layer to add, **Group:** Group name to add the layer into |
| **Modify group property** | Alter the selected property for all layers under a group. | **Group:** The group of layers you want to modify, **Property:** The property you want to change, **Value:** The new value for the property |
| **Set group visible** | Change visibility of all layer under a group | **Group:** The group of layers you want to modify, **Visibility:** The new visibility of the layers under the group |

## Expressions

| Name | Description | Params |
|------|-------------|--------|
| **Get group of layer** | The group this layer belongs to | **Layer:** The layer for which you want to get the group |
