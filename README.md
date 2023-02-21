# python-wheels
I recently had troubles to install python packages which doesn't have a precompiled wheel
for my python version, when the build process starts it fails with a "You need MS VC++ 14" error message.
Well, I don't want to download 5Gb of programs and tools and not use them at all, so I set up an Action
to build the wheels. Now all I need to do is modify requirements.txt, push changes and voilà! Fresh wheels for you!
