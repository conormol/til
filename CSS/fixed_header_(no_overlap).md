# Fixed Header With No Overlap

To create a fixed header with no overlap, i.e content below the header is pushed down:

1. Set position of header
2. Create a seperate fixed header class inside the header (position set to fixed).
3. The actual header is now a placeholder for the fixed header. Add the necessary content to the fixed header.
4. Adjust the header's dimensions so it matches that of the fixed header
5. To avoid the header overlaping the content below upon resizing, add media queries to resize the header at the breakpoints. This must be done manually.

