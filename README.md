# sarmsui
Copy from SB-admin bootstrap theme. :P

Click >> https://jiradawi.github.io/sarmsui/

# Design Flow and Explanations
## In every pages
- Scrolling down will activate "back to top" button at the bottom right of the page. Click to navigate back to top.
- All nav bar are fixed.
- All datable are Bootstrap datable. The document can be found here >> https://datatables.net/examples/styling/bootstrap4
- All date input was changed from boring input to Bootstrap date picker. With this date picker, the result will be the same in every browser.

## First page: index.html >> https://jiradawi.github.io/sarmsui/
- Showing notifications on the top. Using animation to catch user eyes.

## Sogo Page: sogo.html >> https://jiradawi.github.io/sarmsui/sogo.html
- Decrease column of table by adding more info button. Separate data by color, red and blue. Easier to notice which one are on urgent.
- Also showing notification at the top. Using animation to catch users' eyes.

## Hardware page: daicho.html >> https://jiradawi.github.io/sarmsui/daicho.html
- Hiding search bar at the top of the page.
- Decrease number of column by adding "info" button. Click info button to reveal more data and more action.
### Hardware edit: hardwareedit.html >> https://jiradawi.github.io/sarmsui/hardwareedit.html
- Click edit/appedit to access hardwareedit page.
- Hiding all input description in dropdown box. Click to read.
### Hardware edit with warning: hardwareeditinvalid.html >> https://jiradawi.github.io/sarmsui/hardwareeditinvalid.html
- Click submit at hardwareedit page to visit page.
- Add red color and description at input box. Showing red warning at the top.
- If everything are OK, click submit to show hardwar =e edit result as a modal.

## Software page: softwaredaicho.html >> https://jiradawi.github.io/sarmsui/softwaredaicho.html and
## License page: licensedaicho.html >> https://jiradawi.github.io/sarmsui/licensedaicho.html
- Move ALL action to more info button. Save a lot of space.
- Register software page is available but nothing change from hardware edit page. If you want to see... >> https://jiradawi.github.io/sarmsui/registersoftware.html

## Import page: import.html >> https://jiradawi.github.io/sarmsui/import.html
- Make a example file a little bigger. At first, I though it was an error warning. T T

There are a lot more page that I've done but those pages have no interesting design idea. You can explore them.



*************************************************************
# File Added
- Located in dev_src/public/theme/default/css/ui/orm
  - Bootstrap, both CSS and JS
  - jquery
  - animate.css
  - font-awesome
  - dataTables
  - All SB-admin Template

# File Modified
- Header of each view, import all files above.
- All views, add content into <div class="card"></div>


# Credit and Mlre Information
Without these websites, my life is a disaster.
- Bootstrap4  >> https://getbootstrap.com/
- SB Admin Template >> https://startbootstrap.com/template-overviews/sb-admin/
- Bootstrap data table >> https://datatables.net/examples/styling/bootstrap4
- Animate.css >> https://daneden.github.io/animate.css/
- Icon >> https://fontawesome.com/icons?d=gallery
- Date time picker from bootstrap >> https://bootstrap-datepicker.readthedocs.io/en/latest/
Look much better then the old one. :D
