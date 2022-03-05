# Package template

## What is it ?
Package template is a template repository to create quickly package for unity.

Unity package allow you to create independents features and include it like puzzle in your unity project to include its features.

This architecture is based on unity package layout presented [here](https://docs.unity3d.com/Manual/cus-layout.html)

I encourage you to create sample that can be imported independently thanks to unity package manager for more modularity.
You can for example create demo, independent feature in your package theme...
Sample folder contain character '~' that mean that this folder will be ignored by unity.
All sample must be referenced in package.json.

Please don't change the license, and don't forget to update your changelog file and package version in package.json.
For clear information about your package, make a demonstration, add description in GitHub and information in README.

## How to create new package ?
Follow these step to create package based on this template:

1: Click on "Use this template" button to create a new repository based on this template.
![Capture d’écran 2022-03-05 210916](https://user-images.githubusercontent.com/55276408/156898721-99195bf3-02c1-41f5-9bc8-483a9b65c55a.png)

2: Select the owner (by default you, if you want to create a package for this repository, please select OpenSourceUnityPackage).
Then enter your project name. You can next add description. When you're finished, select public repository, include all branch (to include git flow) and click on "select repository from template"
![Capture d’écran 2022-03-05 211005](https://user-images.githubusercontent.com/55276408/156898722-cc3bf2aa-b6bd-44a1-9f74-a63d9543d1f1.png)

3: Your package is created ! Before started to create wonderful features, you need to set up it. Action was created to simplify this process. So click on "action"/Setup package and on setup.yml.
![Capture d’écran 2022-03-05 211342](https://user-images.githubusercontent.com/55276408/156898897-60695326-4cab-436e-bc6b-622cc833dcc8.png)

4: Here you need to define your project name according to the unity package nomenclature. So, click on "edit this file" and replace package name in the field "PackageNameField".
![Capture d’écran 2022-03-05 211424](https://user-images.githubusercontent.com/55276408/156898898-897647d3-e189-4fc5-b907-5b547df43a5c.png)

5: Then you need to commit it, so click on "start commit" and on "commit changes" buttons.
![Capture d’écran 2022-03-05 211459](https://user-images.githubusercontent.com/55276408/156898899-c2811232-cd3d-4bf3-be89-bb9c700c212d.png)

6: All is ready to set up your package! So return to action/ Setup package and click on "Run workflow" button. Green check will appear to tell you that setup work. Else, you can see logs to understand what wrong in the process. You can create issue in package template repository if you think that error provide to action. You can editor package.json to include more detail about your package like tags, unity version, description, author...
![Capture d’écran 2022-03-05 211557](https://user-images.githubusercontent.com/55276408/156898900-43be611c-ad43-474b-8d7b-861bedede27e.png)
