## Python Virtualenv OpenCV setup

**Step 1:**
 - Install Python (preffered way for Mac OsX is brew install python3)
 - Install Pip (Comes with brew installation otherwise install from [here](https://pypi.python.org/pypi/pip))
 - Install Python Virtualenv Virtualenvwrapper with Pip (pip install --upgrade virtualenv virtualenvwrapper)

**Step 2:**
 - Install OpenCV. (There is an excellent explanation on this [web site](https://www.pyimagesearch.com/2016/12/19/install-opencv-3-on-macos-with-homebrew-the-easy-way/). )
 - Install Pip (Comes with brew installation otherwise install from https://pypi.python.org/pypi/pip)
 - Install Python Virtualenv Virtualenvwrapper with Pip (pip install --upgrade virtualenv virtualenvwrapper)

**Step 3:**
 - Create virtualenv for Python Image Processing (mkvirtualenv PyImage) -> This will be saved to your
		 ~/.virtualenvs folder.
 - workon PyImage (In case the virtualenv doesn't workon automatically)
 - Create path between your virtualenv and OpenCV lib in your system. 

		/usr/local/opt/opencv\@3/lib/python3.6/site-packages/ >> ~/.virtualenvs/PyImages/lib/python3.6/site-packages/opencv3.pth

**Step 4:**
 - Check the OpenCV working correctly.
 - $python -> import cv2
 - If there is no problem you're good to go. Otherwise, you haven't fueled your coffee yet. :)
