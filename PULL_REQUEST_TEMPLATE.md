## Pull Request Checklist:

* [ ] Have you added an explanation of which icons you've added and why you'd like us to include them?
* [ ] Have you created three versions of each icon across the `svgs`, `appstract-light`, and `appstract-dark` folders?
* [ ] Do all three icons have the same name, except for the file type ending? (For example, `app.svg`, `app.png`, and `app.png`)
* [ ] Is each file name only comprised of lowercase letters, numbers, and underscores? Underscores should be used only to replace spaces.
    - Acceptable names: `hello.svg`, `bye_bye.svg`, `disney_plus.svg`, `numbers_123.svg`
    - Unacceptable names: `spaces everywhere.svg`, `YouTube.svg`, `$%*&^.svg`
* [ ] Have you ensured that all svgs and pngs are 192x192 px with a line width of 6px and a transparent background?

## Icons added

### Template

For each icon added, please add an entry to the pull request (this text) formatted like this:

* App Name (`app_name.svg`) - [New/Redesigned] Icon
```
<item component="ComponentInfo{Activity Name 1}" drawable="app_name"/>
<item component="ComponentInfo{Activity Name 2}" drawable="app_name"/>
...
```

###### Gotchas:
- The name inside `drawable=` must match the name of the file (For example, `orange.svg` would have `drawable="orange"`)
- For help finding Activity Names, please see the [Contributing Guide](https://github.com/mirrorkeydev/Appstract/blob/master/CONTRIBUTING.md)

### Examples

* Camera (`camera.svg`) - Redesigned Icon
```
<item component="ComponentInfo{com.android.camera/com.android.camera.view.CameraActivity}" drawable="camera"/>
<item component="ComponentInfo{com.mediatek.camera/com.mediatek.camera.CameraLauncher}" drawable="camera"/>
<item component="ComponentInfo{com.GoogleCamera.Wichaya/com.android.camera.CameraLauncher}" drawable="camera"/>
<item component="ComponentInfo{com.hmdglobal.app.camera/com.hmdglobal.app.camera.GuideActivity}" drawable="camera"/>
```

* Poshmark (`poshmark.svg`) - New Icon
```
<item component="ComponentInfo{com.poshmark.app/com.poshmark.ui.MainActivity}" drawable="poshmark"/>
```

* Disney+ (`disney_plus.svg`) - New Icon 
```
<item component="ComponentInfo{com.disney.disneyplus/com.bamtechmedia.dominguez.main.MainActivity}" drawable="disney_plus"/>
<item component="ComponentInfo{jp.co.disney.apps.gm.disneyvod/com.ascendon.disney.activity.DJLoaderActivity}" drawable="disney_plus"/>
```
