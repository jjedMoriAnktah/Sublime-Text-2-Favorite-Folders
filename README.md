#Sublime Text 2 Favorite Folders Navigator

*[WIP]*

Plugin to help you navigate through the favorite folders on your project, you can also exclude, create, rename and move folders and files.

In projects using Magento or something like, for example, this can be very useful once the file working tree is giant and many folders has the same name, but in differents places.

You need declare in to .sublime-project wich folders you want be bookmarked inside an array with key "folders", the three items should follow the format: **["Absolute Path to Folder", "Title of Bookmark", "Description of Bookmarked Folder"]**

**.sublime-project example**

```json
{
	"folders": [
		{
			"path": "/Users/samuel/magento_project"
		}
	],
	"settings":
	{
		"FavoriteFolders":
		{
			"folders": [
				["/Users/samuel/magento_project/app/design/frontend/default/my_teme", "My Themes Files", "Files of my theme, lol"],
				["/Users/samuel/magento_project/skin/frontend/default/sprint", "My Themes Assets", "Assets of my Theme"]
			]
		}
	}
}
```