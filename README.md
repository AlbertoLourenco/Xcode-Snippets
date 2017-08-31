# Xcode Snippets
Xcode snippets: Objective-C and Swift

Here we have a short documentation of Xcode snippets shortcuts. Follow this steps to import these files and do code more fast:

Open Finder, choose “Go > Go to Folder”:

~/Library/Developer/Xcode/UserData/CodeSnippets

And finally move our “.codesnippet” files to this folder.

------------------------------------------------
	+ IBOutlets
------------------------------------------------

	All IBOutlets snippets have the "ib" prefix and var typ name initials:

	- ibsv: UIScrollView
	- ibcv: UICollectionView
	- ibtb: UITableView
	- ibtv: UITextView
	- ibtf: UITextField
	- ibvw: UIView
	- ibwv: UIWebView
	- ibsw: UISwitch
	- ibst: UIStepper
	- ibpc: UIPageControl
	- ibpg: UIProgressView
	- ibsc: UISegmentedControl
	- ibsb: UISearchBar
	- iblbl: UILabel
	- ibbtn: UIButton
	- ibimg: UIImageView
	- ibact: UIActivityIndicatorView
	- ibmap: MKMapView
	- ibwkv: WKWebView

------------------------------------------------
	+ Delegates / Datasources
------------------------------------------------

	Methods snippets have var type name initials + "m" (methods):

	- vcm: UIViewController
	- tvm: UITableView
	- cvm: UICollectionView
	- svm: UIScrollView
	- wvm: UIWebView
	- sbm: UISearchBar
	- txtvm: UITextView
	- custom: Custom methods

------------------------------------------------
	+ Classes
------------------------------------------------

	Classes snippets are implementations with delegate/datasource and custom methods:

	- tbclass: UViewController + UITableView
	- cvclass: UIViewController + UICollectionView
	- svclass: UIViewController + UIScrollView

	- vccontroller: UIViewController
	- tbcontroller: UITableViewController
	- cvcontroller: UICollectionViewController

------------------------------------------------

As a gift, you can install a new theme for your code following above steps, go to “FontAndColorThemes” folder and paste “ALTheme.xccolortheme” file. Then open Xcode and go to “Preferences > Fonts & Colors” and choose “ALTheme”.
