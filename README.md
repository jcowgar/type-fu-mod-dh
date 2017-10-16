Type Fu Colemak Mod-DH Layout
=============================

Type Fu (http://type-fu.com/) is an awesome typing tutor available as an OS X
application or as an application within Google Chrome for all platforms. It
supports many layouts out of the box including Colemak, but it does not support
the Mod-DH addition to Colemak. Thus, this repository.

![Type Fu Screen Shot](https://github.com/jcowgar/type-fu-mod-dh/blob/master/screen-shot.png)

Installation
------------

First, find your Type Fu installation directory. When installed as an OS X
application, this is in your Applications folder. When installed as an
extension to Chrome, it will be in the personal user data folder for each user.
On Windows, this is your home directory
`%HOME%\AppData\Local\Google\Chrome\User Data\Default\Extensions`. From there
you must search for a known file, such as `proverbs-en.json`.

Once found

1. Place moddh.json in the `frontend\assets\layouts` directory
2. Open `frontend.js` in your favorite text editor
3. Search for 'workman', it should look something like `{id:"workman",label:"Workman"},`
4. Add an enrty before or after that, `{id:"moddh",label:"Colemak - Mod-DH"},`
5. Start Type Fu
6. In Preferences, choose "Colemak - Mod-DH"
7. Begin learning!

Notes
-----

I left the lessons alone, thus you learn the keys in the same order
as the base Colemak layout, which works out well.
