# Solution notes: Inventory

## Approach

I put all items into a hash map using the item name as the key. When the same name appears again, I add the quantity to the existing value. For the summary, I count the number of items and add up all quantities.

## Edge cases handled

- Empty inventories return empty results or zero values.
- Matching names are merged correctly.
- The summary works even when the inventory is empty.

## Anything special

This shows the difference between consuming data with restock and borrowing data with summary.
