# In browser test recording

Goals:
* Think SeleniumIDE, but should be much much better ..
* Reliablity is most important here, all other factors have reduced priority

This might require more space for storing tests themselves
because we're going to store some images.

Generally I expect this to be slower on replay, but we'll see if it's reasonable once PoC is made.

Query locators will be supported, but first class locator is actual element image.

We also won't do browser extension as it seems to limited based on my experience doing some changes to SeleniumIDE.
Maybe direct recorder injection via Selenium ( so our app and tested app would be in the same context ), or something like that... concept is not yet in solid, but we at least know what we won't do.


Will be written in Rust maybe, we'll see.
