# AutoFilter spec

## Concepts

In Excel, an AutoFilter can be applied to a specific worksheet so that the data can be filtered. The same concept also applies to Table object, which says when the talbe is created, an AutoFilter Object is created and attached to it automatically.

## Scenario examples
With auto filter APIs, add-ins can 

1. Create an AutoFilter object.
2. Apply an AutoFilter to a range. (Range.applyAutoFilter())
2. Apply an AutoFilter to a worksheet. (Worksheet.Range.applyAutoFilter())
3. Apply an AutoFilter to a Table. (Table.getRange().applyAutoFilter)
4. Get the AutoFilter from worksheet. (Worksheet.autoFilter)
5. Get the AutoFilter from Table. (Table.autoFilter)
6. Get the AutoFilter mode of a worksheet. (Worksheet.autoFilterMode)
7. Set the drop down triangle to be visible/invisible. (Worksheet.showFilerButton())
8. Clear the AutoFilter on a worksheet. (Worksheet.AutoFilter.showAllData())
9. Update the filters in a worksheet. (Worksheet.AutoFilter.applyFiler())
10. Enable the AutoFilter function when worksheet is protecrted (Worksheet.enableAutoFilterInProtection)

## Open issues



