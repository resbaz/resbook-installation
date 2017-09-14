Natural Language Tool Kit (NLTK)
====

You will need one gigabyte of harddisk space


Setup Apple Mac
----

1. Open the Terminal

2. Download setup script that will install Miniconda, Jupyter and NLTK (copy and paste the command)

```sh
curl  https://raw.githubusercontent.com/doylek1/NLTK/master/setup-mac.sh  --output /tmp/setup-mac.sh
```

3. Run the setup script (copy and paste the command)

```sh
sh /tmp/setup-mac.sh
```

4. When asked `proceed (y/n)`, then type `y` and hit `ENTER` key
  This will take a few minutes.
  When downloading is complete, your computer is successfully setup to do work.

5. Open a new terminal window

6. type `jupyter-notebook` in command line and hit `ENTER` key

7. This will open Jupyter notebook in a new internet browser window


If for any reason, you need to re-install Miniconda (eg. broken download), then delete the minconda directory and try again

```sh
rm -rf ~/miniconda/
```

## Setup Ubuntu

1. Open the Terminal

2. Download setup script that will install miniconda, Jupiter and NLTK (copy and paste the command)

```sh
wget -O /tmp/setup-ubuntu.sh https://raw.githubusercontent.com/doylek1/NLTK/master/setup-ubuntu.sh
```

3. Run the setup script (copy and paste the command)

```sh
sh /tmp/setup-ubuntu.sh
```

4. When asked `proceed (y/n)`, then type `y` and hit `ENTER` key
  This will take a few minutes.
  When downloading is complete, your computer is successfully setup to do work.

5. Open a new terminal window

6. type `jupyter-notebook` in command line and hit `ENTER` key

7. This will open Jupyter notebook in a new internet browser window

If for any reason, you need to re-install Miniconda (eg. broken download), then delete the minconda directory and try again

```sh
rm -rf ~/miniconda/
```

## Setup Windows

1. Download the `python 3 exe installer` from https://conda.io/miniconda.html
  (If you are not sure and you are using windows 7, 8, 9 or 10, then download the 64-bit exe installer)

2. Run the exe installer and install using default choices by clicking next.
  (The installation might take a few minutes if the computer is slow, you can click "Show Details" to see the installation progress.)

3. When installation is complete, find and open a program called `Select Anaconda Prompt` from the Windows Start Menu.

  This will open a new window with a black background (it might keep blinking if the computer is slow).  Wait until you can start typing

4. Type `conda install jupyter nltk beautifulsoup4` and hit `ENTER` key.
  When asked do you want to proceed, type `y` and hit `ENTER`.

  This will take a a few minutes to download Jupyter and NLTK.

5. When download is complete, you may wish to change directory by your home directory so that Jupyter notebooks can be opened and saved in your home directroy.
  Change directory by entering `cd c:\users\myUsername` and `c:`

6. Type `jupyter-notebook` and press `ENTER` key.
  This will start Jupyter notebook in the default browser.
  It might open in Internet Explorer.
  If you prefer to use Chrome or Firefox, then you need to change the windows settings to use Chrome or Firefox as the default browser.

