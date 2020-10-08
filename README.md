This is a fork of https://github.com/bricata/material-table

Changes made:

1. Removed DragDropContext from the main table
1. Added ability to add/remove a column from code
1. Changed behavior of hiddenByColumnsButton - now it's used to set visibility in the columns selector regardless of column 'hidden' state. When you add/remove columns it's reset to true/false respectively.
1. Added callback for query changed
1. Bug fix - table was breaking when showing columns that were initially hidden https://github.com/mbrn/material-table/issues/2414
