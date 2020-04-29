#### Creating a Catalog
_via github_
1. Sign up for GitHub url: https://github.com/join?source=header-home
2. Create a new **public** Repository  
![new_repo](https://raw.githubusercontent.com/haensDaempf/SessionMods/master/docs/img/new_repo.png "Create new Repository")  
3. Make sure to set it to public and initialize with README  
![repo_settings](https://raw.githubusercontent.com/haensDaempf/SessionMods/master/docs/img/public_repo_settings.png "Public Repository Settings")  
4. Now you can upload (or simply drag) your mod folders (Make sure you include a Screenshot besides the *.uasset, *.uexp an optional *.ubulk file so people can see how the mods looks ingame)
5. The Upload might take some time, once it´s finished Click `Commit changes`
6. Now you have your mods uploaded to a public server, time to create the catalog via `SessionModManager`
7. Go to the *Asset Store* Tab, Click *Manage Catalogs* then *Create Catalog*  
![create_catalog](https://raw.githubusercontent.com/haensDaempf/SessionMods/master/docs/img/create_catalog.png "Create Catalog")  
8. The *Catalog Creation Tool* needs some information in order to produce a usable *.json for your catalog
  - `Asset ID`: the actual filename of the archive containing the *.uasset, *.uexp an optional *.ubulk file
  - `Author`: your nickname
  - `Name`: the name of the asset as displayed in the *Asset Store*
  - `Version`: version of the asset
  - `Category`: category of the mod (i.e. session-decks, session-wheels, etc.)
  - `Image Url`: the raw link to the uploaded screenshot, you get this one by opening the image in your browser in GitHub and right clicking it.
                 in the context menu select *Copy Image location*, paste this into the *Image Url* field (the format should be something like: `https://raw.githubusercontent.com/YOURUSERNAME/YOURREPOSITORY/master/...`)  
  - `Download Type`: since we´re using GitHub as a host for the files you need to select *Url*
  - `Url`: This is the raw path to the archive (*.zip or *.rar depending on your selection).  
           Navigate to the archive, and copy the *raw* url by right click `View raw` and selecting *Copy Link Location*  
  - `Description`: here you can enter additional information regarding the mod (with which UE Version was it cooked? what original texture is it replacing? and so on..)
  - `Update Date`: you can leave this blank and the Tool will fill in the current date automatically  
  ![create_catalog_dialog](https://raw.githubusercontent.com/haensDaempf/SessionMods/master/docs/img/create_catalog_dialog.png "Create Catalog Dialog")  
9. Finally you can Click `Add Asset` to add the Asset to your catalog
10. Once you are done adding Assets, Click `Export Catalog` to save the data to a *.json file
11. Before uploading open the *.json-file in a text editor and add a Name for the catalog  
![catalog_name](https://raw.githubusercontent.com/haensDaempf/SessionMods/master/docs/img/catalog_name.png "Catalog Name")  
12. Now you´re ready to upload the catalog to GitHub and share the *raw* link to the *.json in the discord
13. Just like before, upload the file, open it in your Browser and Click *Raw* to view the raw json data. Copy the url of the json file and share it.
> NOTE: Here is an example of a catalog url: https://raw.githubusercontent.com/rodriada000/SessionCustomMapReleases/master/DefaultSMMCatalog.json 
