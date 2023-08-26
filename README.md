# SpikeborFreebies
Free Unity Editor Tools

Hello, This tool should be freely used and published on the Unity Asset Store,
but the queue is too bad (2424) so I decide to publish a github for it.
This is a collection of useful tools that I will use in my Unity Tutorial series, so
it's a good idea to share it freely for my viewers to follow along!

What you will find in this package:

SpikeBookmark
- ScriptableObject: Create in your project by Right Click > Create menu > Spikebor Freebies>Create Bookmark
- With SpikeBookmark you can bookmark objects in your Project. You don't need to move
anything to be organized. For example, put all your favourite punches animation in your bookmark file named GreatPunches, then when you want to export those punch anims to another Project, simple hit Select, and you are now selecting all of them, ready to Right Click > Export Package > un-check the dependencies, then your punches are exported nicely. All this happen without the need to create new Folder and drag your punches into it.
Recommend use this to organize your Project instead of moving files around. It's very strictly applied to AssetStore assets. Because many of them don't like to be moved around, they have some
hard references using string for directory in their script. 

SpikeBookmark Window
- EditorWindow : On the top menu bar, go to Tools/SpikeborFreebies/Spike Bookmarks Window
- Use this instead of creating SpikeBookmark file if you only want to temporarily use this feature. Believe me, you need to use bookmark a lot in your workflow.
For example when you switch a material to another shader, the new shader may make you lose all the textures references. Bookmark them first, then the headache is gone.

SpikeNote
- Component: Help in development
- Can put anywhere in your GameObjects in the scene.

SpikeNoteFile
- ScriptableObject: Create in your project by Right Click > Create menu > Spikebor Freebies>Create Note
- No longer scene bound. You can write note anywhere in your Project.

Quick Set Parent
- EditorWindow : On the top menu bar, go to Tools/SpikeborFreebies/Quick Set Parent Window
While working with a long ass Hiearchy, imagine if you have to parent a bunch of objects scatter around to one new parent? That would be a nightmare.
Not anymore with Quick Set Parent window.
Just select them childs, click OnBoard and see their name in the Editor Window.
Click the Parent > click Set Parent, no more long distance drag and drop.
You can have the option to resetRot and resetPos to zero out position / rotation of the childs if needed.

File Mover
- EditorWindow : On the top menu bar, go to Tools/SpikeborFreebies/File Mover Window
Same idea with Quick Set Parent, but for files in your project.
If your project is huge, drag a bunch of folders to a new destination can be a nightmare. You can easily drag wrongly to a different location.
Not anymore with File Mover.
Same interface as Quick Set Parent, just select the child Folders, click Onboard.
Click the new parent, click Select Folder > then Click Move To button and you're set.

I do not hope you to have better Editor experience with this package, because you definitely will have! Those are great Utility Tools. Have fun, happy dev-ing!
