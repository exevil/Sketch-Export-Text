# Export Text Sketch Plugin
Export Text plugin should help you to save all text data on current page in customizable format and filter the excess.

## Setting up
<img src="http://i.dbv.ae/iFC9/Screen%20Shot%202016-11-27%20at%2022.36.45.png" height="506">

* **Use Last Settings** — restoring settings you used previously
* **Text Length** — excluding layer from output if it's text length is more or less than provided values
* **Skip Layers** — skips any layer, artboard or symbol with given name. Enter any names you wanted to skip separated by comma and space e.g. `Rectangle 1, Screen 2, Symbol 3`.¹
* **Before Artboard Divider** — adding a divider before next artboard. Empty line by default. You can add more lines by using `⌥ + return`
* **Show Artboard Name** — adding an artboard name before its contents
* **After Artboard Divider** — adding a divider between artboard name and its contents. Empty line by default. You can add more lines by using `⌥ + return`
* **Save to:** — choose how you'd like to save an output

*1. Please keep in mind that if you used symbol with skip-name as override or just added it as an instance to another symbol's master then contents of this instance or override (not the whole symbol) also will not be added to output. It's really confusing so please double check your symbols data if you want to use this function.*

## Example Output
![](http://i.dbv.ae/iEkn/Screen%20Shot%202016-11-25%20at%2020.33.10.png)

## Upcoming Features
- [x] Filter by layer name
- [ ] Optionally include layer names
- [ ] Error state if output is empty
- [ ] Show exporting process progress
- [ ] Filter by string contents
- [ ] Export as JSON
- [ ] Export as .plist
- Advanced filter by layer name (by starts/ends with and containing) *— done but removed because may confuse*

## Feedback
Your feedback is always appreciated. You can [Create an Issue](https://github.com/exevil/Sketch-Export-Text/issues/new) to report errors and feature requests or drop me a line directly to [m@dbv.ae](mailto:m@dbv.ae?Subject=Sketch%20Export%20Text%20Feedback)

## Donation
Even a small donation from your side is important. This is really motivating to see that people want to pay for your work.

[![](https://www.paypalobjects.com/en_GB/i/btn/btn_donate_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=evil%2emrfix%40gmail%2ecom&lc=GB&item_name=Sketch%20Plugin%20Donation&item_number=sketch%2dplugin&currency_code=USD&bn=PP%2dDonationsBF%3abtn_donate_LG%2egif%3aNonHosted)
