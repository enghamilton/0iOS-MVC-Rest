# 0iOS-MVC-RESTfulJSON
I developed an MVC (model view controller) design pattern using objective C with sdk Cocoa Touch iOS app for iphone on Xcode 7 to a demo for RESTful webservice JSON app.

- M (model) Using from Foundation NSURL Connection (yet deprecated, but works !!!) parsing JSON from a NSString to a NSDictionary iterating objectForKeys to a NSArray.
- V (view) it is a UITableView with includes a UIAlert that shows the JSON parsed. Made in MainStoryboards Scenes.
- C (controller) the viewcontroller that receives data by a Protocol and Delegate to show info on the AlertView.
