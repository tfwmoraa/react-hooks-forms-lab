# TODO: Fix Failing Tests in React Hooks Forms Lab

## Steps to Complete
- [ ] Update ItemForm.js: Add state for name and category inputs, implement form submission handler to call onItemFormSubmit with new item object, and reset form after submission.
- [ ] Update Filter.js: Accept 'search' and 'onSearchChange' props, make the input controlled with value={search} and onChange={onSearchChange}.
- [ ] Update ShoppingList.js: Add search state, pass search and onSearchChange to Filter, update itemsToDisplay to filter by search term (case-insensitive partial match) in addition to category.
- [ ] Update App.js: Add handleAddItem function to update items state with new item, pass onItemFormSubmit to ShoppingList.
- [ ] Run npm test to verify all tests pass.
