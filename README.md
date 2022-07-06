# Tanks-unity

Tanks tutorial from https://unity3d.com/learn/tutorials/projects/tanks-tutorial

Unity version 2021.3.5f1

Scripting Runtime Version: .NET 5.0

You need git-lfs to download this repo properly. See the section below. 


Simply fork this repository and work on it. You are required to complete several tasks as stated in this [handout](https://docs.google.com/document/d/1xu4x60q5HXakWQ7pQ3ntJRZxRMAFq8s9g2o2I3E7s64/edit?usp=sharing). Copy it and fill it up, then export in `.pdf` format to submit in eDimension. Due date can be found in eDimension. 

# Using git-lfs
Some of the files in this repo is very large. Github blocks pushes that are larger than 100MB. Therefore we used git Large File Storage instead. When you `clone` the repository, it will download only references to the file. 

Install `git-lfs` (click [here](https://git-lfs.github.com) for info or search online). Then, you need to run the following:
```
git lfs install
```

After you run the above command, you can clone this repo accordingly with all the assets downloaded. If not, you can `cd` to the repo directory and run:
```
git lfs fetch -all
git lfs pull
```

The above should download ALL required files to your computer as local copy. You can test by opening `50033-tanks/Assets/Sprites/Aim Arrow.png` file and check that you can indeed open an arrow png file.
