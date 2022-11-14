Plan
HTML
On first page
div holds the list of items
render each item once it's fetched from supabase
On second page (details)
create section and div container to hold details
in header on second page, link to home page

Events
Home page loads
fetch all the items from the supabase (dogs)
Display all items
loop through render and append to container
second page - detail page load
fetch single item from supabase(by id)
render page based on items info
use URLSearchParams to get the items.

    Functionality
        fetch-utils -> getitem, getitemById
        render-utils -> renderItemCard, renderItemDetail

Slices (order to code in)

1. get all items to render to home page on load
2. make item cards clickable and have them redirect to detail page
3. get detail page to render with appropriate deatils (hard coded ID)
4. use URLSearchParams to fill in id dynamically
